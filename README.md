<img src="./assets/logo.png" align="left" title="CTI app logo" alt="App Logo" width="80px" height="80px">

# Events Viewer App

The Events Viewer App is a Zendesk App that allows agents to view all Sunshine user events related to a user in a timeline. The app can be set to filter events by keywords, and lets agents search through or sort events, and view the attributes of a specific event on the ticket or the user's profile.


<p align="center">
    <img src="https://cl.ly/e39dfbb6661a/Screen%252520Recording%2525202019-06-26%252520at%25252009.58%252520am.gif" width="600px">
    <img src="https://cl.ly/96e1d10c305b/download/Screen%252520Recording%2525202019-06-26%252520at%25252009.59%252520am.gif" width="250px">
</p>

## App location

* User sidebar
* Ticket sidebar
* New ticket sidebar

## Features

* View list of user events on a user profile and ticket sidebar, including event description and creation date
* Filter list of user events by keywords
* Search for events based on description, date, source or type
* Sort list of events by name or date
* View event details (attributes)

## Using the app

### Prerequisites

* You must be on Zendesk Professional plan or above to be able to install private apps
* The User Events API is currently in Early Access. To enable the EAP, go to Zendesk Support > Admin > Manage > Sunshine > Settings and enable Events & Profiles API

### Getting started

Simply download this project as a ZIP file and upload it as a private app
To create the events, please refer to the Sunshine API documentation to [track events](https://developer.zendesk.com/rest_api/docs/sunshine/events#track-event)

### Settings
You can update the settings below to customise the app's behaviour: 

* Default description: define a default description for events with no description
* Keywords: define one or more comma-separated keywords for the app to show only events related to those keywords

## Known Issues & Limitations

* The app displays only events tracked against the support profile of a user
* Event creation date is is showing in GMT+0
* Attributes longer than sidebar width don't get wrapped around
