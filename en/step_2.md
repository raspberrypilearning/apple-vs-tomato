## Test an existing model

### Follow our video guide

<iframe width="640" height="360" src="https://www.youtube.com/embed/XXXXXXXXXXXXX?rel=0&cc_load_policy=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

--- collapse ---
---
title: I cannot access YouTube
---

<video width="640" height="360" controls>
  <source src="images/dance-detector-part1.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>

--- /collapse ---

### Follow our step-by-step guide

--- task ---

Open the [starter project](https://teachablemachine.withgoogle.com/train/image/1ebW5aMmz4W3IdsLdswRfg8eS0HvfEMM-)

--- /task ---

--- task ---

Allow Google Drive permissions.

--- /task ---

The starter project contains two classes:
- The 'Apple' class contains images of **green** apples.
- The 'Tomato' class contains images of **red** tomatoes.

--- task ---

Train the model.

--- /task ---

--- task ---

Test the model by holding up a **green** apple to your webcam.

The model should make a **confident** prediction that it is an apple.

--- /task ---

--- task ---

Test the model by holding up a red **tomato** to your webcam.

The model should make a **confident** prediction that it is a tomato.

--- /task ---

--- task ---

Test the model by holding up a **red** apple to your webcam.

The model should **not** make a confident prediction that it is an apple.

--- /task ---

The training data is biased, as it only trained on green apples.

In the next step, you will improve your model by adding examples of other coloured apples to the training data used for the 'Apple' class.

--- collapse ---
---
title: Note to educators
---

If appropriate, you may choose to introduce learners to the concept of the ethical bias that can result from the use of biased training data.

--- /collapse ---

- Can use data in test folder if no actual apple or tomato.
