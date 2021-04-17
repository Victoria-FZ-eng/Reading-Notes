# Audio, Video, Images.

## Images

* You can control the `width:` and `height:` of the images , and align them using `margin:` , `float:`.
* To center an imag --> `display: block ; margin:  auto;`.
* You can add background images , `backgroung-image:url("link or relative path");`, you can control the background `background-repeat: ` or `background-attachment: `, and you can control it's position `background-position: `.
* You can change the style of an image when the mouse is ver the image (rollover) using `:hover`.

## SEO (search engine optimization)

>Search engine optimization is the practice of trying to help your site appear nearer the top of search engine results when people look for the topics that your website covers.

### Techniques:

* On page :
    1-Page Title
    2-URL / Web Address
    3-Headings
    4-Text
    5-Link Text
    6-Img Alt Text
    7-Page Decriptions.
* Off page techniques.

You need to identify some key words , learn about your visitors and what are they requiring.

## Videos 

You can apply them to your page by javascript using the ***SWFObject***. But you need to:
1- Convert your video into FLV format.
2- Find an FLV player to play the video.
3- Include the player & video in your page.
And this is not used anymore.

For HTML5 , you can use `<video>` and `<audio>` tags, You can control video and audio players programmatically by `HTMLMediaElement.play()` and `HTMLMediaElement .pause()`. (you need to wrap the audio and video elements in `div` and include some other elements like `<source>`,`<bottom>` and `<span>`,....) , and of coarse you can use CSS for styling.

you need to use event listener , to stop and play a video or an audio (ex. `play.addEventListener(action, function)`), you can move them forward and backward (`fwd` and `rwd`)

For more information check the linked url below in the references.




References :

* Ch.16 & Ch.19 / *HTML & CSS: Design and Built Websites.JON DUCKETT*.
* Ch.9 / *HTML & CSS: Design and Built Websites.JON DUCKETT*.
* [URL](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Video_and_audio_APIs).