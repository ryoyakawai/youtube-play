# youtube-play (Polymer Element)
This is the Polymer element which allow you to display thumbnail image over YouTube embed iframe on your web page.
Main issues that this elemene is able to solve is:

- To reduce time to implement embed YouTube video onto the page.
- To display image of the point where you want to start from. (Need to prepare image, though.)
- To prevent slow page loading by avoid filled with 'X-XSS-Protection' error in each YouTube iframe on the page.

# Live Demo
[Demo](//ryoyakawai.github.io/youtube-play/)

# Usage
To use this element: 
- 2 lines for preparing
- write `<youtube-play></youtube-play>` tag where you want to put YouTube video.

````html
<script src="https://polygit.org/components/webcomponentsjs/webcomponents-loader.js"></script>
<link rel="import" href="youtube-play.html">

<youtube-play contentid="WsptdUFthWI" imgsrc="./images/youtube-play-sample-02.png" start="1:48" autoplay="1" size="75%" rel="0" controls="1" showinfo="0"></youtube-play>

````

Attributes:

- **contentid** : Content ID of YouTube video you want to embed
- **imgsrc** : path for your image that you want to display over YouTube embed iframe
- **start** : starting time where YouTube video to be started (Both 'hh:mm:ss' and only sec format is supported by auto detect)
- **autoplay** : set '1' for starting playing automatically after the image is clicked otherwise set '0' or remove this attribute.
- **size** : set size of width from window. This attribute is required.
- **rel** :  set '1' for providing to display related link after the video reached to the end.
- **controls** : set '1' for providing to video control buttons, remove control button set '0'
-**showinfo** : set '1' for providing information, such as video title etc, during playing, set '0' for removing all of those.

# License

Apache 2.0
