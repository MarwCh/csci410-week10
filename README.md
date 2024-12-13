# week10

A new Flutter project that connects to DB using HTTP REST service.
You can create your cloud DB using one of the following free web hosts:
- https://www.awardspace.com
- https://www.infinityfree.com
- https://googiehost.com
- etc.

Please also note that you need to perform the below steps so that the application works on chrome emulator:
- Go to flutter\bin\cache and remove flutter_tools.stamp file
- Go to flutter\packages\flutter_tools\lib\src\web open file chrome.dart and edit it Add '--disable-web-security' next to '--disable-extensions' line
This is only necessary if you are using chrome as an emulator, otherwise it will give a connection error.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
