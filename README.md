# Image Search

## Find your photos that are most similar

Reusing the activation layer of VGG 16, which was already trained on imagenet,
I ran a database of my images through the CNN, using VGG as a feature extractor,
and then implemented the nearest neighbor algorithm to find the images
that were most similar to the one submitted

### A couple examples
![Sample 1](static/1.png)

![Sample 2](static/2.png)

![Sample 3](static/3.png)

![Sample 4](static/4.png)

![Sample 5](static/5.png)
The second and third nearest neighbor of this photo is not as similar, but it is
super interesting how the feature extractor from VGG was able to still find
similarities through the lights and the clothing patterns in the 3rd NN

!(static/6.png)

---

### Special Thanks To

The TAVTech Fellowship

Gil Levi; AI instructor
