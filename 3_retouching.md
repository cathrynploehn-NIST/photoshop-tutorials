#Retouching

_Salem recently had a conversation on the phone with her mother. Apparently the other cats in the neighborhood have been gossiping about Salem. In order to get her revenge, Salem decides to use her new Photoshop skills to edit some of the Facebook photos of these gossiping cats._

##Non-destructive editing

In general, it's best practice to use __non-destructive editing__, or editing photos without destroying source pixels. This allows for the ability to reverse every edit made and prevent permanent changes to the source image. In particular, when using tools like _healing brush_ and _clone stamp_, it's optimal to create a new layer to work with these tools. 

##Clone stamp

__Clone stamp versus healing brush__

_Salem decides to first alter a photo of the bengal cat telling everyone that Salem doesn't use a litterbox. Salem wants to transform this cat into a ghost._

The healing brush, the tool we used before, takes the texture of the area sampled and combines it with the color of the area painted (sampling colors and blending them from the surrounding pixels) for the final result. On the other hand, the clone stamp takes a _clone_ of the sampled area without blending with the colors in the area that is painted.

[Video: When To Use Clone Stamp Vs Healing Brush](https://www.youtube.com/watch?v=eDAxK-f04xs)

Lets demonstrate the difference between the healing brush and the clone stamp.


Open `cat-wood.jpg`.

![Open](img/retouching_1.png)

Select the clone stamp tool. Change the brush settings so that `Hardness` is at `0%` and `Size` is at `90px`. The brush should be large enough to cover a good portion of the area Some shortcuts for navigating:
- Hold `space` to use the `hand tool`
- Hold `space + cmd` to zoom in
- Hold `space + cmd + option/alt` to zoom out
- Hold `cmd + 0` to fit the image to the page

Hold `cmd` and click to select an area to sample. Click and drag to clone over the layer.

![Clone](img/retouching_2.png)

Notice we are directly editing this image, performing destructive editing. Undo the edit we just made. Create a new layer labeled `wood`. Make sure the layer `wood` is selected. Also, make sure the `Sample` setting at the top toolbar is set at `All layers`.

![Clone](img/retouching_3.png)

Redo the edit. Now we can show and hide the edits to the background image while retaining the original image. Notice the 

![Clone](img/retouching_4.png)

Lets contrast this with how the healing tool works. Create a new layer `wood-healing`. Select the healing tool. Make sure the brush's size is `90px` and has `0%` hardness. Make sure you change the setting `Sample` to `All layers`.

![Healing test](img/retouching_5.png)

Sample the same area as we did with the clone tool before. Click and drag with the tool. Notice the healed spots are much darker in this layer compared to the clone tool. This is because the healing brush has tried to blend in the surrounding colors. We can show and hide `wood` and `wood-healing` to compare and contrast the effects of the clone stamp tool and healing brush tool.

![Healing test](img/retouching_6.png)

Delete the `wood-healing` layer. 

Our goal is to sample as much of the wood as we can to remove the cat. Continuously sample and paint using the clone stamp tool until the entire cat is gone. 


This was a quick job, and the background is a little messy. With more time, the end result should be much better. In this case, it is not necessary because we'll retain the cat over the top of the wood. 

![Healing test](img/retouching_7.png)

##Clone source panel 

However, the `Clone source` panel can help us with the accuracy of our cloning. 
Go to `Window > Clone Source`. The `Clone source` should appear. You can save this in your workspace if you want. 

![Healing test](img/retouching_7a.png)

__Features of the clone source panel:__
- Save multiple clone sources

![Healing test](img/retouching_7b.png)
- Transform the clone source
 
![Healing test](img/retouching_7c.png)

- Change the visibility of the clone source
    
![Healing test](img/retouching_7d.png)


First, click `Show Overlay` on the clone source panel and change the opacity to 50%. Change the rotation if needed. Now we can see exactly where we are painting. 

Hide the `wood` layer. Create a new layer `better wood`. We can now use the overlay and rotate the sampled image as we need to match the lines of the wood. This will help us create a more perfect clone of the wood lines than last time.

![Clone panel](img/retouching_7f.png)

Now we can continue to clone the wood until the cat is completely gone.

![Clone panel](img/retouching_7g.png)

Lets compare this clone to the previous one.

![Clone panel](img/retouching_7h.png)

Delete whichever clone layer you want to discard, and rename that layer `wood`.

Change the opacity of the `wood` layer to about 50%. The cat should show through now. 

![Healing test](img/retouching_8.png)

##Layer blending options

There are a number of reversible edits we can make to individual layers. For example, we can change blending options such as fill color and blending mode from a feature called `Blending options`.

Using this feature, we are going to turn the cat white like a ghost and add a glow. 

Create a copy of the background layer and name it `cat`. Use your method of choice to create a layer mask with the cat as the selection. In this example I used the quick selection tool to create an initial selection, then used the `quick mask` to refine the selection.

![Healing test](img/retouching_9.png)
![Healing test](img/retouching_10.png)

Create a new layer and name it `ghost`. Fill this layer with white.

![Healing test](img/retouching_11.png)

Create a clipping mask quickly by holding `option/alt` and clicking between the `ghost` and `cat` layers. 

![Healing test](img/retouching_12.png)

Right click on the layer and select `Blending options`. 

![Healing test](img/retouching_13.png)

Change the blending mode of the layer to `Overlay`. 

![Healing test](img/retouching_14.png)

Lets add a glow to the cat to add more ghostliness. Click the `Outer glow` menu item to the left. Move the `Spread` and `Size` sliders to get a sizeable glow on the cat.  

![Healing test](img/retouching_15.png)

We can see that the cat looks a little too angelic. Instead, we wan't to create a more demure ghost such like the one here:

![ghost](http://images4.fanpop.com/image/quiz/649000/649656_1311171483888_319_240.jpg)

Let's remove the color from the cat by adding a `Hue/saturation` adjustment layer. 

![Healing test](img/retouching_16.png)
![Healing test](img/retouching_17.png)

Done!

![Healing test](img/retouching_18.png)

======

[< Home](README.md)

[4. Color and brushes >](4_colorandbrushes.md)