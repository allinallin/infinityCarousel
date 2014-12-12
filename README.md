# jQuery Infinity Carousel
Boilerplate for creating a full-width repeatable slideshow.

## Demo
[Codepen](http://codepen.io/allin/pen/QwNGBb)

## TODO
- Make it a plugin

## Dependencies

- [jQuery](http://jquery.com/)
- [Modernizr](http://modernizr.com/) test for csstransforms3d
- [Sass](http://sass-lang.com/) is optional

## Usage
Instantiate the carousel with the following:
```javascript
$(function(){
    $('.infinity-carousel').each(function() {
        infinityCarousel( $(this) );
    });
});
```
This type of slideshow is only practical for slideshows that have enough slides to warrant repeating.


## Required files
```
css/infinityCarousel.css`
js/infinityCarousel.js`
index.html
```

## Recommended files
The sass file `scss/infinityCarousel.scss` contains variables for easier style configuration.