# Colorbox Lightbox for WordPress

[Colorbox](https://noorsplugin.com/wordpress-colorbox-plugin/) plugin is a simple lightbox tool for WordPress. It allows users to pop up content in lightbox using the popular jQuery ColorBox library. They can also view the larger version of a particular media file without leaving the page. It was developed by [noorsplugin](https://noorsplugin.com/) and is currently being used on over 10,000 websites. 

## Features

* Beautiful lightbox popup style
* Flexiblity of creating your own lightbox link
* Pop up custom/HTML content in lightbox
* Trigger lightbox from either a text/image link
* Comptaiblie with WordPress multisite
* Add lightbox to a YouTube or Vimeo video link
* Enable lightbox functionality on your site which supports all major browsers
* Use a simple shortcode anywhere on your site (Post, Page, Homepage etc.)to pop up a media file in lightbox
* Apply lightbox effect on images inserted into WordPress post/page
* Open external page in lightbox using iframe
* Responsive lightbox popup which works on mobile devices. Also it fits perfectly on smaller screens.

## WordPress Colorbox Plugin Usage

### Open image in lightbox

Create a new post/page and use the following shortcode to create a text/image link which will trigger lightbox once clicked:
```
[wp_colorbox_media url="http://example.com/wp-content/uploads/images/overlay.jpg" type="image" hyperlink="click here to pop up image"]
```
here, url is the link to the media file that you wish to open in lightbox and hyperlink is the anchor text/image.
```
[wp_colorbox_media url="http://example.com/wp-content/uploads/images/overlay.jpg" type="image" hyperlink="http://example.com/wp-content/uploads/images/thumb.jpg"]
```
### Open YouTube video in lightbox
```
[wp_colorbox_media url="http://www.youtube.com/embed/nmp3Ra3Yj24" type="youtube" hyperlink="click here to pop up youtube video"]
```
### Open Vimeo video in lightbox
```
[wp_colorbox_media url="http://www.youtube.com/embed/1284237" type="vimeo" hyperlink="click here to pop up vimeo video"]
```
### Show Title in lightbox
```
[wp_colorbox_media url="http://example.com/wp-content/uploads/images/overlay.jpg" title="overlay image" type="image" hyperlink="click here to pop up image"]
```
### Specify an Alternate Text for an Image
```
[wp_colorbox_media url="http://example.com/wp-content/uploads/images/overlay.jpg" title="overlay image" type="image" hyperlink="http://example.com/wp-content/uploads/images/thumb.jpg" alt="Thumbnail image description"]
```
### Apply Custom CSS

You can specify your own CSS class in the shortcode to customize a text/image link.
```
[wp_colorbox_media url="http://www.youtube.com/embed/nmp3Ra3Yj24" type="youtube" hyperlink="click here to pop up youtube video" class="custom_class"]
```
Multiple CSS classes can be separated with a space. For example:
```
[wp_colorbox_media url="http://www.youtube.com/embed/nmp3Ra3Yj24" type="youtube" hyperlink="click here to pop up youtube video" class="custom_class custom_class2"]
```
## Documentation

For detailed documentation please visit the [jQuery Colorbox Plugin](https://noorsplugin.com/wordpress-colorbox-plugin/) page.
