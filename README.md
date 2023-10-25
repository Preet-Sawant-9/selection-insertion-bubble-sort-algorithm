# selection-insertion-bubble-sort-algorithm
A Sorting Algorithm is used to rearrange a given array or list of elements according to a comparison operator on the elements. The comparison operator is used to decide the new order of elements in the respective data structure.

![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/ee8c9c0d-d6fb-41d8-bf34-e804224a3af5)


Selection Sort
In selection sorting technique, the smallest element is fetched by comparing itself with the rest of the elements and sorted at the array's first position. The complete array is divided into two halves, the sorted subarray on the left and the unsorted subarray on the right. Once the first element is sorted, the search for the second minimum element begins from the rest of the array and is positioned at second place.

![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/5b99caef-da54-4242-b5de-8517371f7188)
![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/64e05842-5003-482f-94d9-ee4273afe2d1)


Similarly, all the elements are positioned on the sorted side of the subarray one after the other, and the complete array becomes a sorted array.

Insertion Sort
In this sorting technique, the elements are sorted by comparing the elements with their previous elements. It starts by comparing the second element with the first element. If the second element is smaller than the first, then we will swap it.

![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/4ee84c23-4040-41b9-94b1-9faee1839ec3)


After that, we will compare the third element with all the elements that are before it. Similarly, it goes for the fourth element and so on. Once all the comparisons are made, the elements become sorted.

Bubble Sort
Bubble sort is one of the most straightforward sorting algorithms. In this sorting technique, we begin by comparing the first two elements of the array and checking if the first element is greater than the second element; if it is, we will swap those elements and move forward to the next element.

![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/40bac782-22d5-4765-bc39-eeeb9593d563)


If the first element is not greater than the second, then we don’t need to swap it. And this process will keep on repeating till the end of the array.

![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/d3e43c33-9eac-465d-a37f-39e8fca98653)


ALGORITHM
Here's the algorithm for the provided C++ program that sorts an array using Selection Sort, Insertion Sort, or Bubble Sort based on user input:

1.Start

2.Declare an integer variable n to store the number of elements in the array.

Output "Enter the number of elements in the array: " to prompt the user for input.

Read the value of n from the user.

3.Declare an integer array arr of size n to store the elements of the array.

Output "Enter n elements of the array: " to prompt the user for the array elements.

Use a loop to read and store the n elements in the arr array.

4.Declare an integer variable choice to store the user's choice of sorting algorithm.

Output "Choose a sorting algorithm:".

Output "1. Selection Sort".

Output "2. Insertion Sort".

Output "3. Bubble Sort".

Output "Enter your choice: " to prompt the user for their choice.

5.Read the value of choice from the user.

6.Use a switch statement to perform the selected sorting algorithm based on the value of choice:

a. If choice is 1, call the selectionSort(arr, n) function to perform Selection Sort.

b. If choice is 2, call the insertionSort(arr, n) function to perform Insertion Sort.

c. If choice is 3, call the bubbleSort(arr, n) function to perform Bubble Sort.

d. If choice is none of the above, output "Invalid choice" and return 1 to exit the program.

Output "Sorted array: " to indicate the sorted array.

7.Use a loop to display the elements of the sorted arr array.

8.End

The program provides the user with a menu to choose a sorting algorithm and then displays the sorted array using the selected sorting technique.

OUTPUT
![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/a542b6e7-395a-42f0-b75a-cb4bbaab6a1c)


![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/3c3f3f24-a925-4ff3-ba61-e653ae5af88b)


![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/cf378813-37c0-4869-be57-d74b1c44343c)


![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/3a6b65cd-8338-4870-9171-96f272d6152f)
![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/1569ecb8-2096-4577-a2cc-d1315d1cd56e)
![image](https://github.com/Preet-Sawant-9/selection-insertion-bubble-sort-algorithm/assets/130697042/2478f0d1-af2e-4275-91a0-7461dff26392)


