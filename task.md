# Instabug Cross-Platform Developer Task

* Create a React Native module that's available as an npm package for the two following iOS and Android frameworks.
	* [IBGxNetworkManager - iOS](https://github.com/Instabug/cross-platform-task/raw/master/IBGxNetworkManager.zip): used to create and run HTTP requests conveniently.
	* [Instacapture - Android](https://github.com/Instabug/cross-platform-task/raw/master/Instacapture.zip): used to capture a screenshot of all the current content on a screen.
* The modules should enable developers to use those two native frameworks in their React Native apps.
* Module should map at least one API from the ones provided by the native modules.
* Create a sample app for each framework that demonstrates how the modules you created can be used.
	* Running the app should be possible just by fetching the dependencies using `npm install`, then running it using `react-native run-ios` or `react-native run-android`.
	* App should use APIs mapped in the created modules.
	* Submissions with sample apps that do not run or aren't calling mapped APIs will immediately be rejected, so make sure that when your compressed app is uncompressed, everything works as expected.
* **Bonus:** create a Xamarin, Cordova or Unity plugin for one the native frameworks.

## Deliverables

* Create _local_ Git repos and commit to them regularly while working on the code. When you're done, archive the directories of the repos (including your `.git` directory) and send it our way. 
* You should be delivering 2 modules for `IBGxNetworkManager` and `Instacapture`, in addition to 2 sample apps, one for each framework.


Good luck! 🍀
