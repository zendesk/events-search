<img src="./assets/logo.png" align="right" title="CTI app logo" alt="App Logo" width="70px" height="70px">

# Events Viewer App

The Events Viewer App is a Zendesk App that allows agents to view all Sunshine user events related to a user in a timeline. The app can be set to filter events by keywords, and lets agents search through or sort events, and view the attributes of a specific event on the ticket or the user's profile.


<p align="center">
    <img src="https://cl.ly/e39dfbb6661a/Screen%252520Recording%2525202019-06-26%252520at%25252009.58%252520am.gif" width="600px">
    <img src="https://cl.ly/96e1d10c305b/download/Screen%252520Recording%2525202019-06-26%252520at%25252009.59%252520am.gif" width="200px">
</p>

## App location

* User sidebar
* Ticket sidebar
* New ticket sidebar

## Features

* View list of user events on a user profile, including event description and creation date. 
* Filter list of events by searching for event description, date, source or type.
* Sort list of events by name or date.
* View event details (attributes).

## Using the app

### Prerequisites

* You must be on Zendesk Professional plan or above to be able to install private apps. 
* The User Events API is currently in Early Access. You must sign up to the [User Events API early access program](https://develop.zendesk.com/hc/en-us/articles/360001844267-Using-the-User-Events-API-early-access-) to be able use the API and create Custom User Events.

### Getting started

Simply download this project as a ZIP file and upload it as a private app. 

### Settings

* Default description: Define a default description for events with no description. 

## Known Issues & Limitations

* Event creation date is is showing in GMT+0
* Attributes longer than sidebar width don't get wrapped around (To be fixed)
