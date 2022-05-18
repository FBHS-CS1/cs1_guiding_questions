# Tic Tac Toe Part 3 Guiding Questions

![part1](img01.png)

## Review all of the code before proceeding

<details><summary>Return a list of all values in the column.</summary>

<details><summary>What does the hint say?</summary>

> Append the element at `col` for each row in the board.

<details><summary>Append the element to what?</summary>

> The only thing that makes sense is `colList`
</details>

<details><summary>How dow we get the element at col for each row?</summary>

> The parameter `board` must be a 2D list of **Labels**.  We can use a for loop:

    for row in range(len(board)):
        colList.append(board[row][col].value)

</details>
</details>
</details>

---

![part2](./img02.png)

## Review all code before proceeding

<details><summary>What does checkWin do?</summary>

> It will return `True` if there is a winner, and `False` otherwise.

<details><summary>What is colRowOrDiag?</summary>

> It is a list with exactly 3 values in it.
</details>

<details><summary>What is the purpose of the count variable?</summary>

> While it is initially unclear, we can use it to determine how many of the items in `colRowOrDiag` are the same as `app.player`

<details><summary>How could you do that?</summary>

> Use a for loop going through each item in `colRowOrDiag` and if it is the same as `app.player` add one to `count`

<details><summary>What do you do with that?</summary>

> After the loop finishes, if `count` is 3, then all 3 values in `colRowOrDiag` must have been the same as `app.player`, so return `True`.  If `count` isn't 3, then at least one of the values must not have been the same, so return `False`
</details>
</details>
</details>
</details>