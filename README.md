# ContainsDuplicate

Problem Approach

In order to solve this problem in a time and space efficient manner I will use a set/hashset to add the elements of the list as I go along it.
For each element I will check if its the set and if it isnt add it to the list. This will cause it to leave on encounting a non unique element.
By adding in standard checking of the list at the start I ensure some edge cases in which the list is empty or null.
