
# vendor
### Table of contents
- [System requirements](#system-requirements)
- [Application structure](#project-structure)

### System requirements

Dart SDK Version 2.12.0 or greater.
Flutter SDK Version 3.3.0 or greater.

### Application structure
After successful build, your application structure should look like this:
                    
```
.
├── android                         - It contains files required to run the application on an Android platform.
├── assets                          - It contains all images and fonts of your application.
├── ios                             - It contains files required to run the application on an iOS platform.
├── lib                             - Most important folder in the application, used to write most of the Dart code..
    ├── main.dart                   - Starting point of the application
    ├── auth
    │   ├── auth_controller.dart         - It contains the authentication controllers used login and signup
    │   ├── login_page.dart              - It contains login_page
        ├── splash_screen.dart           - It contains splash screen that decides the user is login in or not while restarting
        ├── signup_screen.dart           - It contains signup_page

    ├── home                          - It contains home page of the app where vendor can view the status
   
