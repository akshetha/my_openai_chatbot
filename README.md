# my_openai_chatbot

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Step By Step Instuctions:

1. Create an open ai account and generate a open api key. 

https://platform.openai.com/

2. Generate a open api user key by following the instructions

https://platform.openai.com/docs/api-reference/introduction

Note that OPEN_API_KEYs are secret key and should not be share with others

3. Install and setup flutter in your system by following the instructions below (choose the installables specific to your platform)

https://docs.flutter.dev/get-started/install

You can use any editor for running flutter, I presonally liked VSCode

https://docs.flutter.dev/get-started/install/macos/mobile-ios#install-the-flutter-sdk

Note: Enable flutter for all terminals

4. Once the installation is completed clone the project to your local folder 

5. Open the project in VSCode editor -> Open a new Terminal -> and run the command 

	**flutter --help** (or) **flutter doctor**

to make sure that the flutter SDK is installed correctly

6. Make sure the class main.dart is loaded with no exception. if there is any dependent packages are missing install them using the below command

  **flutter pub add <package_name>**

	- flutter packages installation instructions can be found here 	https://pub.dev/packages/flutter_chat_ui/install

7. Now run the command **flutter run** to start the chatbot
