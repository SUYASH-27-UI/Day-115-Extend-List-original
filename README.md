# Day-115-Extend-List-original
# Python Day 115 - Extend List

## Description

This program demonstrates how to use the `extend()` method in Python.

The `extend()` method is used to add multiple elements to the end of an existing list.

## Example

```text
Original list: [10, 20, 30]
Updated list: [10, 20, 30, 40, 50, 60]
```

## Code

```python
numbers = [10, 20, 30]

print("Original list:", numbers)

numbers.extend([40, 50, 60])

print("Updated list:", numbers)
```

## Concepts Used

* Lists
* `extend()` method
* `print()`
* Adding multiple elements

## How It Works

1. A list named `numbers` is created.
2. The `extend()` method is used to add `[40, 50, 60]`.
3. All three elements are added to the end of the list.
4. The updated list is displayed.

## append() vs extend()

```text
append()  → Adds one element
extend()  → Adds multiple elements
```

## File Name

`extend_list.py`

## Goal

The goal of this program is to understand how the `extend()` method can be used to add multiple elements to a Python list.
