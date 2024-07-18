# Number of Good Leaf Nodes Pairs

LeetCode Q # 1530.

You are given the root of a binary tree and an integer distance. A pair of two different leaf nodes of a binary tree is said to be good if the length of the shortest path between them is less than or equal to distance.

Return the number of good leaf node pairs in the tree.

Example 1:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/f55b1813-3d93-45d0-8032-1d4874253b9c)

</div>

> Input: root = [1,2,3,null,4], distance = 3</br>
> Output: 1</br>
> Explanation: The leaf nodes of the tree are 3 and 4 and the length of the shortest path between them is 3. This is the only good pair.

Example 2:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/2dd72545-1faa-46e9-9c82-ba30ff16a37d)

</div>

> Input: root = [1,2,3,4,5,6,7], distance = 3</br>
> Output: 2</br>
> Explanation: The good pairs are [4,5] and [6,7] with shortest path = 2. The pair [4,6] is not good because the length of ther shortest path between them is 4.

Example 3:

> Input: root = [7,1,4,6,null,5,3,null,null,null,null,null,2], distance = 3</br>
> Output: 1</br>
> Explanation: The only good pair is [2,5].

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/user-attachments/assets/68ccb840-8244-493f-8e54-3e77fb6d0372)

  Time complexity: O(n).</br>Space complexity: O(1).
</div>
