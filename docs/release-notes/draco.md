# Kodular Draco

![Kodular Draco](//assets.kodular.io/images/creator/versions/draco.png)

## 1.3 Draco   \|   _13 January 2019_

### Major Changes

- Full **HTTPS** Support  
_Big thanks to MIT App Inventor, specially to Jeffrey Schiller_

- **Integrated Kodular Account**, making _login & signup_ easier  
_In order to login, you will be redirected to Kodular Account, where you can just use your Google account or any other social provider to access to Creator_  
_You will not lose any project data with this change_

- **Compressed images** making _loading_ faster

- Added Target **SDK 28** (_Android 9_) for all apps

- Added **New Languages**
	- **Arabic** Language  
	- **Romanian**  Language

- Updated **runtime permission system**  
_It will now prompt for permissions when required, and not on start_  
[Add blocks to assist in permission workflow · mit-cml/appinventor-sources@2d19558 · GitHub](https://github.com/mit-cml/appinventor-sources/commit/2d19558acd16f2a3bbe1920215e3bfe4bca05675)

### Companion

- Companion can be _exited_ by **pressing back button**

- Companion now works **without being connected to the same WiFi network**  
_You can even use it with your phone connected to mobile network_

### UI Changes

- Added **apps' icons** at Projects Dashboard

- Added **Show & Hide All Comments** to menu in _Blocks Editor_

- Added **Social Networks** to _Splash Screen_

- Fix **erroneously shown**  _edit and delete icons_ on Screen Properties panel

### New Components

- Added new **Bottom Navigation** component to _User Interface_ category  
![image|243x119](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/f/f2ce9deff1d09fe463611de0e4b4e42278b037ad.png)

- Added new **State Progress Bar** component to _User Interface_ category  
![image|244x121](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/7/7b43ffeafc01245a105942f8825f2bbb4526f511.png)

- Added new **Firebase Authentication** component to _Google_ category  
![image|243x125](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/a/aa7f51685c526c1b3a8bc9bbe95e7e2ad92646f1.png)

- Added new **Firebase Remote Config** component to _Google_ category  
![download|236x125](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/e/e649a29a7bff946c5749eeac2f6d8f068befe621.png)

- Moved **Fiebase DB** component to _Google_ category and renamed to **Firebase Database**

- Added new **Chameleon Ads** component to _Monetization_ category  
_Find more about this [HERE](https://community.kodular.io/t/chameleon-ads-what-is-it/15802)_  
![image|250x142](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/6/62f917c42e423bccad07ec2db06bf1a521310b18.png)

### New Blocks

- Add new **bitwise** operator blocks to _Math_ category  
![image|519x80](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/dc29a2e0ba91e3ede8a89ac51800e9345dcaef32.png)

### New Events

- **Screen**
	- `Keyboard Visiblity Changed`: triggered after _keyboard_ becomes visible or hidden  
![image|355x103](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/f/f665c291e364f25092c9481e0e44555010c191f1.png)  
&nbsp;  
	- `Permission Denied`: triggered after a _permission has been denied_  
![image|396x98](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/1/19625edacc44c48ca5f0c7b62b6d42711f7ec329.png)  
&nbsp;  
	- `Permission Granted`: triggered after a _permission has been granted_  
![image|299x106](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/d2cf8b2562baab82f754dc0d0988d6fed3a3002d.png)

- **Chat View** component  
	- `Double Tap Click`: triggered after a message is _double clicked_  
![image|690x73](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/a/aab1c0e6476516542aa476c40f8415f78d570fc5.png)

- **Device** component  
	- `Got IMEI`: triggered after the _Get IMEI_ method  
![image|279x109](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/2/2e9bb34641ffc34d0d9907980c2b874246b98899.png)

### New Functions

- **Screen**  
	- `Ask For Permission`: prompts user asking a permission using the native Android method  
![image|283x70](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/2/20fe65dca5894d6c759f04330ca694d82abc308d.png)

- **Chat View** component  
	- `Clear Chat View`: deletes all messages from layout  
![image|287x50](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/da0401831c5a279805a2eb0073b236f85ee6ec6a.png)

- **ExoPlayer** component
	- `Resume`: resumes the paused track  
![image|233x55](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/8/8ca2a74adb301ecf9fee1c07c5e07116393e5199.png)

- **Device** component  
	- `Get IMEI`: attempts to get device's IMEI code  
![image|247x39](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/0/0e7859c7c6a3649bc3e8e2c31714e7854e3f5326.png)

### New Properties

- **Chat View** component  
	- `Double Tap`: enables double clicking messages  
![image|297x65](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/2/236daa119bedc24670cb94459d3a1dfd588ba9c2.png)

- **Label** component  
  - `Marquee`: adds a marquee effect to the label  
![image|292x66](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/0/02a47796177cc5b92e7434a9ed3894a2e252b601.png)  
&nbsp;  
  - Support for _inline clickable links_

- **Lottie** component  
	- `Clickable`: enables Lottie layout to be clickable by the user  
![image|297x66](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/f/f6651b844d00bc255f8371dda6ffcae33dec4777.png)

- **Map** component  
	- `ScaleBar`: adds a scale bar to generated map  
![image|282x64](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/9/9c2c0410e6b49a873a2811e529f7a152cbc742b1.png)  
&nbsp;  
	- `ScaleUnits`: changes unit system of the scale bar  
![image|288x62](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/9/95bd7d691ae2b44f7a2b50b1736aa69d16229b25.png)

### Bugs Fixed

- _Too many extensions_ resulted on **compilation error**

- **Backpack icon** state was bugged with _multiple screens_

- **Screen**
	- **HighQuality** is now by default _false_

- **User Interface**
	- **Button** _border shadow_ fixed
	- **Chat View** messages now have _dynamic width_
	- **Chat View** _swipe on message_ fixed

- **Layout**
	- **Arrangements** _borders' color_ with _IsCard_ property  
[Changing programmatically the background color of arrangements defined as "iscard" doesn't change borders color](https://community.kodular.io/t/changing-programmatically-the-background-color-of-arrangements-defined-as-iscard-doesnt-change-borders-color/13996)  
	- **CardView** _elevation_ property wasn't working properly  
[CardView ELEVATION property does't work correctly](https://community.kodular.io/t/cardview-elevation-property-doest-work-correctly/12583)

- **Drawing and Animation**
	- **Lottie** Component fixed as it was causing an _unexpected error_

- **Connectivity**
	- **ActivityStarter** Component fixed when _opening files_

- **Monetization**
	- **AdMob** Components loading bug fixed
	- **Facebook Ads** Components fixed by upgrading libraries  

- [Set webViewString directly to bypass event from blocks (#1320) · mit-cml/appinventor-sources@2869a13 · GitHub](https://github.com/mit-cml/appinventor-sources/commit/2869a13e01c1fbcfdf5e27640c15ca36e7cde912)

- [Fix null pointer when logging before user info available · mit-cml/appinventor-sources@b99cfc4 · GitHub](https://github.com/mit-cml/appinventor-sources/commit/b99cfc47eea0d514da2340c99f2a8fa84d6cf863)

- [Fix GeoJSON parsing in MockFeatureCollection · mit-cml/appinventor-sources@517360b · GitHub](https://github.com/mit-cml/appinventor-sources/commit/517360b2b19f2e5b1c797f88619f0e49f2af0f9f)

- [Make Backpack open in Firefox · mit-cml/appinventor-sources@3372a19 · GitHub](https://github.com/mit-cml/appinventor-sources/commit/3372a195e0829556267bfb7811d7c7eafc7e7544)

- [Ensure connections added to ConnectionDB on load · mit-cml/appinventor-sources@55b5834 · GitHub](https://github.com/mit-cml/appinventor-sources/commit/55b5834229e56c018cc9eddb95a5b233ac81a296)

- [Fix connection DB bug when workspace contains blocks with errors · mit-cml/appinventor-sources@f6f0160 · GitHub](https://github.com/mit-cml/appinventor-sources/commit/f6f0160297b6a50e72bccd880e7ef063235fa13d)

- [Stop resetting list of connections when errors occur · mit-cml/appinventor-sources@ac7c0e4 · GitHub](https://github.com/mit-cml/appinventor-sources/commit/ac7c0e4c74009b064e617ab2387caa43fb60f9fa)

- [Fix handling of Map.ZoomLevel when animating changes · mit-cml/appinventor-sources@6f14488 · GitHub](https://github.com/mit-cml/appinventor-sources/commit/6f144887abd7be4bb78714720d8df343726890fa)

&nbsp;

## 1.3.1 Draco   \|   _19 January 2019_

### UI Changes

- Added **_Carbon Ads_** in _Creator_ dialogs

- Fixed **_Docs URL_** when using _non-English language_

### Companion

- Fixed **_Error 1103_** on Companion using _Android 9_ (`when attempting to connect it was raising this error`)
 
- Fixed **_Lottie_**  component in Companion (`it was crashing when trying to load it`)

### New Features

- Added missing **_Keep Screen On_** property for **Screen**

- Added missing **_Text Color_** property for **Snackbar** component

- Added missing **_Sign Up Success_** event for **Firebase Authentication** component

- Added missing **_URL_** and **_Token_** blocks for **Firebase Database** component

- **Chameleon Ads**
	- Ads can now be **loaded with any device orientation**
	- Ads can be **closed with backpress button**
	- Ads can be **rotated**
	- Ads are now **displayed in fullscreen**

- Added missing **_error Code_** parameter to _Error Events_ for **Chameleon Ads** component

### Bugs Fixed

- Fixed **importing AIAs** from other servers which had set _Classic theme_

- **Button** component made _app crash_ on devices with Android <5 (`when launching Screen, app was stopped`)

- **Label** component was not working properly with _Inline Links_ (`temporall removed clickable links from it`)  
[How to disable inline clickable links](https://community.kodular.io/t/how-to-disable-inline-clickable-links/15808)

- **List View Image and Text** component was _crashing_ on devices with Android <5 (`when launching Screen, app was stopped`)

- **WebView** component bug when _requesting location_ (`was not working properly`)  
[WebViewer Bug with Maps](https://community.kodular.io/t/webviewer-bug-with-maps/7352)

- **Lottie** component was crashing when no _Source_ was found (`now it will no longer crash`)

- **Cloudinary** component was _sometimes crashing_ (`some internal bugs have been fixed`)

- **Device Tools** component was requesting _too many permission_ (`on app start, some unused permissions were asked`)

- **AdMob** components were _not working_ (`sometimes ad requests were unsuccessful`)

&nbsp;

## 1.3B.0 Draco   \|   _03 February 2019_

### Major Changes

- Added full **RTL support** (_right-to-left_) for apps

- Added ability to use **strings.xml files**

- Added a **connection progress bar** to Companion

### Companion

- Fixed using **Companion in Safari**

### UI Changes

- Added **Google Pixel 3** phone's mock to preview

- Added **Kodular Draco** version image

### New Components

- Added new **Color Utilities** component to _Experimental_ category  
![image|250x124](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/e/e91876494e13887e8120398da4f1648e2c5a0015.png)

-  Added new **Image Utilities** component to _Experimental_ category  
![image|248x140](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/9/9e3d9c344c733a3629bd859d0446bfabb87ba22a.png)

- Added new **Resources Utilities** component to _Experimental_ category  
_This permits the usage of `strings.xml` files_  
![image|248x139](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/f/fb88786243ca239ca2cf3df20ab2c40e134f5350.png)

### New Events

- **Push Notifications** component
	- `Got Available Tags`: triggered after the _Get Available Tags_ method  
![image|369x108](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/d997900396767745035371eb99ae674ccd770335.png)  
&nbsp;  
	- `Notification Opened`: triggered after opening a sent notification  
![image|377x110](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/2/2c5f420328504d12c2d2b83677abf7d2d1ee096b.png)  
&nbsp;  
	- `Notification Received`: triggered after receiving a notification  
![image|377x110](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/e/e419741a4d9faf52bad71dd00441a785fe079e08.png)

### New Methods

- **Wallpaper** component
	- `Clear Wallpaper`: resets the custom wallpaper to system's default one  
![image|274x49](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/d64bf23e59fb113dac739c4085132b6797d03712.png)  
&nbsp;  
	- `Set Lockscreen Wallpaper`: changes lockscreen's wallpaper to given image  
![image|274x49](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/2/23f39e1f01605fa09c69097f08859e4ee9ddd81b.png)

- **Push Notifications** component
	- `Send Tag`: identifies an user based on given _key_ to later segment them with the set _value_  
![image|298x100](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/5/551b16da58367a0c3eb69316dcb0ed01622b5d90.png)  
&nbsp;  
	- `Delete Tag`: removes the given tag for the user  
![image|303x73](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/3/375950952507949f2c24c3c8b593869916639765.png)  
&nbsp;  
	- `Get Available Tags`: returns a list of available tags  
![image|349x48](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/4/41d1550fa6a763e1d3bcb1169c460de8e7162b4e.png)

### New Properties

- **Screen**
	- `Navigation Bar Light Icons`: declares if Navigation Bar should use light or dark icons  
![image|344x85](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/d8f91c5a379cd99e8aca14bc1bcfc414529bd675.png)

- **Chat View** component
	- `Messages Border Radius`: sets a radius for messages' borders  
![image|273x67](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/b/b565680043762a613871ce48eedfcbf1432bef5d.png)  
&nbsp;  
	- `Messages Font Size`: changes the font size of the text message  
![image|281x62](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/b/b1ae500e4d63ed82d1f0ae336ebd45049b4f28b9.png)  
&nbsp;  
	- `Receivers Typeface Message`: changes the font type for received messages  
![image|290x63](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/d677725e1c2e21172a10ae4fbec55ebad6263ec9.png)  
&nbsp;  
	- `Receivers Typeface Message Import (.ttf)`: imports a custom font type for received messages  
![image|287x72](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/f/f2a07007979eb33e3fb11952c6c12e6fe2f3df36.png)  
&nbsp;  
	- `Receivers Typeface Title`: changes the font type for receiver's title  
![image|283x62](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/3/330f8f81eaa7dd936189bd203b92c1a8a4a63b7b.png)  
&nbsp;  
	- `Receivers Typeface Message Import (.ttf)`: imports a custom font type for receiver's title  
![image|288x69](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/9/9dd91a7ff214e64dea6b9399482cb8cb5b7df8e0.png)  
&nbsp;  
	- `Senders Typeface Message`: changes the font type for received messages  
![image|279x60](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/8/840b4ca2a1aaec2b6b3991dee1508f381caf46b5.png)  
&nbsp;  
	- `Senders Typeface Message Import (.ttf)`: imports a custom font type for received messages  
![image|287x72](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/1/122021120214e2b29eee867f28ac82af3a436b69.png)  
&nbsp;  
	- `Senders Typeface Title`: changes the font type for receiver's title  
![image|280x59](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/5/5c69ce976face9a2e3921dd6732ef2ae04e08913.png)  
&nbsp;  
	- `Senders Typeface Message Import (.ttf)`: imports a custom font type for receiver's title  
![image|284x71](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/1/144e5f3c728c70968e62648253510dc23f96a1de.png)  
&nbsp;  
	- `Timestamp Border Radius`: sets a radius for timestamp's boxes  
![image|285x70](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/dec4c2377bae93dfa13962c0d725453a574fd95b.png)  
&nbsp;  
	- `Timestamp Font Size`: changes the font size of the timestamp's text  
![image|282x75](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/2/246ceb5b685f77bc52ea1ea3c96edc15e29295a8.png)  
&nbsp;  
	- `Title Font Size`: changes the font size of the title  
![image|279x68](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/d/dd9b34adfdbec22aa0e89ef3caf2cf1095d67634.png)

- **Wallpaper** component
	- `Is Set Wallpaper Allowed`: returns true when changing wallpaper is allowed  
![image|331x45](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/0/0b8ba2e2b6722784c0a9a2d07869321b1e20b7ce.png)  
&nbsp;  
	- `Is Wallpaper Supported`: returns true when changing wallpaper from apps is allowed  
![image|322x48](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/9/9794a0de35fa8fe647e53afbb5abde01f9482e7c.png)  

- **Google Maps** component
	- `Camera Angle`: sets map view angle (in _degrees_)  
![image|274x66](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/6/6b172f0c8c54c4204a9df28720a8e3b7418ff496.png)  
&nbsp;  
	- `Camera Rotation`: sets map rotation (in _degrees_)  
![image|284x63](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/3/3e6f0af17bf9e7c93bc91a0f7b80550bc180beb7.png)  
&nbsp;  
	- `Camera Zoom Level`: sets the altitude from where map should initialize  
![image|293x65](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/b/b1dd21c3e28fb40aa52c180ae39f51460b2947af.png)  
&nbsp;  
	- `Style`: sets a custom theme from a JSON string for the map  
![image|290x51](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/4/4468e0ed70dbccae7db854c41ecd6f0be1cc3332.png)  
&nbsp;  
	- `Theme`: sets a pre-defined theme for the map  
_Big thanks to @Peter for Kodular one_  
![image|292x64](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/4/4c3cee8119eccdef10efce58777f60bc2fd66205.png)  

- **Push Notifications** component
	- `Get Email Subscription Email Address`: Returns the email address of the email subscription  
![image|472x52](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/7/7a78bcbd2ea12233c3c32c5146937d77b33e4ae2.png)  
&nbsp;  
	- `Get Email Subscription User ID`: Returns the user ID of the email subscription  
![image|423x49](https://kodular-community.s3.dualstack.eu-west-1.amazonaws.com/original/2X/2/2b0cc0f68c96c602b38a9044bb7ee1650c866f09.png)

### Bugs Fixed

- **User Interface** category
	- **Bottom Navigation** when using _too many items_  
[New Bugs("Maximum number of items supported by BottomNavigationView is 5. Limit can be checked with BottomNavigationView#getMaxItemCount()")](https://community.kodular.io/t/new-bugs-maximum-number-of-items-supported-by-bottomnavigationview-is-5-limit-can-be-checked-with-bottomnavigationview-getmaxitemcount/16608)
	- **Tab Layout** raised _Null Pointer Exception_
	- **Textbox** crashing when using _Copy/Paste feature_
	- **View Pager** raised _Null Pointer Exception_

- **Media** category
	- **Camera** had no permission to enable flash, _now it asks for the it_
	- **Metadata** was raising _Null Pointer Exception_  
[Null Metadata instead of Empty String](https://community.kodular.io/t/null-metadata-instead-of-empty-string/11377)
	- **OCR** works now too with Companion by _removing deprecated libs and added runtime permission system_

- **Drawing and Animation** category
	- **Lottie** component was _not working properly on Companion_

- **Storage** category
	- **Cloudinary** had one _permission missing_
	- **Spreadsheet** was raising _Null Pointer Exception_ on set cell method

- **Device** category
	- **Device Tools** component was _not working properly_

- **Google** category
	- **Google Maps** component was _broken_

- **Monetization** category
	- **Admob** components were crashing sometimes

_Other minor bugs which were not listed here have been fixed too, improving code performance_