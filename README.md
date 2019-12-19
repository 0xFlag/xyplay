# xyplay
使用WebView，目前用于解析视频
</br>
编程语言：Java</br>
编程软件：Android studio 3.5.2</br>
</br>
部分代码注释：</br>
AndroidManifest.xml
<uses-permission android:name="android.permission.INTERNET"></uses-permission>
</br>
开启网络权限</br>
android:hardwareAccelerated="true"
</br>
android:configChanges="orientation|keyboardHidden|navigation|screenSize"
</br>
android:screenOrientation="sensor"
</br>
根据物理传感器方向转动，用户90度、180度、270度旋转手机方向，activity都更着变化</br>
</br>
MainActivity.java</br>
webView.loadUrl("localhost");
</br>
WebView加载网址</br>
</br>
styles.xml
</br>
<style name="AppTheme" parent="Theme.AppCompat.Light.NoActionBar">
</br>
无标题栏
