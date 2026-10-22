# Task 3 - Loops for Dataset Processing

## Objective

Learn how to use `for` and `while` loops to process datasets and
calculate summary statistics.

## Tools

-   Python
-   Jupyter Notebook

## Program 1: For Loop

``` python
for i in range(5):
    print(i)
```

## Program 2: While Loop

``` python
i = 1
while i <= 5:
    print(i)
    i += 1
```

## Program 3: Process a List

``` python
numbers = [10,20,30,40,50]
for num in numbers:
    print(num)
```

## Program 4: Calculate Total

``` python
numbers = [10,20,30,40,50]
total = 0
for num in numbers:
    total += num
print("Total =", total)
```

## Program 5: Calculate Average

``` python
numbers = [10,20,30,40,50]
total = 0
for num in numbers:
    total += num
average = total / len(numbers)
print("Average =", average)
```

## Program 6: Find Maximum

``` python
numbers = [10,20,30,40,50]
largest = numbers[0]
for num in numbers:
    if num > largest:
        largest = num
print("Largest =", largest)
```

## Program 7: Find Minimum

``` python
numbers = [10,20,30,40,50]
smallest = numbers[0]
for num in numbers:
    if num < smallest:
        smallest = num
print("Smallest =", smallest)
```

## Key Concepts

-   `for` loop: Used when iterations are known.
-   `while` loop: Used until a condition becomes false.
-   `range()`: Generates a sequence of numbers.
-   Loops help process datasets efficiently.

## Conclusion

This task demonstrated how to use loops to iterate through datasets,
calculate totals, averages, maximum and minimum values, and understand
the basics of dataset processing in Python.

> "Success comes from consistent practice, one loop at a time."
# task3
