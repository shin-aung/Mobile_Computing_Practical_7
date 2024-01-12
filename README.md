# Mobile_Computing_Practical_7

**Learning Journey: Creating Spirit-Level App with Android Sensor API and Custom Views**

In a dedicated session of approximately 3 hours, I worked on developing a Spirit-Level App, leveraging Android Sensor API and creating a custom view. The following is a breakdown of my tasks and experiences.

**Task 1 - Setup the Project and Explore the Gravity Sensor:**

Created a new project "SpiritLevel" with a minimum SDK level of 21.

**Set up boilerplate code for one activity.**

Successfully retrieved the list of all sensors and default gravity sensor using the provided code.
Question: Handled the scenario where no gravity sensor is available by providing a user-friendly message or a default action.
Implemented SensorEventListener for the default gravity sensor in MainActivity, monitored sensor events, and logged values.
Utilized onResume() and onPause() to register and unregister the sensor listener.
Handled onSensorChanged() and onAccuracyChanged() callbacks to manage sensor data.
Tested the app on an emulated device, modifying the emulated data using Extended Controls.

**Task 2 - Create a Custom View and Display Sensor Data:**

Added a SpiritLevelView class derived from android.view.View with a two-parameter constructor.
Handled onSizeChanged() to compute the center and dimensions of SpiritLevelView.
Overrode onDraw() to draw a "bubble" representing the spirit level's position based on sensor data.
Implemented a helper method to adjust the bubble's position based on gravity sensor data percentages.
Used View.invalidate() to force the view to redraw itself.

**Task 3 - Self-Reflection:**

**Description of the Experience:**

Engaging in this exercise allowed me to explore Android's Sensor API and gain practical experience in creating a custom view.

**Feelings and Thoughts about the Experience:**

The integration of sensor data into a custom view was fascinating, providing a visual representation of real-world data. Challenges were encountered in fine-tuning the bubble's position.

**Evaluation of the Experience, Both Good and Bad:**

Positive aspects included successfully handling sensor data and creating a dynamic visual representation. Challenges included the need for precise positioning of the bubble.

**Analysis to Make Sense of the Situation:**

Working with sensor data introduced a practical dimension to app development. Fine-tuning the bubble's movement requires a nuanced understanding of sensor values.

**Conclusion about What I Learned and What I Could Have Done Differently:**

Learned the practical implementation of Sensor API and custom views. In retrospect, exploring alternative strategies for bubble movement may enhance accuracy.

**Action Plan for Future Situations or Changes:**

Future focus will involve mastering alternative strategies for adjusting the bubble's position and exploring advanced sensor functionalities.
