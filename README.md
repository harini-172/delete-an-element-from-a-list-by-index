# delete-an-element-from-a-list-by-index
numbers = [3, 4, 1, 9, 6, 2, 8]
print("Original list:", numbers)

x = int(input("Enter the position of the element to be deleted: "))

numbers.pop(x)
print("Updated list:", numbers)
output
Original list: [3, 4, 1, 9, 6, 2, 8]
Updated list: [3, 4, 1, 6, 2, 8]
