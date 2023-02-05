# messageApp
Reference link ----> https://www.youtube.com/watch?v=PcbSgSJxIBc
Installation Guide for Android Studio with React Native
	GO to --> https://reactnative.dev/docs/
	Select React Native Cli Quick Start
	Under Android Section
	Install Node Js 14 or above version
	Download Java 11jre
	Download Android Studio by using link --> https://developer.android.com/studio/index.html
	Select SDKTools
	Install Android SDK Build-Tools
	GO to --> home/.bash_profile or home/.bashrc
	Copy paste below lines in above file:
	export ANDROID_HOME=$HOME/Android/Sdk
	export PATH=$PATH:$ANDROID_HOME/emulator
	export PATH=$PATH:$ANDROID_HOME/platform-tools
	
	echo $ANDROID_HOME
	echo $PATH
Install React Native Cli in Home/Android location:
	1.npm install -g react-native-cli
	2.react-native init PROJECT --version 0.68.2
	3.cd PROJECT 
	4.react-native run-android
	
	
	or if Existing Application then clone existing project
	1. npm install
	2. react-native run-android



