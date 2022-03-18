# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (floor){
  if (floor <= 0){
    return floor
  }

  let offset = 1
  if (floor >= 13){
    offset = 2
  }

  return floor - offset
}
```

| Input | Output |
| ----- | ------ |
|   0   |    0   | 
|   1   |    0   | 
|   15  |    13  | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>The function takes a number as the floor value, if that number is 0 or below it will output that number, if it is greated than 0 and less than 12
    then it outputs the number less 1, if the input number is 13 or higher it will output the number less 2.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
