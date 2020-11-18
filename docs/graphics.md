---
layout: default
---

# Computer Graphics

Computer graphic can be classified into 2 groups
|Raster |Vector  |

|--------|-------------|

|Deals with images with pixels on a screen. Mainly used for rendering images i.e. photographs. The size of the image is represented by the pixels it has by its length and width. The image when zoomed in will become blurry but it will be possible to see each pixel that makes up the image. Some software used for editing raster images are [GIMP](https://www.gimp.org/), [Photoshop](https://www.adobe.com/sea/products/photoshop.html) and MS Paint. File formats for rasters are PNG and JPEG/JPG|Uses paths, points, curves and polygons to model the image. With the use of mathematical functions or algorithms it will display the image on the screen. The vectors have clean edges and so if you zoom in there will be no distortion. Used yo format logos, posters, signs, etc. Software used for vectors are [Inkscape](https://inkscape.org/) and [Illustrator](https://www.adobe.com/sea/products/illustrator.html). Some common vector file formats are .dxf, .svg and STEP|

## Photoshop
I have decided to learn a little bit about photoshop as I have access to it. The task is to remove the background of the photo and replace it with the seaside view.

|Photo |Seaside View  |

|--------|-------------|

|(person.jpg)|(seaside.jpg)|

Steps:
1. Import your image with the person into photoshop
2. Click on the Quick selection tool and press select subject in the top
3. After doing that, click Select and Mask also in the top
(mask.jpg)
4. Use the refine edge brush tool to clean up the edges on the hair. For it to be more visible you can switch the mode of background view.
(view.jpg)
5. From output settings select Output to: `Layer mask` and click OK
(psoutput.jpg)
6. Create a new layer and shift it below the masked layer. Call it seaside layer
7. Import your seaside view to your seaside layer.
8. Resize the subject to fit the image. and there you have it.
(photoshopfinal.jpg)
(personedit.jpg)
You can export the image by clicking Save As, Save as type: JPEG
