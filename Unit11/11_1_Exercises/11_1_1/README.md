# 11.1.3.1 Animate Polygons Guiding Questions

![code](./img1.png)

## Review all of the code before proceeding.

<details><summary>Use the index to get an inner list from app.points</summary>
<details><summary>What is "the index"?</summary>

> The variable `index` on line 16
</details>

<details><summary>What does an "inner list" in app.points represent?</summary>

> A single point (coordinate)
</details>

<details><summary>What is app.points?</summary>

> `app.points` is a 2D list with 5 rows and 2 columns
</details>

<details><summary>How do you get an inner list from app.points?</summary>

> Use `listName[i]` to get an item out of a list at index `i`
</details>

<details><summary>What should you do with the inner list?</summary>

> Store it in a variable, maybe called `point`

<details><summary>How do you store it?</summary>

> `point = app.points[index]`
</details>
</details>
</details>

<details><summary>Set the 0th value of that inner list to mouseX</summary>

<details><summary>What is "that inner list"?</summary>

> You should have named it `point` if you followed the previous set of questions

</details>

<details><summary>How do you "set the 0th" value?</summary>

> Use `L[i] = n` to set the ith value of the list `L` to `n`

</details>

</details>

<details><summary>Set the 1st value of the inner list to mouseY</summary>

> Read the previous questions

</details>

<details><summary>Also draw a dot</summary>

<details><summary>What shape are the dots?  What properties do you need to set?</summary>

> Run the solution and click the screen and examine the dots to figure out what shape they are and the properties to set.

</details>
</details>

<details><summary>Update the value of pointsAdded</summary>

<details><summary>What is pointsAdded?</summary>

> `pointsAdded` is a label that holds the number of points that have been added.

</details>

<details><summary>How many points did you add?</summary>

> We clicked once, adding 1 point.  So we need to increase `pointsAdded.value` by 1.
</details>
</details>

