#Video Player Plugin for Phonegap Android

This is simple Phonegap Plugin to play videos in Android application. 

1. Initialy, move *vplayer.js* file into your **www** folder and add line in your index.html 

	```
	<script src="vplayer.js"></script>
	```
2. Add *VPlayer.java* file into your **src** folder and do not forget set your package name.

3. This part important for you to define this plugin as functional. Open your *config.xml* in your **res/xml** folder. Add a line as:

	```
	<plugin name="VPlayer" value="your.package.name.VPlayer" />

	```
	
To use this plugin just call it as:

```
window.plugins.vplayer.show({ videopath: "http://example.com/example.mp4" },{},{});
```

Note: I tested on Cordova 2.9!