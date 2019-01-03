# Events Search App

The Events Search App is a Zendesk App that allows agents to view all custom user events related to a user in a timeline. The app lets agents search through or sort events, and view the attribute of a specific event next on the user's profile.

## Screenshot(s):
![](https://cl.ly/132acf8e2cab/Screen%20Recording%202019-01-03%20at%2002.58%20pm.gif)

## App location

* User sidebar

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
