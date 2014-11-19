## WakCropImages Widget for [Wakanda](http://wakanda.org)

The __WakCropImages__ widget allows you to display a image editor, which crop and resize image. The result of your editing, you can upload to wakanda server's folder or in an attribute of type image. This widget is based on the Image Cropper plugin -written by Fengyuan Chen (https://github.com/fengyuanchen/cropper).

Drag and drop to the Wakanda Studio

!["captura1"](http://nsae01.casimages.net/img/2014/11/13/141113050643401712.png "captura1")

Widget in the browser

!["captura2"](http://nsae01.casimages.net/img/2014/11/13/141113050643669326.png "captura2")

!["captura3"](http://nsae01.casimages.net/img/2014/11/13/141113050643837820.png "captura3")

Get the result

!["captura4"](http://nsae01.casimages.net/img/2014/11/13/14111305064465974.png "captura4")


### Properties
This widget has the following properties:

* __placeholder__: placeholder of the widget.
* __label__: label of the widget

### Events
This widget has the following events:

* __save__: Fired when the button(save) is clicked. Here you can get the result of image editing as data URI scheme. Example: `var dataUri = event.data.dataUri;`


### More Information
For more information on how to install a custom widget, refer to [Installing a Custom Widget](http://doc.wakanda.org/WakandaStudio0/help/Title/en/page3869.html#1027761).

For more information about Custom Widgets, refer to [Custom Widgets](http://doc.wakanda.org/Wakanda0.v5/help/Title/en/page3863.html "Custom Widgets") in the [Architecture of Wakanda Applications](http://doc.wakanda.org/Wakanda0.v5/help/Title/en/page3844.html "Architecture of Wakanda Applications") manual.
