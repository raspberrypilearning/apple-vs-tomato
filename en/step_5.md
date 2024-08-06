## Improve the model

<html>
  <div style="position: relative; overflow: hidden; padding-top: 56.25%;">
    <iframe style="position: absolute; top: 0; left: 0; right: 0; width: 100%; height: 100%; border: none;" src="https://www.youtube.com/embed/s-UoG3US_Jg?rel=0&cc_load_policy=1" allowfullscreen allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"></iframe>
  </div>
</html>

--- collapse ---
---
title: I cannot access YouTube
---

<video width="640" height="360" controls>
  <source src="images/XXXXXXXXXXX.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

--- /collapse ---

The training data is biased, as it only includes green apples.

To reduce the bias, you need to add extra examples of apples to the 'Apple' class.

--- task ---

Download a [folder of more images of apples](https://drive.google.com/drive/folders/1OIuoG7go72c7QririIpykJ4tW-arrtfA){:target="_blank"}.

--- /task ---

--- task ---

Unzip the new folder.

--- /task ---

--- task ---

In the 'Apple' class, add some samples of images from one of the folders you have just downloaded.

Choose images that look most like your **red** apple.

**Tip:** You can also use your webcam to take images of your red apple.

**Tip:** You only need to add a few extra samples to your 'Apple' class.

--- /task ---

### Train the model again

--- task ---

Click on **Train Model**.

![The 'Train Model' button.](images/train_model.png)

--- /task ---

When the model is trained, the preview panel will open.

--- task ---

Hold up your **red** apple to your webcam to test the model again.

The model should produce a prediction with a **higher confidence score** that it is an **apple**.
 
--- /task ---

--- task ---

Hold up your tomato to your webcam.

The model might produce a prediction with a **lower confidence score** that it is a **tomato**.

This is because you have added training data to the 'Apple' class of images that look more like tomatoes.

--- /task ---

--- collapse ---
---
title: Note to educators
---

You may choose to introduce learners to the concept of the ethical bias that can result from the use of biased training data.

--- /collapse ---
