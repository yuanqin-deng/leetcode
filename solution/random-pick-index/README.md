## 398. Random Pick Index

<p>Given an array of integers with possible duplicates, randomly output the index of a given target number. You can assume that the given target number must exist in the array.</p>

<p><b>Note:</b><br />
The array size can be very large. Solution that uses too much extra space will not pass the judge.</p>

<p><b>Example:</b></p>

<pre>
int[] nums = new int[] {1,2,3,3,3};
Solution solution = new Solution(nums);

// pick(3) should return either index 2, 3, or 4 randomly. Each index should have equal probability of returning.
solution.pick(3);

// pick(1) should return 0. Since in the array only nums[0] is equal to 1.
solution.pick(1);
</pre>


### Similar Questions
  1. [Linked List Random Node](https://github.com/openset/leetcode/tree/master/solution/linked-list-random-node)(Medium)
  1. [Random Pick with Blacklist](https://github.com/openset/leetcode/tree/master/solution/random-pick-with-blacklist)(Hard)
  1. [Random Pick with Weight](https://github.com/openset/leetcode/tree/master/solution/random-pick-with-weight)(Medium)