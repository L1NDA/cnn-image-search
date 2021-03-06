# Image Search

## Find your photos that are most similar

Reusing the activation layer of VGG 16, which was already trained on imagenet,
I ran a database of my images through the CNN, using VGG as a feature extractor,
and then implemented the nearest neighbor algorithm to find the images
that were most similar to the one submitted

#### Example 1
![Sample 1](static/1.png)

#### Example 2
![Sample 2](static/2.png)

#### Example 3
![Sample 3](static/3.png)

#### Example 4
![Sample 4](static/4.png)

#### Example 5
![Sample 5](static/5.png)
The second and third nearest neighbor of this photo is not as similar, but it is
super interesting how the feature extractor from VGG was able to still find
similarities through the lights and the clothing patterns in the 3rd NN

#### Example 6
![Sample 6](static/6.png)
This one had a much greater distance to its second and third nearest neighbor,
as you can tell from the images. The model is far from perfect, but potential
next steps are to try a more complex CNN, whether that be with architecture or
the specific types of images it was trained on, as well as creating a larger database
of images (this one only had ~500).

---

### Special Thanks To

[The TAVTech Fellowship](http://taventure.org/)

[Gil Levi](https://gilscvblog.com/); AI instructor
