


# PLUGIN: 

phonegap-plugin-wizUtils
phonegap version : 1.7<br />
last update : 10/05/2012<br />


# DESCRIPTION :

PhoneGap plugin for general utility functions to access information from the native OS.

<br />
<br />
<br />
# EXAMPLE CODE : #
<br />
<br />
Get App File Name<br />
<pre><code>
wizUtils.getAppFileName(Function success);
* returns String eg. "game.app"(iOS) or "game.apk" (Android)
</code></pre>
<br />
Get Bundle Version<br />
<pre><code>
wizUtils.getBundleVersion(Function success); 
* returns String eg. "1.0.0"
</code></pre>
<br />
Get Bundle Display Name<br />
<pre><code>
wizUtils.getBundleDisplayName(Function success); 
* returns String eg. "bundleDisplayName" ''
</code></pre>
<br />
Get Bundle Identifier<br />
<pre><code>
wizUtils.getBundleIdentifier(Function success);
* returns String eg. "com.bundle.identifier"
</code></pre>
<br />
Get Device Height<br />
<pre><code>
wizUtils.getDeviceHeight(Function success); 
* returns Int eg. 480
</code></pre>
<br />
Get Device Width<br />
<pre><code>
wizUtils.getDeviceWidth(Function success); 
* returns Int eg. 320
</code></pre>
<br />
Get Text<br />
<pre><code>
wizUtils.getText(Function success, Function failure);
* returns String (current clipboard/clipbuffer text)
</code></pre>
<br />
Set Text<br />
<pre><code>
wizUtils.setText(String text, Function success, Function failure);
* Sets the current clipboard/clipbuffer text
</code></pre>
<br />
Restart<br />
<pre><code>
wizUtils.wizUtils.restart(Boolean true/false);
* Restart the app.
* If a boolean value of true is passed, the splash screen will be shown.
* If a boolean value of false is passed, the splash screen will not be shown.
* If a boolean value is not provided:
*   If the AutoHideSplashScreen key is set to YES in the Cordova.plist file.
*   Otherwise, the splash screen will not be shown.
</code></pre>
<br />
