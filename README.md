
# Shipwaze
Started a small project that will ask users to enter the from and to locations where the item(s) is going to be move using less than truck loads apis from 3rd party logistic companies. Eg. USP, Fedex, Dominion, AAA Cooper, Pilot Freight and more... I have at the moment a website using Unify Template, MVC framework, C#. These will be my core components Google map apis, KnockoutJS, jQuery, RequireJS and Typescript to implement the product.

<ul>
<li>
<a href='https://htmlstream.com/preview/unify-v1.9.8/index.html'>Unify</a> is an incredibly beautiful responsive Bootstrap Template for corporate and creative professionals. It works on all major web browsers, tablets and phone.
</li>

<li>
<a href='https://developers.google.com/apis-explorer/#p/'>Google Apis</a> is a set of application programming interfaces (APIs) developed by Google which allow communication with Google Services and their integration to other services. Examples of these include Search, Gmail, Translate or Google Maps. Third-party apps can use these APIs to take advantage of or extend the functionality of the existing services.<sup><a href='https://en.wikipedia.org/wiki/Google_APIs'>Read more...</a></sup> 
</li>
<li>
<a href='http://knockoutjs.com/'>KnockoutJS</a> s a JavaScript library that helps you to create rich, responsive display and editor user interfaces with a clean underlying data model.<sup><a href='http://knockoutjs.com/documentation/introduction.html'>Read more...</a></sup>
</li>
<li>
<a href='https://jquery.com/'>jQuery</a> is a fast, small, and feature-rich JavaScript library. It makes things like HTML document traversal and manipulation, event handling, animation, and Ajax much simpler with an easy-to-use API that works across a multitude of browsers.<sup><a href='http://api.jquery.com/'>Read more...</a></sup>
</li>
<li>
<a href='http://requirejs.org/'>RequireJS</a> is a JavaScript file and module loader. It is optimized for in-browser use, but it can be used in other JavaScript environments, like Rhino and Node. Using a modular script loader like RequireJS will improve the speed and quality of your code.<sup><a href='http://requirejs.org/docs/api.html'>Read more...</a></sup>
</li>
<li>
<a href='https://www.typescriptlang.org'>Typescript</a> is a typed superset of Javascript that compiles to plain Javascript..<sup><a href='https://www.typescriptlang.org/docs/tutorial.html'>Read more...</a></sup>
</li>
</ul>




# Video Converter (FFmpeg )
C# wrapper that allows you to convert media type to any format using 

<a href='https://ffmpeg.org/about.html.'>FFmpeg</a> is the leading multimedia framework, able to decode, encode, transcode, mux, demux, stream, filter and play pretty much anything that humans and machines have created. It supports the most obscure ancient formats up to the cutting edge. No matter if they were designed by some standards committee, the community or a corporation. It is also highly portable: FFmpeg compiles, runs, and passes our testing infrastructure FATE across Linux, Mac OS X, Microsoft Windows, the BSDs, Solaris, etc. under a wide variety of build environments, machine architectures, and configurations.

<h3>Eg.</h3>

```
public void ConvertVideo() {
  var toSettings = new VideoConversionSettings();
      toSettings.VideoBitrate = 16;
      toSettings.FrameRate = 23.97;
      toSettings.AudioBitrate = 192;
      toSettings.Width = 1024;
      toSettings.Height = 512;
      toSettings.VideoFormat = VideoFormat.mkv;
      toSettings.SourcePath = @"\SourcePath";
      toSettings.TargetPath = @"\TargetPath";

      var convertToVideo = new VideoConversion(toSettings);
	
      //Capture image of the first frame
      convertToVideo.ToJpeg(); 

      //Convert Current Video to the specified settings *.mkv
      convertToVideo.ToNewVideoFormat();
}
```
