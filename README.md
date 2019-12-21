
# react-native-native-demo-odoo-lib-new

## Getting started

`$ npm install react-native-native-demo-odoo-lib-new --save`

### Mostly automatic installation

`$ react-native link react-native-native-demo-odoo-lib-new`

### Manual installation


#### iOS

1. In XCode, in the project navigator, right click `Libraries` ➜ `Add Files to [your project's name]`
2. Go to `node_modules` ➜ `react-native-native-demo-odoo-lib-new` and add `RNNativeDemoOdooLibNew.xcodeproj`
3. In XCode, in the project navigator, select your project. Add `libRNNativeDemoOdooLibNew.a` to your project's `Build Phases` ➜ `Link Binary With Libraries`
4. Run your project (`Cmd+R`)<

#### Android

1. Open up `android/app/src/main/java/[...]/MainActivity.java`
  - Add `import com.reactlibrary.RNNativeDemoOdooLibNewPackage;` to the imports at the top of the file
  - Add `new RNNativeDemoOdooLibNewPackage()` to the list returned by the `getPackages()` method
2. Append the following lines to `android/settings.gradle`:
  	```
  	include ':react-native-native-demo-odoo-lib-new'
  	project(':react-native-native-demo-odoo-lib-new').projectDir = new File(rootProject.projectDir, 	'../node_modules/react-native-native-demo-odoo-lib-new/android')
  	```
3. Insert the following lines inside the dependencies block in `android/app/build.gradle`:
  	```
      compile project(':react-native-native-demo-odoo-lib-new')
  	```

#### Windows
[Read it! :D](https://github.com/ReactWindows/react-native)

1. In Visual Studio add the `RNNativeDemoOdooLibNew.sln` in `node_modules/react-native-native-demo-odoo-lib-new/windows/RNNativeDemoOdooLibNew.sln` folder to their solution, reference from their app.
2. Open up your `MainPage.cs` app
  - Add `using Native.Demo.Odoo.Lib.New.RNNativeDemoOdooLibNew;` to the usings at the top of the file
  - Add `new RNNativeDemoOdooLibNewPackage()` to the `List<IReactPackage>` returned by the `Packages` method


## Usage
```javascript
import RNNativeDemoOdooLibNew from 'react-native-native-demo-odoo-lib-new';

// TODO: What to do with the module?
RNNativeDemoOdooLibNew;
```
  