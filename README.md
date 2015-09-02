#Sample Ionic Framework app

This is a basic sample app for the [Ionic Framework](http://ionicframework.com/). This is an attempt to demostrate the basic funcitonalities of the framework in a small application for iOS. Anyone attempting to have run this app on iOS must use a Mac and have XCode installed.

##Install npm
Follow instructions on site
https://docs.npmjs.com/cli/install


##Install global dependencies
```
sudo npm install -g bower cordova ionic ios-sim
```

##Install npm dependencies
```
sudo npm install
```

##Install bower dependencies
```
bower install
```


##Build
###iOS
```
ionic platform add ios
ionic build ios
```

##Run
###iOS
```
ionic emulate ios
```

###Web
```
ionic serve
```