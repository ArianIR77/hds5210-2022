# Notes on the Midterm

* _Correctness    (out of 40):_ 39
* _Good Practices (out of 10):_ 8
* _Docs / Testing (out of 10):_ 10

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

Good use of docstrings and tests throughout. Great solutions (except for Part 4). Please review my notes on that.

## Step 1
* Nice work. No comments.

## Step 2
* I appreciate how you loaded everything up into a simplified dictionary, but it wasn't necessary. You could have just done the test for the billing code and service code you're looking for inside the loops and terminated early, when you found the match.
* I don't see where your code returns None in the case that a match is not found. It looks to me that it will return 0 instead. I've deducted 1 point from _Correctness_ for missing that.

## Step 3
* Nice work. No comments.

## Step 4
* Your hardcoding of all the month and hospital name buckets is not an acceptable solution. Instead, your code can simply test if a dictionary element is there based on the hospital / month, insert the item if it isn't there, or update the item if it is there. We've done that pattern before, but you can also see it in my solution in the recording. I've deducted 2 points from _Good Practices_ for this.