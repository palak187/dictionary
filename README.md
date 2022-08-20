test_dict = { 'gfg' : 10, 'is' : 15, 'best' : 20, 'for' : 10, 'geeks' : 20}
print("The original dictionary is : " + str(test_dict))
temp = {val : key for key, val in test_dict.items()}
res = {val : key for key, val in temp.items()}
print("The dictionary after values removal : " + str(res))
