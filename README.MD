🎉 🎉 🎉

*** This is a cross-platform Video Player component for use in Xamarin Forms apps. It is based on a [project](https://github.com/adamfisher/Xamarin.Forms.VideoPlayer) by Adam Fisher, which is no longet maintained. This fork makes it work with modern versions of Xamarin Forms and adds support for more platforms. *** 

🎉 🎉 🎉


## Introduction

This Xamarin Forms component that makes it extremely easy to **render the native video player on every mobile platform** and respond to common video events all from shared Xamarin Forms code. This component provides a highly customizable development experience with a solid foundation to develop rich and visually interesting cross-platform mobile video playback.

This video player does all the heavy lifting for you, allowing you to spend more time focused on making your mobile app great and less on the intricate details of managing network state, decoding and media playback.

### A Video Player on Every Platform in 2 Minutes...

This is the simplest example of how to use the video player component that fills an entire page. Just declare the `VideoPlayer` tag in your XAML Forms page and specify the location of the video file. For more advanced configuration, check out the [Getting Started](GettingStarted.md) page.

```XML
<?xml version="1.0" encoding="utf-8" ?>
<ContentPage xmlns="http://xamarin.com/schemas/2014/forms"
             xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
             xmlns:o="clr-namespace:Octane.Xamarin.Forms.VideoPlayer;assembly=Octane.Xamarin.Forms.VideoPlayer"
             x:Class="VideoPlayerSamples.VideoPlayerBasicExamplePage"
             Title="Basic Video Player">

    <o:VideoPlayer Source="http://vjs.zencdn.net/v/oceans.mp4" />

</ContentPage>
```

### Native Mobile Performance

<img src="http://i.giphy.com/26tP7ug0D3lG9Sn16.gif" width="274" style="float:right;margin-left:1em;" />

This video player component is fully cross-platform between the iOS, Android, and Windows Phone mobile operating systems as it renders the native video player on each platform, taking on the look and feel of the operating system they are running on. This ensures your mobile application looks and works its best on each system supported.

**No complex knowledge is required to properly manage the playback of video files.** This component handles playback state and renders the native video player for each mobile platform for the best playback performance. Under the hood, this component uses the <a href="https://developer.apple.com/library/ios/documentation/AVFoundation/Reference/AVPlayer_Class" target="_blank">`AVPlayer`</a> on iOS, the <a href="http://developer.android.com/reference/android/media/MediaPlayer.html" target="_blank">`MediaPlayer`</a> on Android, and the <a href="https://msdn.microsoft.com/en-us/library/windows/apps/system.windows.controls.mediaelement(v=vs.105).aspx" target="_blank">`MediaElement`</a> on Windows Phone.

- Optimized for Xamarin
- Cross-platform Xamarin Forms XAML component
- Can play local files, embedded resources or HTTP(S)-based streamed files from the web
- Simple configuration
- Low overhead/footprint
- Handles and releases resources for you

### Platform Requirements

Please make sure the platforms you're targeting meet the minimum requirements listed below.

| Platform 			| Minimum Version    	|
|----------------	|--------------------	|
| iOS      			| 8.0+ Unified        	|
| Android  			| 4.1+ (API Level 16) 	|
| UWP  	| 10 	                |
