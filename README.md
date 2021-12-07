# Places-framework-description

**Places-framework-description** is a description of the framework for Places.

Snippets of code from the framework and the project itself will only be given away to backers of my project, [Places](). Places is an advanced mobile geofence system that will be used for place-based analysis.

The framework itself is made up of three components:

* Backend application (Java)
* Android application (Java)
* Core library (Java)

# Features

Here is the full list of features within the framework:

* User accounts
    * Account creation
    * Phone number/email verification
    * Account settings
        * Change username
        * Change password
        * Change phone number
        * Change email address
* Generic Android framework
    * Many generic UI components for all sections of the app:
        * User account creation, log in, verification and settings screens
        * Widgets and dialogs for generic object data
    * Generic activity/screen heirarcy
* Full REST framework
    * A complete REST framework that processes and returns generic object data
    * Complete backend response management
    * Complete backend error management
    * Complete database implementiong (built on PostgreSQL)
    * Full-stack object managment framework for serializing, deserializng and diplaying data
* Remote client configurations
    * Control multiple things in the app by changing configuration records in the database, like characters for username validation, object update restrictions, action restrictions, minimum token life and much more (fully shared between the frontend and backend).
* Remote user messages
    * Change user messages that are displayed on different events within the app (fully implemented in Android) by updating the configurations in the database.
