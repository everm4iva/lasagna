<div align="center">

<img src="./www/shc/banner.png" alt="Lasagna Banner" width="70%">

<a href="changelog.md">Changelog</a> | <a href="https://everm4iva.github.io/p/lasagna">Website</a> | <a href="LICENSE">License</a>


## About

</div>

Lasagna is a simple web application that converts your boring currency to lasagna!

It is built using HTML, CSS, and JavaScript, and packages with <a href="https://cordova.apache.org/">Apache Cordova</a> to create a cross-platform mobile application.

The application uses a simple conversion rate of 1 USD = 1 Lasagna, but you can customize it to your liking.

> I created this project because my brain is been doing this thing for months of "convert my money to lasagna" and i couldn't keep up with the market lasagna price, so here it is. - Very autistic

> quick note: it only applies to the portuguese lasagna market as a base. But it becomes more fun, if in a conversation you say "that equals 4 portuguese lasagnas" heheh

## How to build
### Prerequisites
- Node.js (v14 or higher)
- Android sdk (for Android development)
- Xcode (for iOS development)
- Apache Cordova CLI: `npm install -g cordova`
- Git
- A code editor (e.g., Visual Studio Code)
- A device or emulator for testing

### Actual building steps
1. Clone the repository: `git clone https://github.com/everm4iva/lasagna.git`
2. Navigate to the project directory: `cd lasagna`
3. Install dependencies: `npm install`
4. Add platforms:
   - For Android: `cordova platform add android`
   - For iOS: `cordova platform add ios`
   - For web: `cordova platform add browser`
   - For desktop: `cordova platform add electron`
5. Build the application:
   - For Android: `cordova build android`
   - For iOS: `cordova build ios`
   - For web: `cordova build browser`
   - For desktop: `cordova build electron`
   - For all platforms: `cordova build`
   - For debug, you can add the `--debug` flag to the build command, e.g., `cordova build android --debug`
6. Run the application:
   - For Android: `cordova run android`
   - For iOS: `cordova run ios`
   - For web: `cordova run browser`
   - For desktop: `cordova run electron`
   - For debug, you can add the `--debug` flag to the run command, e.g., `cordova run android --debug`

**Happy building!**

  -- everm4iva, april 2026 --