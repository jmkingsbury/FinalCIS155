# FinalCIS155
HydrateMe App
Open the project in Android Studio:

Open Android Studio, click on Open an existing project, and select the directory where the project is saved.

Build the project:

Once the project is open, click Build > Make Project to compile the code.

Run the app:

Select your target device (either an emulator or a physical device) and click Run to start the app.

App Structure
MainActivity.java
Main screen where users can set a water intake goal, log water consumption, and view their progress.

Displays a visual jug that fills up as the user drinks more water.

Allows the user to set their intake goal and reset their daily intake.

CalendarActivity.java
Displays the history of water intake in a list format.

Shows how much water the user drank on different days.

Layouts
activity_main.xml: Layout for the main screen with buttons for adding water, resetting, saving the goal, and opening the calendar.

activity_calendar.xml: Layout for the calendar history view, where users can see their daily water intake history.

Usage
Set Your Daily Goal:

Enter your desired daily water intake goal in the "Set daily goal" text box.

Choose the unit (ml or oz) from the radio buttons.

Press the "Save Goal" button to save your goal.

Log Water Intake:

Each time you drink a glass of water, tap the +250 button to add 250 ml of water (this can be changed if needed).

The progress bar (jug) will fill up based on how much you've consumed.

View Your History:

Tap the "View Calendar History" button to see your daily water intake history.

The app will display the amount of water you consumed each day.

Reset Daily Intake:

If you want to start fresh, tap the "Reset Today" button to reset your daily intake.

Enable Reminders (Optional):

Set up reminders to help you stay hydrated throughout the day. This feature can be added in the future, but it's currently a placeholder.

App Preview
The app shows a progressive visual jug that fills up based on the user's intake. It also provides daily history tracking, making it easy for users to see how much water they've consumed over time.

Future Enhancements
Notifications/Reminders: Automated reminders to drink water at specific intervals.

Charts and Statistics: Graphs to display your hydration trends over time.

Dark Mode Support: A theme that adjusts for low-light environments.

Cloud Syncing: Sync data across multiple devices using Firebase or a similar service.

Contributing
If you'd like to contribute to the project, feel free to fork the repository and submit a pull request. You can contribute in various ways:

Bug fixes

Feature additions

Documentation improvements

License
This project is licensed under the MIT License - see the LICENSE file for details.
