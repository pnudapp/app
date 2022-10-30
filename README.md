# bunq app: free (libre) and open source version

This is the free (libre) and open source version of the bunq app, a mobile banking app for Android and iOS. The app is made in Flutter and uses the public [bunq API][].

## Getting Started

You need to have Flutter installed. See the [Flutter documentation][] for more information on how to do this.

Code editor: [Visual Studio Code][] is recommended, but you can use any editor you like. Even Vim works, if you're into that.

Flutter Doctor: Run `flutter doctor` to check if you have all the required dependencies installed.
### Android & Apple iOS

To run the app on Android, you need to have an Android/iOS device connected to your computer or an Android/iOS emulator running. You can then run the app with:

    flutter run

### Web

To run the app on the web, you need to have the Google Chrome web browser installed. You can then run the app with:

    flutter run -d chrome

Firefox is also supported, but you need to run the app with:

    flutter run -d web-server --web-port=8000

and then open http://localhost:8000 in your browser.
## Contributing

We highly encourage you to contribute to the app, whether it's by fixing bugs, adding features or improving the documentation. You can find a list of issues that need to be worked on in the [issue tracker][]. If you want to work on an issue, please leave a comment so we know you're working on it &mdash; this prevents duplicate work.

You can contribute to the app by opening a pull request or by opening an issue. We encourage you to contribute to the app by fixing bugs, adding new features and improving the app. <!-- If you want to contribute to the app, please read the [contribution guidelines][]. If you want to contribute to the app, please read the [code of conduct][]. -->

## License

The bunq app is licensed under the [ISC license](LICENSE).

<!-- Links -->
[bunq API]: https://doc.bunq.com/ "bunq API documentation"
[Flutter documentation]: https://flutter.dev/docs/get-started/install "Flutter documentation"
[Visual Studio Code]: https://code.visualstudio.com/ "Visual Studio Code"
[issue tracker]: https://github.com/pnudapp/app/issues "Issue tracker"
[ISC license]: ./LICENSE "ISC license"