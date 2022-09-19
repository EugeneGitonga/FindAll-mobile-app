# FindAll-Emergency-Application
Android application for vehicle users 

## Contribute Code

Contributions are most welcome, whether you’ve fixed a bug or introduced a new feature. I welcome pull requests! (If you’d like to make a larger change and check with me first, you can do so via (eugenegitonga30@gmail.com).

## USER MANUAL 
The aim of this guide was to help users operate the software productively with minimum reading. It will also guide the users while using the program. It is an important tool in trouble shooting when working with the system and when installing the program.

## 1.0 Software and Hardware Requirements
This application runs only on Android operating systems. The system requires the mobile devices running the application to be connected to the internet. The Android devices must meet the following hardware and software requirements for effective running in order to function at peak performance
*	The system requires a mobile device –1GB RAM Minimum.
*	Android version should be 8.0 (Oreo) and above.

## 2.0 Installation
The app can be installed using [Android Studio](https://developer.android.com/studio) or the [Gradle Wrapper](https://docs.gradle.org/current/userguide/gradle_wrapper.html) (gradlew) command line tool.

## Using Android Studio

This is the recommended and most straightforward method. First, clone the repository with:

```sh
git clone https://github.com/EugeneGitonga/FindAll-Application.git
```

From Android Studio, select *Import Project*, then select the root folder of the cloned repository.
Click *Make Project* to build the app and download all the required dependencies.
Click *Run app* to install the app on your device or emulator.

## Using the Gradle Wrapper command line tool

The Gradle Wrapper can be built using [Gradle](https://docs.gradle.org/current/userguide/installation.html#installation). You can install Gradle using [Brew](https://brew.sh/):

```sh
brew install gradle
```
To generate the wrapper, execute this task:

```sh
gradle wrapper
```
 
Clone the repository with:

```sh
git clone https://github.com/EugeneGitonga/FindAll-Application.git
```

Enter the project root folder with:

```sh
cd FindAll-Application
```

Execute the command:

  
```sh
./gradlew assembleDebug
```
  
This creates an APK named *app-debug.apk* in *FindAll-Application/app/build/outputs/apk/*, so you can immediately install it on a device.

To build the APK and immediately install it on a running emulator or connected device, instead invoke installDebug:

```sh
./gradlew installDebug
```

## Direct installation through APK bundle
To install it directly in your mobile device, you need to build APK (select Build > Build Bundle(s)/APK(s) > Build APK(s) from the toolbar menu) in Android Studio after exporting/cloning the project since it has not yet been uploaded to Google app store yet. The user needs to allow USB debugging in mobile device settings when linking the device with Android Studio. Click the APK file where the mobile device will prompt the user to install the application to the device by clicking the install button. The application will install instantly in the user’s android device and ask for various permissions from the user like allowing the application to make calls in order to function effectively.

## 3.0 User Access Levels
There are two types of roles in FindAll emergency application :-
### 1. Guest User 
Guest user is the one who accesses and uses the FindAll Eemergency application without registering in 
the application.
### 2. Registered User
Registered user is the one who registers himself/herself in the FindAll emergency application by filling the registration form. Registered user can search for emergency services like the police, hospitals and mechanics, book requests and purchase packages etc. 

Getting Started :-
## 3.1	Guest User (Privileges)
Following features can be availed by the guest user.
*	Viewing list of registered mechanics.
*	Accepting and Rejecting new mechanics.
*	Login to application with a special passcode.

## 3.1.1 Admin Login details
To start the program, double click on the application Icon and then click the button with the name “Login As Mechanic/Admin” on the bottom of the applications first module. This will prompt the user to input the special pass key and then click the “Login with us” button and load the mechanics list as shown in figure 1.

![image](https://user-images.githubusercontent.com/70195777/189661636-08d59752-b059-4cd3-89d8-18ae6d3e046d.png)

## 3.1.2 Viewing list of registered mechanics.
To view the list of registered mechanics, click the button with the name “Login with Us” and input the special passcode where will direct the user to the mechanics lists for viewing. This Admin can Accept or Reject mechanics request from clients where it outputs a success message when the Admin clicks on either of the two buttons. It automatically logs out the user once the request has been made as shown in figure 2.

![image](https://user-images.githubusercontent.com/70195777/189662021-cd9cb753-c203-4c3d-9afb-b468788ad23e.png)
                    
## 3.2	Registered Users (Privileges)
Following features can be availed by registered user.
*	Register for new account.
*	Sign in with their credentials and sign out..
*	Book vehicle requests to mechanics.
*	Search for nearby emergency service providers.
*	Make calls to emergency service providers.
*	Make packages purchases.
*	Share the application to new users.


## 3.2.1 New User Registration
A Registered user can avail more benefits than a guest user. Hence it is recommended that 
users register themselves to access the additional services. 
A user can register in the FindAll mobile application. If you are a new user, select “Register With Us” to register. Fill all the required details which include full name, email and password then click the “Sign Up” button. On successful validation , the user will be registered and directed to the main module of the application as seen on as shown in figure 3.

![image](https://user-images.githubusercontent.com/70195777/189663077-8049a4e9-3912-47ff-9d09-f48b2e5ccbd0.png)

## 3.2.2 Sign In and Sign Out Section
To Sign In into the application click on the "Login" option from the main page. Enter email and password to login. On successful login, the user is redirected to home page screen. When the user wants to Sign Out of the application he/she clicks the “Sign Out” button on the navigation bar as seen in figure 4 below. 

![image](https://user-images.githubusercontent.com/70195777/189663484-ce2c328b-ad81-409d-a156-4f12579f04f6.png)


## 3.2.3 Booking vehicle requests
To book a request with the mechanic, the user needs to sign in into the application then he will be directed to main page where he/she will be expected to click the mechanic Image button with the name where a list of nearby mechanics and user is expected to select one of the mechanics listed. Upon selecting, a booking form will be displayed where the name, phone, type of wheel and vehicle problem will be filled and the user will be expected to click the “Submit” button as seen in figure 5 below.

![image](https://user-images.githubusercontent.com/70195777/189663741-68f7910f-1835-4149-b28e-ca9b2acfc963.png) ![image](https://user-images.githubusercontent.com/70195777/189664060-dfaf36c9-ce16-4a53-b982-d76b7a955181.png)

## 3.2.4 Searching for nearby emergency service providers 
In order to get the nearby emergency service providers location and distance, the user will click on the search button on the navigation bar and select “Hospital” Icon when he/she needs to access nearby hospitals where he/she can click to a specific hospital on the list to be directed to emergency service provider contact. When the user needs to search for nearby mechanics he/she will click on the “Mechanic” Icon where they will be directed to a list of nearby mechanics together with their contacts and also the same procedure is used when the user needs access to nearby police stations within a given range by clicking on the police icon. It’s seen in the figure 6 below.

![image](https://user-images.githubusercontent.com/70195777/189663741-68f7910f-1835-4149-b28e-ca9b2acfc963.png) ![image](https://user-images.githubusercontent.com/70195777/189668855-e4d6a9b9-d5c8-488a-9c93-63e8d6c02ba9.png)


## 3.2.5 Making packages purchases.
FindAll mobile application has an extra feature that allows users to subscribe to vehicle repair packages to cover them for a given period of time incase they encounter a vehicle emergency. The user will purchase packages by first logging in to the application then go to the navigation bar where he/she will click the “packages” button to be able to purchase a particular package. When the user purchases a given plan he/she will receive a confirmation message. The packages are divided into Plan A, Plan B and Plan C. It is seen in the figure7 below.

![image](https://user-images.githubusercontent.com/70195777/189664827-31f17411-dc33-426d-9b76-411c744d7e17.png)

## 3.2.6 Emergency service providers call feature.
To access the emergency service providers call feature, the user needs to allow the application to make and manage calls during the initial installation of the application. The user then needs to search the particular nearby service providers location by clicking on one or all the Service providers icons as seen in figure 6. On clicking to the nearest service provider from the list displayed, he/she will be directed to a module that will display the distance, ratings and the call button with contact details which when clicked it will direct user to the call logs to place the call. It’s seen in figure 8 below.

![image](https://user-images.githubusercontent.com/70195777/189665017-ea20468c-b551-44f6-8747-3a531b3390b1.png)

## 3.2.7 Sharing the application to new users.
FindAll application has a feature that allows users to share the application to new users through social platforms and email services. The user needs to login to the application initially then go to the navigation bar where he/she will see a “Share” icon. When the user clicks it, it will direct him to various platforms like telegram, WhatsApp where he/she can share the application. It’s seen in figure 9 below.

![image](https://user-images.githubusercontent.com/70195777/189665175-9fb671fa-65d6-46fb-b24d-fb609d45cb55.png)




