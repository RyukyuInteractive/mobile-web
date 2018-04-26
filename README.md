## Disable Auto Zoom for Form

set the font size of the form elements to at least 16px

```
@media screen and (-webkit-min-device-pixel-ratio:0) { 
  select:focus,
  textarea:focus,
  input:focus {
    font-size: 16px;
    background: #eee;
  }
}
```

## isMobile

```
    isMobile: function(){
	    // if(jQuery(window).width() >= 768){
        if(window.matchMedia('screen and (min-width:768px)').matches){
	        return false;
        } else {
	        return true;
        }
    },
```

## Avoid Rubber band scrolling

https://github.com/RyukyuInteractive/mobile-web/wiki/scrolling-menu-on-iPhone
