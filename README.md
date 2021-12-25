# __list__
str_1 = []
str_1 = [1, 9, -99, 34, -5, 0]
str_1.reverse()
print(str_1)
str_1.append("Patserkovskyi")
print(str_1)
str_1.pop()
print(str_1)
str_1.remove(1)
print(str_1)
str_1.sort()
print(str_1)
str_1.insert(3, 1)
print(str_1)
print(len(str_1))

# __dict__
dict_1 = {}
dict_1["Misha"] =  1999
print(dict_1)
dict_1.clear()
print(dict_1)
dict_1 = dict(Misha = 1999, Dasha = 2001)
print(dict_1.items())
print(dict_1.keys())
print(dict_1.values())
dict_1.popitem()
print(dict_1)
dict_2 = dict(London = "victory")
dict_1.update(dict_2)
print(dict_1)

# __str__
str_1 = "Kiev", "Lviv", "Rivne"
print(type(str_1)) #tuple
str_list = list(str_1)
print(str_list)
a = "How"
b = "old"
c = "you"
x = "{0} {1} are {2}?".format(a, b, c)
print(x)
print(len(x))
print(x.isdigit()) #number
print(x.isalpha()) #letter
print(x.upper())
print(x.lower())

