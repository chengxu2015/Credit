## run app in simulator with node server
1.	dev mode :  react-native run-ios
2.	release mode:	react-native run-ios --configuration Release
If you run app in release mode, the app will be bundled automatic

## bundle in to package
1.	comment 21th line instand of 22th line
2.	npm run bundle-ios
3.	use xcode to open thw ios project, choose your device and run it

## remove "loading from pre-loaded bundle" at app's header in dev mode
search "loading from" globally and comment the line
