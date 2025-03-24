# sort-list-number
user enter number and sort it to ascending orders
def get_numbers():
    numbers = input("Enter numbers separated by spaces: ")
    return [float(num) for num in numbers.split()]

def sort_numbers(num_list):
    num_list.sort()
    return num_list

def display_numbers(sorted_list):
    print("Sorted numbers:", sorted_list)


