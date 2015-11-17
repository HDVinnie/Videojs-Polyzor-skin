## Video.js Polyzor Skin (for video.js 5)
	Customizable skin for video.js v.5
[DEMO](http://codepen.io/enygmatik/pen/NGJWRY?editors=010)
### Preview
	 Video js skin
   ![Video.js skin image](http://s12.postimg.org/grhy59p4d/Screenshot_2015_11_17_16_19_53_copy.png)
   
   User inactive
   ![video.js skin preview](http://s12.postimg.org/hiaob1rhp/Screenshot_2015_11_17_16_20_15_copy.png)

### Usage
  1. Place (polyzor-skin.min.css/polyzor-skin.css) after default video.js styles
  2. Add class  "vjs-polyzor-skin" to video tag
```html

    <link rel="stylesheet" href="video-js.css">
    <link rel="stylesheet" href="polyzor-skin.min.css">
    
    <video class='video-js vjs-polyzor-skin'></video>

```

### Settings
```scss

$primary-foreground-color: #36c183;  //#fff default

$primary-background-color: #2B333F;   //#2B333F default

//Color for video progress indicator
$progress-indicator-color: #fcfaff; //skin default #fff

//Color for mute/vol-0 icon
$mute-icon-color: red;

//Color for time text
$time-color: #fff; //skin default  #fff

//Make a slightly lighter version of the main background for the slider background.
$slider-bg-color: lighten($primary-background-color, 33%);


//Skin size settings
//----------------------------
//video bar height
$video-container-height: 5em;

//Play button size
//align center play button
$center-play-button: true;
$play-button-size: $video-container-height / 1.4;

//All controls height size
$control-buttons-size: 20px;
//TODO: add control elements width setting

//Big play button
$center-big-play-button: true; //true default
$center-big-play-button-color: $primary-foreground-color;
$center-big-play-button-hover-color: #fff;

$big-play-width: 1em;
$big-play-height: 1em;


//When user is inactive progress bar move to bottom of the player
$show-progress-bar: true; //skin default true
```




#### Notice:
	Skin version 0.1.0
