# Notes on the Midterm

* _Correctness    (out of 40):_ 39
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 10

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

You consistently open and load the JSON data BEFORE your function definition and then use that variable. The instructions were to open the file and read it WITHIN the function. You also hardcoded the file name instead of using the `file` parameter. I deducted 1 point form _Correctness_ for this.

## Step 1
* No additional comments.

## Step 2
* Rather than `if key not in dictionary: continue`, the more typical style is to say `if key in dictionary` and indent the code that follows.

## Step 3
For the couple of items on this step, I deducted 1 point from _Good Practices_
* You should have reused the `get_rate` function from above rather than copying / pasting the code into this new function.
* The use of mixed variable naming styles (capital A in `Amount` whereas no other variables use a leading capital letter)


## Step 4
* Nice work. No additional comments.