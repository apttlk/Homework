

# Homework: Introduction to Python

## Exercise 1-a: Print "Hello World!" by typing it inside print() function.
print(Hello World!)

## Exercise 1-b: Assign "Hello World!" to the variable my_text
my_text = "Hello World!"
print(my_text)

## Exercise 2-a: Assign 3 to variable glass of water
glass_of_water = 3
print("I drank", glass_of_water, "glasses of water today.")

## Exercise 2-b: Place the variable: glass_of_water inside the print function
glass_of_water = 3
glass_of_water = glass_of_water + 1 # overwrites existing variable
print(glass_of_water) # new output: 4

## Exercise 3-a: Assign an integer to the variable
men_stepped_on_the_moon = 12
print(men_stepped_on_the_moon)

## Exercise 3-b: String example
my_reason_for_coding = "My PhD thesis."
print(my_reason_for_coding)

## Exercise 3-c: Assign a float with 2 decimals to the variable
global_mean_sea_level_2018 = 21
global_mean_sea_level_2018 = 21.36
print(global_sea_level_2018)

## Exercise 9-a: Assign the string below to the variable
str = "It's always darkest before dawn."
print(str)

## Exercise 9-b: By using first, second and last characters of the string, create a new string
str = "It's always darkest before dawn."
ans_1 = str[0] + str[1] + str[-1]
print(ans_1) # output: It.

## Exercise 9-c: Replace the (.) with (!)
str = str.replace(".", "!")
print(str)

## Exercise 10-a: Using len() function to find out how many items are in the list
lst = [11, 10, 12, 101, 99, 1000, 999]
answer_1 = len(lst)
print(answer_1)

## Exercise 10-b: Find out the length of the string given below
msg = "Be yourself, everyone else is taken."
msg_length = len(msg)
print(msg_length)

## Exercise 10-c: How many keys are there in the dictionary?
dict = {"Real Madrid": 13,"AC Milan": 7,"Bayern Munich":5 ,"Barcelona": 5, "Liverpool": 5}
ans_1 = len(dict)
print(ans_1)

## Exercise 11-a: Sort the list in ascending order
lst = [11, 100, 99, 1000, 999]
lst.sort()
print(lst)

## Exercise 11-b: Sort the countries in alphabetic order
lst = ["Ukraine", "Japan", "Canada", "Kazakhstan", "Taiwan", "India", "Belize"]
lst.sort()
print(lst)

## Exercise 11-c: Sort the list in descending order
lst = [11, 100, 101, 999, 1001]
lst.sort(reverse = True)
print(lst)

## Exercise 12-a: Pop the last item of the list below
lst = [11, 100, 99, 1000, 999]
popped_item = lst.pop()
print(popped_item)
print(lst)

## Exercise 12-b: Remove "broccoli" from the list using .pop and .index methods
lst = ["milk", "banana", "eggs", "bread", "broccoli", "lemons"]
lst.index("broccoli") # get the index number of "broccoli"
item = lst.pop(4) # remove "broccoli" from list
print(lst, item)

## Exercise 12-c: Save Italy's GDP in a separate variable and remove it from the dictionary
GDP_2018 = {"US": 21, "China": 16, "Japan": 5, "Germany": 4, "India": 3, "France": 3, "UK": 3, "Italy": 2}
italy_gdp = GDP_2018.pop("Italy")
print(GDP_2018)
print(italy_gdp, "trillion USD")

