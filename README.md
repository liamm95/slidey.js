# slidey.js
Simple image slider, mobile ready. The most simple but effection slider out there!

## Usage
Slidey has only one configuration option, which is the threshold of when Slidey should go over to the next image when user is dragging. This is a percentage and is calculated on how much the mouse has travelled.

The default is 10%.
```javascript
imageSlider();
```

To change this setting simply do:
```javascript
imageSlider({
  threshold: 30,
});
```

Slidey will automatically initialized itself on every element on the page that has .image-slider class.

You can also change this by simply doing:
```javascript
imageSlider({
  parent: $('.your-swag-class'),
});
```

Ultra simple, no? I think so.
