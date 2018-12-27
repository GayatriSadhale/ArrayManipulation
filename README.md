# ArrayManipulation
Creating basic functionality of Array in Java like following:

1) union([array1],[array2])
Creates an array of unique value
union([2],[1,2]);
// => [2, 1]

2) compact(array1, array2)
Creates an array with all falsely values removed.The values  null, 0, "", undefined, and NaN are falsey.
compact([0, 1, 2, 3]);
// => [1, 2, 3]
compact(“A”,”0”,null,”NaN”,”B”,”null”);
//=>[“A”,”B”]

3) concat(array1, array2)
Creates a new array concatenating two arrays to one array
concat([1,2,3,4],[5,6,7])
// => [1,2,3,4,5,6,7]

4) difference(array1, array2)
Creates an array of array values not included in the other given arrays
difference([2, 1], [2, 3]);
// => [1]

5) drop(array, [n=1])
Creates a slice of array with n elements dropped from the beginning.
drop([1, 2, 3]);
// => [2, 3]
drop([1, 2, 3], 2);
// => [3]
drop([1, 2, 3], 5);
// => []
 drop([1, 2, 3], 0);
// => [1, 2, 3]

6) dropRight(array, [n=1])
Creates a slice of array with n elements dropped from the end.
dropRight([1, 2, 3]);
// => [1, 2]
 dropRight([1, 2, 3], 2);
// => [1] 
dropRight([1, 2, 3], 5);
// => []
dropRight([1, 2, 3], 0);
// => [1, 2, 3]

7) dropLeft(array, [n=1])
Creates a slice of array with n elements dropped from the end.
dropLeft([1, 2, 3]);
// => [2, 3]
dropLeft ([1, 2, 3], 2);
// => [3]
dropLeft ([1, 2, 3], 5);
// => []
dropLeft ([1, 2, 3], 0);
// => [1, 2, 3]

8) uniq(array)
Creates a duplicate-free version of an array
uniq([2, 1, 2]);
// => [2, 1]

10) Prime number
Identity prime numbers from given array
prime([4,5,6,7,8]);
//=>[5,7]

11) Odd and Even
Identity Odd and even numbers from given array
odd([4,5,6,7,8]);
//=>[5,7]
even([4,5,6,7,8]);
//=>[4,6,8]

12) Max min Numer
Identity max-min numbers from given array
min([4,5,6,7,8,3,10]);
//=>3

13) Divisible
Create an array which is divisible by given number 
divisibleBy([4,5,6,7,8,12],4);
//=>[4,8,12]

