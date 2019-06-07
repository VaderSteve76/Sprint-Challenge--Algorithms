Add your answers to the Algorithms exercises here.

A. 0(n) O(n) This is linear time because the loop will run n number of times while a is less than n^3

B. O(n^3) Runs n^3 number of times because the first 3 loops run n number of times. They are nested so they get mulitplied together. We ignore the last loop after we simplify the runtime because it runs a constant amount of times.

C. O(n) The runtime is linear because the function will run as many times as the input it is given.

Exercise II

    The function takes in the amount of floors (n) and makes an array.

    The array is already sorted because it is made by looping from index 0 to n - 1.

    Then I will divide the array by the floors that eggs will break on.

    Example, if eggs break at the 4th floor, I would have floor 1-3 in a sub array and floors 4-n in another sub array.

    I would then say if the egg was dropped off of the first array(1-3) breaking the egg equals false.

    If the egg was dropped off of the second array, breaking the egg equals true.

    If the egg was not broken when it dropped, I could eliminate one entire sub array of potential floors.

    After eliminating one subarray, I would keep dividing the remaining array again and check each side until I find what floor(f) the egg was dropped from.
