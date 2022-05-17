# Tic Tac Toe Part 2 Guiding Questions

![part1](./img01.png)

## Review all of the code before proceeding

<details><summary>What is the purpose of the isValidMove function?</summary>

> It needs to check if app.board already has something in the given `row` and `col` parameters.  

> If we look at line 90, we can see that `isValidMove` is called as part of an `if` statement, which means it needs to return either `True` (if it's a valid move) or `False` (if it's not a valid move).

<details><summary>How would we know if a move is valid?</summary>

> A move would be  valid if the label at the indicated `row` and `column` has an empty string.

<details><summary>How do we check that?</summary>

> `app.board[row][col]` is a `Label`.  Check its `value` property to see if it's an empty string (`''`).  

> If it is an empty string, return `True`, otherwise return `False`
</details>
</details>
</details>
</details>

---

![part2](./img02.png)

## Review all of the code before proceeding

<details><summary>What is the purpose of the makeMove function></summary>

> To put an X or O (depending on `app.player`) into the board.

<details><summary>Set the value at row, col to app.player</summary>

<details><summary>Set the value at row, col in what?</summary>

> The only thing that makes sense is the 2D list: `app.board`

<details><summary>How do we set the value in app.board at row, col?</summary>

> Since `app.board` is a 2D list of **labels**, you need to set `app.board[row][col].value` to `app.player`.
</details>
</details>
</details>

<details><summary>and set the color depending on if the player is 'X' or 'O'</summary>

<details><summary>How do we do something depending on if...?</summary>

> Use an `if` statement!

<details><summary>If what?</summary>

> If `app.player` is `X` the fill of the label should be `white`, otherwise it should be something else (inspect!)

<details><summary>What label?</summary>

> Since `app.board` is a 2D list of **labels**, the label at `app.board[row][col]`
</details>
</details>
</details>
</details>
</details>
