# Tic Tac Toe Part 1 Guiding Questions

![img](./img01.png)

## Review all of the code in the assignment before proceeding

<details><summary>Calculate x, y for each row, col</summary>

<details><summary>Does x depend on row or col?</summary>

> Since columns are vertical, changing columns moves us side-to-side.  The x-value depends on which column we are in.

<details><summary>What are the values that col is going to be?</summary>

> Since `col` gets its value in the `for` loop on line 10, `col` will get values `0`, `1`, and `2`.

<details><summary>What are the corresponding x-values?</summary>

> Inspecting the picture shows that the x-values of the cells are `0`, `133`, and `267`.

<details><summary>x doesn't appear to be changing by a constant amount...what's going on?</summary>

> Since the canvas is 400 pixels wide and we want 3 equally sized cells, the width of each cell is `400 / 3`.  There is a variable on line 8, `cellSize` containing that value.

<details><summary>So what is x?</summary>

> `x = col * cellSize`
</details>
</details>
</details>
</details>
</details>

<details><summary>Does y depend on row or col?</summary>

> Since rows are horizontal, channgin rows moves us up and down.  The y-value depends on which row we are in.

<details><summary>What are the values that row is going to be?</summary>

> Since `row` gets its value in the `for` loop on line 10, `row` will get values `0`, `1`, and `2`.

<details><summary>What are the corresponding y-values?</summary>

> Inspecting the picture shows that the y-values of the cells are `0`, `133`, and `267`.

<details><summary>y doesn't appear to be changing by a constant amount...what's going on?</summary>

> Since the canvas is 400 pixels wide and we want 3 equally sized cells, the width of each cell is `400 / 3`.  There is a variable on line 8, `cellSize` containing that value.

<details><summary>So what is y?</summary>

> `y = row * cellSize`
</details>
</details>
</details>
</details>
</details>
</details>

<details><summary>and add a rectangle to the board group.</summary>

<details><summary>Where should the rectangle go?</summary>

> The top left of each rectangle should go in the `x` and `y` that we just calculated.
</details>

<details><summary>What should the width and height be?</summary>

> Since the cells are squares, the width and height should both be `cellSize`.
</details>

<details><summary>What other properties need to be set?</summary>

> `border`, `fill`, and `borderWidth` should be set based on inspecting the picture.
</details>

<details><summary>What else are you forgetting?</summary>

> The rectangle needs to be added to the board group using `board.add()`
</details>
</details>
<br></br>
<details><summary>Calculate the center of each cell</summary>

<details><summary>What does the hint say?</summary>

> The hint says, "Add `cellSize / 2` to `x` to get the center of the cell.

<details><summary>So, what do you do?</summary>

> Create a local variable called `centerOfCell` and assign its value using the hint.
</details>
</details>
</details>

<details><summary>and add a label there.</summary>

<details><summary>What are the required parts of a label?</summary>

> `text`, `centerX`, `centerY`

<details><summary>What should you use for each?</summary>

> Use an empty string for the text `''`
> Use `centerOfCell` for both `centerX` and `centerY`
</details>
</details>
</details>


<details><summary>Also assign the label into app.board</summary>

<details><summary>What is app.board?</summary>

> `app.board` is a 2D list.

<details><summary>How do we assign things to 2D lists?</summary>

> Using `app.board[row][col] = label`

<details><summary>Why doesn't that work?</summary>

> `label` isn't a thing yet.  You need to create the local variable `label` and assign it the `Label` you created in the previous step.

> `label = Label('', centerOfCell, centerOfCell)`
</details>
</details>
</details>
</details>

<details><summary>and add it to the board Group.</summary>

<details><summary>What is "it"?</summary>

> It is the label that you created in the previous step.  Add it to the group `board` using `board.add()`
</details>
</details>