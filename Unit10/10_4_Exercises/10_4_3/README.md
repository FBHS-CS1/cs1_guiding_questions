# 10.4.3 Word Cloud Guiding Questions

![countWord() code](./img1.png)
## Review the code above before proceeding
<details><summary>What does this function do?</summary>

> It counts the number of times a target word appears in a paragraph.

</details>

<details><summary>What does the comment on line 13 say to do?</summary>

> "Return count"

<details><summary>How do you do that?</summary>

> You return a value using the word `return` followed by the value/variable you want to return.  In this case the function is supposed to return the value of `count`.

> Make sure to return *outside* of the loop.

</details>
</details>

---

![loop code](./img2.png)
## Review the code above before proceeding

<details><summary>According to the comments on line 21-23, what variables are you going to be giving values to?</summary>

> `size`, `color`, `angle`, `x`, `y`

<details><summary>Where in the code will you be giving them values?</summary>

> On lines 25, 26, 27, 28, 29

</summary>
</details>

<details><summary>What should the size be?</summary>

> According to the comment on line 21, the size should be "10 + 2 times the word count"


</summary>

<details><summary>How do you get the word count?</summary>

> Use the helper function `countWord` that you finished above.

<details><summary>What are the parameters of wordCount and where do you get their values?</summary>

> The parameters are `paragraph` and `targetword` (see line 5).  The variable `text` should be passed in for `paragraph`, and `word` for `targetword`.  

</details>

<details><summary>How do you call wordCount?</summary>

> `countWord(text, word)`

</details>

<details><summary>What variable should you assign the result to?</summary>

> `size`
</details>
</details>
</details>

<details><summary>What should color be?</summary>

> According to the comment on line 21, color is random.

<details><summary>How do you get a random thing out of a list?</summary>

> Use the `choice` function. `choice(listName)` returns a random item from a list called `listName`.

</details>
</details>

<details><summary>What should angle be?</summary>

> 0, 90, or 270, apparently at random

<details><summary>How could you get that angle value?</summary>

> There are a few ways, but one way would be to use `choice` again, but put the list containing the values 0, 90, and 270 as the argument. That is, instead of `choice(listName)` you can put `choice([0, 90, 270])`.

</details>
</details>

<details><summary>What should x and y be?</summary>

> Random values between 50 and 350 inclusive.  Review `randrange` if you aren't sure how to do this.

</details>
</details>

---
### FAQs
<details><summary>My program works, but the text is super small.  What did I do wrong?</summary>

> You probably forgot that the size is supposed to be 10 + 2 times wordcount, not just wordcount.

</details>




