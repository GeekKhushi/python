# python
#create a program for prime numbers
#taking input

lowest_value = int(input ("Please, Enter the Lowest Range Value: "))  
highest_value = int(input ("Please, Enter the highest Range Value: "))  
  
print ("The Prime Numbers in the range are: ")  
for number in range (lowest_value , highest_value + 1):  
    if number > 1:  
        for i in range (2, number):  
            if (number % i) == 0:  
                break  
        else:  
            print (number)  
            
