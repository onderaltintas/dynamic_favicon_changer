# dynamic_favicon_changer
javascript implementation for changing favicon dynamically

you can add text to favicon or simply change the icon with another png. the only requirement is the icon should be a png file and the browser should be a new one which makes 2 requirements. 

measures the text size and changes font size dynamically up to text's size. 

usage:
  var text = "1";
  var imageSrc = "favicon.png";
  var faviconChanger = new FavIconChanger();
  favIconChanger.changeFavicon(text,imageSrc);
