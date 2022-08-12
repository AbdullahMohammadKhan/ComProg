# ComProg

## Dictionary

#### How does a python dictionary look like ?
```python
myCat = {
    'size': 'fat',
    'color': 'gray',
    'disposition': 'loud'
}
```

Answer 1
```python

```

#### How to declare a python dictionary ?
```python
my_dict = {}  # empty dictionary
my_dict = {1: 'Python', 2: 'Java'}  # dictionary with elements
```
Answer 1

#### How to add a new element ?
```python
my_dict = {'First': 'Python', 'Second': 'Java'}
my_dict['Third'] = 'Ruby'  # adding key-value pair
```
Adding items with setdefault()
It’s possible to add an item to a dictionary in this way:
```python
>>> wife = {'name': 'Rose', 'age': 33}
>>> if 'has_hair' not in wife:
...     wife['has_hair'] = True
```
Using the setdefault method we can make the same code more short:
```python
>>> wife = {'name': 'Rose', 'age': 33}
>>> wife.setdefault('has_hair', True)
>>> wife
# {'name': 'Rose', 'age': 33, 'has_hair': True}
```
#### How update an element ?
```python
my_dict = {'First': 'Python', 'Second': 'Java'}
my_dict['Second'] = 'C++'  # changing element
```
Answer 1

#### How to delete an item from the dictionary ?
```python
my_dict = {'First': 'Python', 'Second': 'Java', 'Third': 'Ruby'}
a = my_dict.pop('Third')  # pop element
```
pop method returns the **VALUE** of the deleted item.
```python
my_dict = {'First': 'Python', 'Second': 'Java', 'Third': 'Ruby'}
b = my_dict.popitem()  # pop the key-value pair
my_dict.clear()  # empty dictionary
print('n', my_dict)
```
popitem retrun the **key, value** tupple. # ('Second', 'Java')

#### How to clear empty dictionary ?
```python
my_dict = {'First': 'Python', 'Second': 'Java', 'Third': 'Ruby'}
my_dict.clear()  # empty dictionary
```

#### How to access dictionary elements ?
```python
my_dict = {'First': 'Python', 'Second': 'Java'}
print(my_dict['First'])  # access elements using keys
print(my_dict.get('Second'))
```
But if the key doesn't exist, then python throw will an error. How to avoid this error ? By using get method.
The get() method returns the value of an item with by using the key. If the key doesn’t exist, it returns None:
```python
print(my_dict.get('Second'))
```
More examples:
```python
>>> wife = {'name': 'Rose', 'age': 33}

>>> f'My wife name is {wife.get("name")}'
# 'My wife name is Rose'

>>> f'She is {wife.get("age")} years old.'
# 'She is 33 years old.'

>>> f'She is deeply in love with {wife.get("husband")}'
# 'She is deeply in love with None'
```
You can also change the default None value for other of your choice:
```python
>>> wife = {'name': 'Rose', 'age': 33}

>>> f'She is deeply in love with {wife.get("husband", "lover")}'
# 'She is deeply in love with lover'
```

#### How does a python dictionary look like ?
```python

```
Answer 1
#### How does a python dictionary look like ?
```python

```
Answer 1

#### How does a python dictionary look like ?
```python

```
Answer 1

#### How does a python dictionary look like ?
```python

```
Answer 1

#### How does a python dictionary look like ?
```python

```
Answer 1

#### Question 2

Answer 2

```python
var add2 = function(number) {
  return number + 2;
}
```

How to access an array element ?
https://leetcode.com/problems/build-array-from-permutation/
TODO:: https://leetcode.com/problems/build-array-from-permutation/discuss/?currentPage=1&orderBy=most_votes&query=

How to add two arrays ?
https://leetcode.com/problems/concatenation-of-array/submissions/
TODO:: https://leetcode.com/problems/concatenation-of-array/discuss/1330138/Python-One-Line-Straight-Forward-Solution

How to do cumulative sum with an array ?
https://leetcode.com/problems/running-sum-of-1d-array
TODO:: https://leetcode.com/problems/running-sum-of-1d-array/discuss/

+= -= in python:
https://leetcode.com/problems/final-value-of-variable-after-performing-operations/
https://leetcode.com/problems/final-value-of-variable-after-performing-operations/discuss/


2D array, indexing at it's best, max() function for two values:
https://leetcode.com/problems/richest-customer-wealth/
https://leetcode.com/problems/maximum-number-of-words-found-in-sentences/
https://leetcode.com/problems/maximum-number-of-words-found-in-sentences/discuss/
https://leetcode.com/problems/richest-customer-wealth/discuss/?currentPage=1&orderBy=most_votes&query=


index play, append()
https://leetcode.com/problems/shuffle-the-array/

range function:
https://leetcode.com/problems/number-of-good-pairs/
https://www.w3schools.com/python/ref_func_range.asp
https://leetcode.com/problems/number-of-good-pairs/discuss/


max for list: https://www.tutorialspoint.com/python/list_max.htm
https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/
boolean value for python: starts with T and F 
https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/discuss/


