# youtube-play
This is the Polymer element which allow you to display thumbnail image over YouTube embed iframe on your web page.
Main issues that this elemene is able to solve is:

- To reduce time to implement embed YouTube video onto the page.
- To display image of the point where you want to start from. (Need to prepare image, though.)
- To prevent slow page loading by avoid filled with 'X-XSS-Protection' error in each YouTube iframe on the page.

# Live Demo

# Usage

````html
<youtube-play contentid="WsptdUFthWI" imgsrc="./images/youtube-play-sample-02.png" start="1:48" autoplay="1" size="75%" rel="0" controls="1" showinfo="0"></youtube-play>

````

- **contentid** : Content ID of YouTube video you want to embed


# License

Apache 2.0
