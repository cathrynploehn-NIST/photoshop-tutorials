#Color and Brushes

_Another cat has said mean things about Salem. Salem wants to change this cat's eyes to red, to reflect the meanness inside this cat._

##Select and change colors

Changing any selected color is easy using layer masks and the `Color Range` function. 

[Video: How to Select and Change Colors in Photoshop](https://www.youtube.com/watch?v=n9fwiNyDHLI)

Open `cat-sink.jpg`. 

Open `Select > Color range`.

![Color range](img/retouching_19.png)

In the dialog box, click the eye dropper tool with a plus. 

![Color range](img/retouching_20.png)

Use the `space + cmd` shortcut to zoom in on the cat's eyes. Click and drag within the eye. The preview in the center of the dialog box will show selected areas of the image in white, and unselected areas in black. This is adding a range of yellows to be selected. 

![Color range](img/retouching_21.png)

We can now make a new adjustment layer to apply to just this selection. With the eyes still selected, go to `Layer > New adjustment layer > Hue/saturation` to create a new `Hue/saturation` layer. 

![Color range](img/retouching_22.png)

Adjust the hue sliders until the eye turns red. Using a saturation somewhere in the middle is suggested.  

![Color range](img/retouching_23.png)

_Salem wants to take this a step farther. She wants the entire cat to be red!_

Duplicate the background layer. Select the cat using one of the methods described earlier (background eraser, quick select tool, etc.).

![Color range](img/retouching_24.png)

Add a red layer. Hide the Hue/saturation layer for the cat's eyes. Change the blending mode to `Overlay`, reduce the opacity to 50%, and create a clipping mask (`option/alt` + click between the layers). Now the entire cat is red!

![Color range](img/retouching_25.png)

We can also add another layer of red to give the entire photo a similar red tint. 

![Color range](img/retouching_26.png)

_Very evil._

#Brush management

_Still, Salem is not satisfied. She wants to add some black splatters around the image to make the cat look additionally creepy. In order to do this, we will have to add some new brushes._


##Adding brushes
Download a brush (.abr file type), for example: [this splatter set from Smashing Magazine](http://www.smashingmagazine.com/2008/10/splatter-and-watercolour-brushes-for-photoshop/#download-the-sets-for-free)
Move into `Applications > Photoshop CC > Presets > Brushes`

![brush management](img/retouching_28.png)

In Photoshop, select the `Brush tool (B)` and open the brush settings by clicking the arrow next to the brush preview. Click the small gear and select `Load brushes`. Open the brushes you have just selected in Photoshop. 

![brush management](img/retouching_27.png)

The brushes should be appended to the bottom of the brush selection pane. 

![brush management](img/retouching_29.png)
![brush management](img/retouching_30.png)

Add some splatters to the image on a layer named `splatter`.

![brush management](img/retouching_31.png)

We can transform for perspective of these splatters to match the image.

![brush management](img/retouching_32.png)
![brush management](img/retouching_33.png)

Change the blending mode to `Overlay`, convert the layer to a Smart Object, and add some blur.

![brush management](img/retouching_34.png)

##Organize brushes

Select the `Brush tool (B)` and open the brush settings. Click the gear and select `Preset Manager`.

![brush management](img/retouching_35.png)

You can reorder, add, and delete brushes from here. You can also save subsets of these brushes as a preset to load. Select and drag the splatter brushes to the top of the pane.

![brush management](img/retouching_36.png)

##Create a new brush

_Salem wants to create a brush with her signature on it so she can sign her work with her name. We need to create a custom brush in Photoshop._

Custom brushes can be created to create a very specific, unique effect.

[Video: Advanced Photoshop Brushes](https://www.youtube.com/watch?v=CrT64oGebiM)
Start with a new document by selecting `File > New...` and editing the settings.

![brush management](img/retouching_37.png)

Add a white background layer and a transparent layer on top to begin with. Select the `Brush Tool (B)`. You might have to go to the brush panel to decrease the spacing on the brush you choose.

![brush management](img/retouching_39.png)

Draw a cat face. 

![brush management](img/retouching_38.png)

Select the `Marquee Tool (M)` and select the cat. Go to `Edit > Define Brush Preset` to define a new brush. 

![brush management](img/retouching_40.png)

Enter the name `kitty`. 

![brush management](img/retouching_41.png)

Go to the brush panel (if it is not visible, go to `Window > Brush`). There you can see the newly added brush preset. You can edit the brush with the options in the left sidebar. We have increased the spacing to prevent the cat heads from merging together.

![brush management](img/retouching_42.png)

Navigate to `cat-sink` and create a layer named `signature`. We can now use our new brush to create a signature in white in the bottom right corner of the image. 

![brush management](img/retouching_43.png)

======

[< Home](README.md)

[5. Strategy: Putting it all together >](5_strategy.md)