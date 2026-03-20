---
layout: default
title: Preparing Image for Laser Engraving
nav_order: 2
parent: Workshop Activities
---

# Vectorizing your Design in Inkscape 

## Importing and Sizing Document

1. Open Inkscape. Select “Open” and navigate in your files to your saved .png file.

2. A window will pop up asking for things like Image Import Type and Image DPI. Leave everything at default (Should look like this) and press “OK” at the bottom.

3. Next, let’s check the size of the file in inches or cm. At the top of the window there should be two numerical values next to the letters “W” and “H” with a lock in between them. Select the drop down menu directly to the right of the H window and scroll to find inches or cm. Click on either and it will show you in the “W” and “H” windows what size your image is in that measurement.

4. If you are unhappy with that size, simply click on the lock button in between the W and H and then change one of the measurements, H for example, to the height you want it to be. Because you selected the lock, when the image changes size, it will retain the same aspect ratio. 

5. Now you may notice that your image is not the same size as the canvas which will be an issue when exporting as whatever is visible on the canvas itself is what gets exported. To fix this, we will go to “File”, “Document Properties” and then you will be shown a new window.

6. Under “Front page” there will be a width and height option again. Change your measurement to the same units you used to change the size of the image (if you used cm, use cm here again) and change the size to be the same as those sizes in both the width and the height. Simply press the “x” in the top right corner to exit the window and apply your change 

7. Recenter your image if needed to be centered on the canvas 

## Vectorizing 


1. Select “Path” at the top of your window, and choose “Trace Bitmap”. A new window on the right should pop up. 

2. Left click on your image to make sure it is selected. You’ll know it is selected hwen there are black arrows surrounding the image, or more importantly, if you can see it in the new window that appeared. 

3. In this image you can adjust the settings for vectorizing your image. You can extend the new window out to the left to enlarge the image of the preview. 

4. We are going to use the generic “Brightness cutoff” detection mode. You can adjust the threshold up or down. Keep an eye on the preview. The higher the threshold, the more pixels will be converted to Vector. 

5. Be sure to select “Invert Image” for woodblock printing purposes. If you want a positive print, you need to invert it. If you want a negative print, keep it as is. Remember, the parts that are black will be the parts that are engraved and not visible in the final print. 

6. If you want, you can adjust the smoothness of the corners, speckles, or optimize. These are completely up to you and we encourage you to play around with your settings.

7. Press “Apply” to trace the bitmap. It will be directly overlaid your old image on the canvas, so click to select it and move it aside. You can compare them side by side and if you are unhappy with your result simply go to “Edit” and then “Delete” to delete your vector version. Retry until you get settings you are happy with.  

## Cleaning up the Image 

You may want to edit some lines or delete some pieces off of the vectorized result. 

1. Go to "Node Tool" on the left under the black arrow button. Your design will now have grey boxes all over it. These are the *"nodes"*.

2. Zoom in close by holding "ctrl" or "command" on your keyboard and scrolling.

3. You can left click on any of the nodes to move them around, or press "Delete" on your keyboard to remove unwanted ones.

4. Once finished, choose the black arrow above the Node Tool to go back to selection mode. 

## Flipping your Image

1. If you are doing woodblock printing, your design needs to be flipped so that the image that is produced on the paper is the same orientation as the original design. 

2. Select your design and go up to the top window bar beneath “Path and Text”. There will be two triangles which are orientation flipping buttons. There is a horizontal one, meaning you flip it along the horizontal axis, or there is a vertical one meaning you flip it along the vertical axis. Let’s click on “Object Flip Horizontal”. Now your image should be flipped left to write. 

3. Trace bitmap to path by selecting “Path” “Trace Bitmap” and then adjusting your settings like the threshold. Make sure to select “INVERT IMAGE”. This is integral to your result as you want the . You can view your result the preview box below those settings before selecting “Apply”. 

4. Drag your result away from the original image. Compare and if you are happy with the result, click on the original and delete it out of the canvas. Recentre your new vectorized inverted image. 

5. Flip the image horizontally. Your image must be mirrored so that when you stamp it, it comes out the right orientation!

## Adding a Cutting Guide

1. In order to make sure the laser cutter cuts your piece as the correct size, we need to create a guideline for it. You can pick any shape you want, but typically squares or circles work best depending on your design.

2. Select the "Rectangle Tool" and left click and drag on your canvas to make a rectangle or square that fits your design in it. 

# Exporting your Image

1. First, make sure your image is centered on your canvas and double check that you are happy with the image size as we did in the importing step.

2. Go to "File", then "Export". An exporting window will pop up on the right hand side.

3. Select the "Folder" icon above "Export" to choose a save location in your files.

4. Next choose, your file type. Pick "Inkscape SVG". This means Scaleable Vector Graphic and this is the image format 






















[NEXT STEP: Vectorizing your Design in Inkscape](vectorizing-design.html){: .btn .btn-blue }
