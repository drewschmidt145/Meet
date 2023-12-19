# Meet

An application that uses Google Calendar API to fetch upcoming events

## Description

This application uses a the Google Calendar API to fetch upcoming events. It will list and give details about these events and give easy access to all of the information.

## Feature 1: Show Hide Event Details

### User Story: Viewing Event Details

Given: The user is logged into the Calendar App and has events scheduled.

When: The user clicks on a specific event on the calendar.

Then: The event details should be displayed, showing information such as event name, date, time, location, and any additional notes.

### User Story: Hiding Event Details

Given: The user is viewing event details on the Calendar App.

When: The user clicks on a "Hide Details" button or an area outside the event details.

Then: The event details should be hidden, returning the user to the main calendar view.

### User Story: Toggle Event Details

Given: The user is viewing the event details on the Calendar App.

When: The user clicks on the same event again or clicks on a "Toggle Details" button.

Then: The event details should toggle between being shown and hidden, providing a seamless way for the user to switch between views.

## Feature 2: Specify Number of Events

### User Story: Setting Default Number of Events

Given: The user has just installed the Calendar App and has not listed any specific preferences.

When: The user opens the Calendar App for the first time.

Then: The default number of events displayed should be set to 32.

### User Story: Changing Number of Events to Display

Given: The user is using the Calendar App and wants to adjust the number of events displayed.

When: The user navigates to the settings or preferences section of the app.

Then: The user should find an option to specify the number of events to display and can set a custom value (e.g., 10, 25, 50, etc.).

### User Story: Viewing Specified Number of Events

Given: The user has set a custom number of events to display in the app preferences.

When: The user returns to the main calendar view.

Then: The calendar should show the specified number of events, and a scrollbar or pagination feature should be available if the total number of events exceeds the specified limit.

## Feature 3: Use the app when Offline

### User Story: Offline Mode

Given: The user is using the Calendar App and loses internet connectivity.

When: The user attempts to access or modify calendar settings.

Then: The Calendar App should detect the lack of internet connectivity and switch to offline mode, allowing the user to view and interact with locally stored events. Any attempt to modify settings requiring internet access should display a notification or message indicating the offline status.

### User Story: Changing Search Settings Offline

Given: The user is in offline mode in the Calendar App.

When: The user attempts to change search settings, such as the city or the number of events to display.

Then: The Calendar App should display an error message informing the user that these settings cannot be modified while offline. The app should guide the user to reconnect to the internet to apply changes.

### User Story: Error Handling for Connection Loss During Search Setting Change

Given: The user is actively changing search settings in the Calendar App.

When: The user loses internet connectivity during the process.

Then: The Calendar App should display an error message indicating the connection loss and inform the user that the changes may not be applied until a stable internet connection is restored.

## Feature 4: Add an App shortcut to the home screen

### User Story: Adding App Shortcut

Given: The user has the Calendar App installed on their device.

When: The user opens the Calendar App and navigates to the settings or options menu.

Then: The user should find an option to "Add Shortcut to Home Screen."

### User Story: Creating Home Screen Shortcut

Given: The user is in the Calendar App and has selected the "Add Shortcut to Home Screen" option.

When: The user follows the prompts or confirms the action.

Then: The Calendar App should create a shortcut icon on the device's home screen for quick access to the app.

### User Story: Accessing Calendar from Home Screen Shortcut

Given: The user has added a shortcut to the Calendar App on their device's home screen.

When: The user taps on the Calendar App shortcut.

Then: The Calendar App should launch directly, providing convenient and quick access to the calendar without having to navigate through the device's app menu.

## Feature 5: Display Charts Visualizing Events Details

### User Story: Viewing City-Based Event Chart

Given: The user has events scheduled in different cities in the Calendar App.

When: The user navigates to the "Charts" or "Analytics" section of the app.

Then: The app should display a chart that visualizes the number of upcoming events in each city. Each city should be represented on the chart, and the user can easily interpret the data to see event distribution across cities.

### User Story: Interacting with the City-Based Event Chart

Given: The user is viewing the city-based event chart.

When: The user interacts with the chart, such as tapping on a city or using gestures.

Then: The app should provide additional details or options, such as displaying a list of events for the selected city or allowing the user to customize the time range for the chart.

### User Story: Updating the City-Based Event Chart in Real-Time

Given: The user has the Calendar App open and new events are added or existing events are modified.

When: A change occurs in the events data.

Then: The city-based event chart should update in real-time, reflecting the latest changes in the number of upcoming events in each city.

