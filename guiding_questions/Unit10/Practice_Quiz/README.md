# Unit 10 Practice Quiz Guiding Questions

![getTotal() code](./img1.png)


### Read the comments on lines 15 & 16 before proceeding
  
<details>
  
  <summary>What is "the list"?</summary>
    
  > `app.prices`
 
</details>

<details>
  <summary>How do you add up all of the values in the list?</summary>
  
  > 1. You need to create a local variable to hold the sum. Maybe call it `sum` and set it to `0`.  
  > 2. Loop through the list (see the previous question if you aren't sure what list) and add each price in the list to the sum.
  
  </details>

<details>
  <summary>How do you return a value?</summary>
  
 > Use the keyword `return` followed by the thing you want to return

</details>

<details>
  <summary>What needs to be returned here?</summary>
  
> `sum * 1.08`
</details>

<details>
  <summary>Should the return statement be inside of the loop or outside?</summary>

> outside
</details>

![drawList() code](./img2.png)
### Read the comments on lines 23 & 24 before proceeding

<details><summary>How do you get the total amount spent?</summary>
  
  > Call the helper function `getTotal` and store its return value in a variable.  Maybe call the variable `total`.
  
  <details><summary>How do you store the return value in a variable?</summary>
    
  > `total = getTotal()`
  
  </details>

</details>



<details><summary>What is the prices list?</summary>
  
> `app.prices`
</details>

<details><summary>How do you store something in a list?</summary>
  
> `listName.append(thingToStore)`
  
  </details>
  
<details><summary>How do you store the total amount in the prices list?</summary>
  
> Assuming you created the local variable, `total`, `app.prices.append(total)`
  
</details>

### Read the comments on lines 27 & 28 before proceeding

<details><summary>What are the prices on the screen?</summary>
  
> Labels
</details>

<details><summary>What properties of the prices are changing?</summary>
  
> 1. `value`
> 2. `centerY`

<details><summary>Where is `value` coming from?</summary>
  
> `app.prices`
</details>

<details><summary>Where is `centerY` coming from?</summary>
  
> It starts at 130 and goes up by 40 each time
</details>

<details><summary>How can we get the `value` and the `centerY` in a single loop?</summary>
  
 > * Use `for i in range(len(app.prices))`.  
 > * Inside the loop create a Label setting its `value` to `app.prices[i]` and its `centerY` to `130+40*i` (set everything else by inspecting the solution).
</details>
</details>

<details><summary>Run your program.  How is it different from the solution?</summary>
  
> We're missing the $ in front of the price.
</details>

<details><summary>How do we fix that?</summary>
  
> One way would be to make a local variable before creating the label, call it `price`.  
> * Set the value of price to `'$' + str(app.prices[i])`
> * Change the value of the label to `price` (no quotes)

 </details>
  
  
### If you followed my directions, you should have added 4 lines in getTotal(), and 5 lines in drawList() (in 2 separate sections).

### If it still doesn't work, go back through the guiding questions slowly and make sure you didn't skip anything. Read carefully.

  

  

  

  
  




  