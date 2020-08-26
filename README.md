# Unity-Vibrator

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/f70a74f2ca5840e6b6e923012fe74d47)](https://app.codacy.com/manual/Comp3interactive/Unity-Vibrator?utm_source=github.com&utm_medium=referral&utm_content=Comp3interactive/Unity-Vibrator&utm_campaign=Badge_Grade_Dashboard)

Performs custom Vibrate functions on an Android device  and standard vibrations on iOS

<B>Overview</B></br>
This Unity Package will provide you with simple functions to call as and when you require a mobile device to vibrate.</br>
Android allows for customisable lengths whereas iOS will perform a standard 500ms vibration.</br></br>
<i>Simply have the package inside your project and everything is ready to go!</i>

<b>Public Methods</b></br>
<code>public static void Vibrate(long milliseconds) { ... }</code></br>
<code>public static void Vibrate(Vibration vibration) { ... }</code></br>
<code>public static void Cancel() { ... }</code></br>

<table>
  <td><b>Vibrator.Vibrate(long milliseconds)</b></td>
  <td>Will vibrate an android device for the specified number of milliseconds (1/1000th of a second). iOS will vibrate for a standard 500ms</td>
  <tr></tr>
  
  <td><b>Vibrator.Vibrate(Vibration vibration)</b></td>
  <td>Will vibrate an android device for one of the pre-set vibration lengths in the Vibration enum. Values are as follows:</br>
  <b>SHORT</b> = 100ms</br>
  <b>MEDIUM</b> = 250ms</br>
  <b>LONG</b> = 500ms</br>
  <b>VERY_LONG</b> = 1000ms</br></br>
  
  iOS will, again, only vibrate for a standard 500ms</td>
  <tr></tr>
  
  <td><b>Vibrator.Cancel()</b></td>
  <td>Will cancel any active vibration performing on the device. This method will only work on Android devices, iOS will not respond to this method call.</td>
  <tr></tr>
  
  <td><b>Vibrator.IsAndroid()</b></td>
  <td>Returns true of false depending on if the current device is Android or not.</td>
</table>
   <p>Feel free to use this is any of your projects without accreditation =)
