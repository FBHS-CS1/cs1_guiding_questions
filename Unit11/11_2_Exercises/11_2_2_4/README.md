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

> While it is initially unclear, we can use it to determine 
</details>
</details>