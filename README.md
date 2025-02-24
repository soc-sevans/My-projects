# Age next year 
 #Introduction 
print('Kia Ora') 
print("What's your name?") 
#name input
name = input("what's your name ")
print("hello " + name) 
#age input 
age = input("how old are you ")
#next year
next_year = int(age) + 1
print("This time next year you will be")
print(next_year)

## Celcius -> Fahrenheit 

 (0°C × 9/5) + 32 = 32°F
 (0°C × 1.8) + 32 = 32°F
 (10°C × 1.8) + 32 = 18 + 32 
 10°C = 50°F

#input a temp
celsius = int(input('Enter a temp in Celsius: '))

#convert
fahrenheit = celsius*9/5 + 32

#tell user
print(fahrenheit, 'Fahrenheit')
elif celsius<= 17:
  print("thats not very warm")
elif celsius<= 25:
  print("ooh thats nice")
  elif celsius<=32:
  print("keep hydrated")
else : print ("run")

## Pocket money shares 

#input the amount of money 
pocket_money = float(input("how much money?"))

#input the amount of people
number_people = int(input("how many people are sharing?"))

print(pocket_money / number_people)
