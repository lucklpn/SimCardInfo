
# react-native-sim-card-library

## Getting started

`$ npm install react-native-sim-card-library --save`

### Mostly automatic installation

`$ react-native link react-native-sim-card-library`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-sim-card-library` and add `RNSimCardLibrary.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNSimCardLibrary.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNSimCardLibraryPackage;` to the imports at the top of the file
  - Add `new RNSimCardLibraryPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-sim-card-library'
  	project(':react-native-sim-card-library').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-sim-card-library/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-sim-card-library')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNSimCardLibrary.sln` in `node_modules/react-native-sim-card-library/windows/RNSimCardLibrary.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Sim.Card.Library.RNSimCardLibrary;` to the usings at the top of the file
  - Add `new RNSimCardLibraryPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNSimCardLibrary from 'react-native-sim-card-library';

// TODO: What to do with the module?
RNSimCardLibrary;
```
  