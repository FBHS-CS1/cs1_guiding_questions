# 11.1.3.1 Color Blocks

![part 1 comments](./img1.png)

## Review all of the code before proceeding

<details><summary>Create a rectangle with the correct blue value...</summary>

<details><summary>What is "the correct blue value?"</summary>

> The value in the variable `blue`

</details>

<details><summary>What property of the block needs to change?</summary>

> The blue part of the rgb in the `fill` property should be `blue`

</details>
</details>

<details><summary>and store it in the list.</summary>

<details><summary>What needs to be stored in the list?</summary>

> The `block` needs to go in the list.

</details>

<details><summary>What list?</summary>

> `app.board`

</details>

<details><summary>Where in the list?</summary>

> `app.board[row][col]`
</details>

</details>

---


![part 2 comments](./img2.png)

## Review all of the code before proceeding

<details><summary>If the block was clicked, set the selectedRow and selectedCol</summary>

<details><summary>How do you check if the block was clicked?</summary>

> Use `if block.hits(x, y):`
</details>

<details><summary>What does it mean "selectedRow" and "selectedCol"?</summary>

> It's referring to the global variables, `app.selectedRow` and `app.selectedCol`.

</details>

<details><summary>What do they need to be set to?</summary>

> `app.selectedRow` should be set to `row` and `app.selectedCol` should be set to `col`

</details>
</details>

<details><summary>and return the block</summary>

<details><summary>What block?</summary>

> The variable `block` from line 36.  
> Use the `return` keyword to return it from the function.  
> Double check your indentation (it should be indented inside of the `if` statement)
</details>
</details>

---

## If it still doesn't pass the tests...
<details><summary>Read the error in the console, what does it say?</summary>

> `AttributeError: 'Shape' object has not attribute 'blue'`

<details><summary>What does that mean?</summary>

> On line 26 it is trying to access the property `blue` of a block, but a `block` doesnt' have a `blue` property.

<details><summary>What do we do about that?</summary>

> Give `block` a property called `blue` on line 19 
> Insert a line `block.blue = blue`
</details>
</details>
</details>