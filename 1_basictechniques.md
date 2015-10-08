#Getting started
_Basic Photoshop techniques_

_Salem the cat is loney at dinner. Her mom is concerned Salem isn't making any friends, and is asking Salem to send her a picture of her and her friends. Salem wants it to appear like all of her friends join her for dinner._

First, lets open Photoshop and customize the workspace.

![First opening photoshop](img/gettingstarted.png)

##Workspace
Customize the workspace by hiding and showing panels.

_Salem's paws are very nubby and sometimes she inadvertently selects the wrong panels in the workspace. In order to avoid this, Salem wants to close as many unnecessary panels as she can._

__Hiding panels__ : Right click on a panel and choose `Close`
![Hiding panels](img/workspace-hidingpanels.png)
__Showing panels__: Click `Window` and select a panel to show (Layers, etc.)
![Showing panels](img/workspace-showingpanels-1.png)
![Showing panels](img/workspace-showingpanels-2.png)
_The navigator panel has appeared_

__Saving a workspace:__ Click `Window > Workspace > New Workspace`. Name and save your workspace.
![Saving a workspace](img/workspace-saveworkspace.png)

We're ready to open an image. 

_Salem has taken a photo of herself eating dinner that she would like to photoshop friends into. Lets open it up._

__Open an image:__ Click `File > Open` or `Ctrl + o`. Open `salem.jpg`.
![Opening an image](img/workspace-open.png)

##Zooming and navigating an image

__Show the navigation panel__: Click `Window > Navigatior`

![Show navigation again](img/zoomnav-shownav.png)

__Zoom in__: Select the zoom tool (Z). Click on the place you want to zoom into.

![Zoom in](img/zoomnav-zoomin.png)

__Navigate with navigation panel__: Drag on the `Navigation` pane to navigate around the image.

![Zoom in](img/zoomnav-navigate.png)

__Hand tool__: Press `H` or click the hand icon on the left toolbar. Drag to navigate with the hand tool.

__Automatically fit an image to the window__: `cmd + 0` or `View > fit on screen`

![View whole image](img/zoomnav-viewwholeimg.png)

##Basic techniques
_In order to make it seem like Salem has some friends, we are going to copy and paste some kittens into this lonely photo of Salem that we found on Google Image search._

###Copy/move (within same image)
_First we want to create more places for Salem's friends to eat. We'll copy the plate that's already on the table._

1. There are a few ways to do this. We can use the `Quick Selection Tool (W)`, `Magic Wand Tool (W)`, or the `Lasso Tool`. Select the plate using the `Quick Selection Tool`.

![Select the plate](img/basictechniques-copypastesame-1.png)

Copy and paste the plate (`Ctrl-C` and `Ctrl-P`, alternatively `File > Copy` and `File > Paste`). This will create a new layer.

![Select the plate](img/basictechniques-copypastesame-2.png)

Since the new plate is its own layer, we can drag around the plate without affecting the _Background_ layer. We can rename this layer "plate 1"

2. Select the `Move tool (V)`. Drag the plate downward. 

![Move plate downward](img/basictechniques-copypastesame-3.png)

3. There are extra pixels on the edges of the plate. We can use the `Eraser Tool (E)` to erase the extra information. There is a better way to manage selections (layer masks) which will be covered later.

Edit the brush settings to suit the size of the plate.

![Edit brush settings](img/basictechniques-copypastesame-3a.png)

Zoom in on the plate and erase the extra information. 

![Erase plate information](img/basictechniques-copypastesame-4.png)

4. The plate still looks weird. Use `Transform (Ctrl + T)` to scale the plate up to match the perspective of the image. 

![Scale plate](img/basictechniques-copypastesame-5.png)

5. Lets use the `Burn Tool (O)` to add more imperfections to help the second plate blend in. This will darken the pixels in the plate, like we have "burned it."

![Burn the plate](img/basictechniques-copypastesame-6.png)

6. Try to add a third plate.

![Add a third plate](img/basictechniques-copypastesame-7.png)

###Copy/paste (between different images)
_We're ready to add in some friends. First we should open the cat photos in new tabs._

1. Open `cat.png`. 
2. Select all `Ctrl + A`, copy `Ctrl + C`.
3. Navigate to `Salem.jpg` and paste `Ctrl + P`. 

![Paste cat](img/basictechniques-copypastesame-8.png)

Notice how the cat we have copied into the image is grey. This is because the color mode of `Salem.jpg` is Grayscale. We can view this in `Image > mode`.

![View color mode](img/basictechniques-copypastesame-9.png)

4. Resize the cat and order it underneath the plates.
5. There is a little white on the outline of the cat. Lets try to remove that using the `Refine Edge tool`. First hold `cmd` while clicking the cat layer's thumbnail. This should select the outline of the cat layer. Click the `Refine Edge` button on the top toolbar. We can add a little feather to the outline and shift the edge inward a little bit.

![Select outline of the cat](img/basictechniques-copypastesame-10.png)
![Refine the outline of the cat](img/basictechniques-copypastesame-11.png)

Invert the selection using `Cmd + shift I` and delete. 
![Invert and delete the selection](img/basictechniques-copypastesame-12.png)

###Noise restoration
_Salem's friend still looks professionally photographed (Salem only has his grandma's camera to take photos of herself. We'll need to add noise to Salem's new friend to make this image more believeable.)_

1. First, we will edit the colors in the photo. We can add an bightness/contrast adjustment layer. Adjustment layers are useful because they can be edited and re-edited at any point. 

![Add adjustent layer](img/basictechniques-copypastesame-13.png)

2. We'll create a clipping mask so that the adjustment layer will only affect the layer with the kitten beneath it. 

![Create clipping mask](img/basictechniques-copypastesame-14.png)

Now we can make the kitten layer more grey.
![Make layer more grey](img/basictechniques-copypastesame-15.png)

Lets also apply a blur filter to make the kitten blend a little better with the image.

![Select blur](img/basictechniques-copypastesame-15a.png)
![Add Gaussian blur](img/basictechniques-copypastesame-16.png)

3. Lets add another layer to add some shadows to the kitten. Be sure the new layer is below the adjustment layer, and also has an arrow indicating it is a clipping mask. 
![Select brush](img/basictechniques-copypastesame-17.png)

We've selected a brush with 0 hardness in a black color, using the mode "darken".

4. We can now combine these layers in a group. First, select all the layers. Then, select the folder icon at the bottom of the layers pane.

![Select brush](img/basictechniques-copypastesame-18.png)

5. If we wanted to take things a step further, we could have saved the file we copied `cat.png` in a low quality .jpg format in order to mimic the jpeg artifacts in salem's original photo.

![jpeg artifacts](img/basictechniques-copypastesame-19.png)

###Add a reflection

Now, lets add a reflection to the image in order to add even more realism. First, we can copy the group of layers that comprise the kitten. Then, we can transform the entire group of layers, rotating them 180 degrees. 

![jpeg artifacts](img/basictechniques-copypastesame-20.png)

Then, we need to change the blend mode of the kitten layer. We can change it to overlay, so it blends in and matches more closely the pattern of the table. We can also bring down the opacity of the layer to make this effect more subtle.

![jpeg artifacts](img/basictechniques-copypastesame-21.png)

###Remove objects

_Salem realizes the coaster her mother had been asking Salem to return is in the front and center of the table! Rather than crop the photo, Salem decides to remove it using Photoshop Magic._

1. Double click the background layer in order to convert it to a regular layer, "layer 0".

![Convert background layer](img/basictechniques-copypastesame-22.png)

2. Select the patch tool. Click and drag around the coaster. The technique for removing objects will vary from case to case. In this instance, we can get away with continuously patching the area vertically to match the reflection from the window behind. 

![Use patch tool](img/basictechniques-copypastesame-23.png)
![Use patch tool](img/basictechniques-copypastesame-24.png)

Use the `Blur Tool` too smooth out the resulting patched area.

![Use blur tool](img/basictechniques-copypastesame-25.png)


###Add more noise
Finally, we can add a noise filter to try to uniformly distort the image. 

1. Create a new layer `Cmd + shift + N` at the top of the layers. Name it noise. Select "Overlay" for the Mode and check the box "Fill with Overlay-neutral color (50% grey)". 

![Use blur tool](img/basictechniques-copypastesame-26.png)

2. Go to `Filter > Noise > Add Noise` to bring up the Add Noise dialog. Select 10% under Amount and Gaussian under Distribution. Click ok. 

![Use blur tool](img/basictechniques-copypastesame-27.png)

3. Reduce the opacity of this layer to 40%. 

![Use blur tool](img/basictechniques-copypastesame-28.png)

_Finished! Salem will send the photo to her mother._

======

[Advanced Layer Tasks >](2_advancedtechniques.md)