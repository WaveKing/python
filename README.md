# calculator with while loop

#first_value = input("Please enter first value") # collect value
#float_value1 = float(first_value) # convert to float

#second_value = input("Please enter second value")
#float_value2 = float(second_value) # convert to float

#operator= input("Please enter one operator[+, -, *, /, %, ]")

#start = True
#while start: # infinite
    #vclculator code
    #if operator == "+":
    #    result = float_value1 + float_value2
     #   print(result)
      #  break
    #if operator == "-":
    #    result = float_value1 + float_value2
    #    print(result)
     #   break
    #if operator == "*":
    #    result = float_value1 + float_value2
    #    print(result)
    #    break
    #if operator == "/":
    #    result = float_value1 + float_value2
     #   print(result)
     #   break
    #if operator == "%":
    #    result = float_value1 + float_value2
    #    print(result)
    #    break

# using for loop on a dictionary {key : value}
example_dict = {1: "goggle", 2: "Microsoft", 3:"Oracle",4:"Facebook" }
for item in example_dict:
    print(item)
    print(example_dict[item])

for item in example_dict:
    #print(item + "key an the value"+value) # prints only the keys will cause an error
    print(f"The item is {item} and its {example_dict[item]}")# using the string format for interpolation
    










