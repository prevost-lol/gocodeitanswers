=================|Gocodeit Answers|================
- ts so ez, only use if ur genuinely stuck


-IMPORTANT(TO AVOID GETTING CAUGHT)!!!

copy and paste the script into chatgpt or deepseek or copilot or etc and then copy and paste the following prompt:

can you change the variable names into something else that's still relevant to the program but doesn't change it's function at all. And do not add any comments



#-------------------------->∼<--------------------------#
>>>>>>>>>>>>>>>>>>>>>>>>>>Unit-1<<<<<<<<<<<<<<<<<<<<<<<<<
#-------------------------->∼<--------------------------#

=========================================================

First Calculation

width = int(input("Enter the width: "))
height = int(input("Enter the height: "))
depth = int(input("Enter the depth: "))
area = width * height
print("The volume is:",area * depth)

=========================================================
=========================================================

Cone Volume

# Program to calculate the volume of a cone
PI = 3.141 # Create a constant for the value of PI
radius = int(input("Enter the radius: "))
height = int(input("Enter the height: "))
radiusSquared = radius ** 2
volume = PI * radiusSquared * (height/3)
print("The volume of the cone is:", volume)

=========================================================
=========================================================

Asterisk

print("*")
print("**")
print("***")
print("****")
print("*****")

=========================================================
=========================================================

Heading

name = input("Please enter your name")
print("Hello", name)

Simple Concatenation

name1 = input("Please enter your first name")
name2 = input("Please enter your surname")

print("Hello" , name1 , name2)

=========================================================
=========================================================

First Calculator

num1 = int(input("Enter the first number"))
num2 = int(input("Enter the second number"))

mul = num1*num2
add = num1+num2
print("Multiplied =" ,mul)
print("Added =" , add)

=========================================================
=========================================================

Area of rectangle

width = int(input("Enter the width"))
height = int(input("Enter the height"))

print("The area is" , width*height)

=========================================================
=========================================================

Missing Angle

width = int(input("Enter the width"))
height = int(input("Enter the height"))

print("The area is" , width*height)

=========================================================
=========================================================

More Concatenation

hobby = input("Please enter your hobby")
film = input("Please enter your favourite film")
colour = input("Please enter your favourite colour")

print("Your hobby is" , hobby)
print("Your favourite film is" , film)
print("Your favourite colour is" , colour)

=========================================================
=========================================================

Average Speed

miles = int(input("Enter the number of miles"))
hours = int(input("Enter the number of hours"))

speed = float(miles / hours)
print("The average speed was" , speed,"mph")

=========================================================
=========================================================

Goal Difference

home_team = input("Please enter the home team name")
away_team = input("Please enter the away team name")

home_goals = int(input(f"Please enter the goals scored by {home_team}"))

away_goals = int(input(f"Please enter the goals scored by {away_team}"))

diff = home_goals - away_goals
print("The goal difference is",diff)

=========================================================
=========================================================

Tax Man

cost = int(input("Please enter the cost of the item"))
VAT = int(input("Please enter the VAT percentage"))
VAT = VAT / 100
tot = VAT * cost
tot = int(tot)
print("The VAT was","£" + str(tot))

=========================================================
=========================================================

Tiler's Problem

area_r = int(input("Enter the area of the room"))
area_t = int(input("Enter the area of one tile"))
area = int(area_r / area_t)
print("Tiles needed is", area)

=========================================================
=========================================================


Area of a Cube

height  = int(input("Enter the height of the cube"))
width = int(input("Enter the width of the cube"))
depth = int(input("Enter the depth of the cube"))

volume = height *  depth * width

print("The volume of the cube is", volume)

=========================================================
=========================================================

Test Marks

t1 = int(input("Enter test mark 1"))
t2 = int(input("Enter test mark 2"))
t3 = int(input("Enter test mark 3"))

avg = t1 + t2 + t3
avg = int(avg / 3)
print("The average mark was", avg)

=========================================================
=========================================================

Temperature Converter

temp = int(input("Enter the temperature in Fahrenheit"))
v1 = temp - 32
v2 = v1 * (5/9)
print("The temperature in Centigrade is", int(v2))

=========================================================
=========================================================

#-------------------------->∼<--------------------------#
>>>>>>>>>>>>>>>>>>>>>>>>>>Unit-2<<<<<<<<<<<<<<<<<<<<<<<<<
#-------------------------->∼<--------------------------#
=========================================================

Introducing Selection Using 'if'

num1=int(input("Please enter a number"))
num2=int(input("Please enter another number"))
if num1>num2:
    print("The largest number is",num1)
elif num1<num2:
    print("The largest number is",num2)
else:
    print("Both numbers are equal")

=========================================================
=========================================================

The Bowler

choice=input("Do you have your own bowling shoes?")
if choice == "YES":
    print("You can bowl")
else:
    print("You cannot bowl")

=========================================================
=========================================================

Cake Recipe

eggs=int(input("Please enter the number of eggs"))
flour=int(input("Please enter the amount of flour in grams"))
milk=int(input("Please enter the amount of milk in ml"))
if eggs>=3 and flour>=200 and milk>=100:
    print("You have enough to bake")
else:
    print("You do not have enough to bake")

=========================================================
=========================================================

Test Scores

test=int(input("Please enter your test score"))
if test > 100:
    print("MERIT")
elif test > 50:
    print("PASS")
else:
    print("FAIL")

=========================================================
=========================================================

The Fairground Worker

spin = int(input("Please enter the number of spins per minute"))
if spin in range(0,11):
    print("This ride is boring")
elif spin in range(11,31):
    print("We want to go faster")
elif spin in range(31,51):
    print("WOOHOO")
else:
    print("I might be sick")

=========================================================
=========================================================

The Hustler

roll1=int(input("Please enter roll 1: "))
roll2=int(input("Please enter roll 2: "))
roll3=int(input("Please enter roll 3: "))
if roll1 == roll2 and roll2 == roll3:
    print("Your score was", roll1 + roll2 + roll3)
elif roll1 == roll2:
    print("Your score was", roll1 + roll2)
elif roll1 == roll3:
    print("Your score was", roll1 + roll3)
elif roll2 == roll3:
    print("Your score was", roll2 + roll3)
else:
    print("Your score was 0")

=========================================================

#-------------------------->∼<--------------------------#
>>>>>>>>>>>>>>>>>>>>>>>>>>Unit-3<<<<<<<<<<<<<<<<<<<<<<<<<
#-------------------------->∼<--------------------------#
=========================================================

Counter

counted=int(input("Please enter number to count to"))
for i in range (1,counted+1):
    print(i)

Introducing Definite/Fixed Loops Using For

for i in range (1,11):
    print(i)

=========================================================
=========================================================

Return of the Fairground Worker

loled=int(input("Please enter the number of loops"))
for i in range(loled):
    print("Let me off")

=========================================================
=========================================================

Times Tables

ttse=int(input("Please enter the times table"))
for i in range(1,13):
    print(i*ttse)

=========================================================
=========================================================

All The Squares

x=int(input("Please enter a number"))
for i in range(1,x+1):
    print(i**2)

=========================================================
=========================================================

Average Numbers

count = int(input("How many numbers?"))
tempvarA = 0
for i in range(1, count + 1):
    enp = int(input(f"Enter number {i}: "))
    tempvarA += enp
print(f"Average is {tempvarA / count}")

=========================================================
=========================================================

Running Totals

count = int(input("How many numbers?"))
tempvarA = 0
for i in range(1, count + 1):
    enp = int(input(f"Enter number {i}: "))
    tempvarA += enp
print(f"Total is {tempvarA}")

=========================================================
=========================================================

Highest Number

count = int(input("How many numbers?"))
tempvarA = 0
for i in range(1, count + 1):
    enp = int(input(f"Enter number {i}: "))
    if enp > tempvarA:
        tempvarA = enp
print(f"Highest number was {tempvarA}")

=========================================================
=========================================================

The Hustler Returns

scoreTotal = 0
for roundNum in range(3):
    diceA = int(input("Enter dice A: "))
    diceB = int(input("Enter dice B: "))
    diceC = int(input("Enter dice C: "))
    if diceA == diceB and diceA == diceC:
        scoreTotal += diceA * 3
    elif diceA == diceB:
        scoreTotal += diceA + diceB
    elif diceA == diceC:
        scoreTotal += diceA + diceC
    elif diceB == diceC:
        scoreTotal += diceB + diceC
if scoreTotal >= 30:
    print("Total was", scoreTotal)
    print("Winner")
else:
    print("Total was", scoreTotal)
    print("Loser")

=========================================================
=========================================================

Thinking Positive

sumResult = 0
for entryNum in range(1, 6):
    userVal = int(input(f"Enter number {entryNum}: "))
    if userVal > 0:
        print("Added")
        sumResult += userVal
    else:
        print("Not Added")
print("Total was", sumResult)

=========================================================
=========================================================
#-------------------------->∼<--------------------------#
>>>>>>>>>>>>>>>>>>>>>>>>>>Unit-4<<<<<<<<<<<<<<<<<<<<<<<<<
#-------------------------->∼<--------------------------#
=========================================================

Introducing Indefinite/Conditional Loops

while True:
    ue = int(input("Please enter a number between 1 and 100"))
    if ue in range(1,101):
        break

=========================================================
=========================================================

Simple Password Check

while True:
    pass = input("Please enter your password")
    if len(pass) > 8:
        break

=========================================================
=========================================================

The Chef's Ingredients

while True:
    batter = int(input("Please enter batter amount"))
    if batter > 300:
        break

=========================================================
=========================================================

Valid Word

while True:
    checko = input("Please enter yes")
    if checko == "yes":
        break

=========================================================
=========================================================

Output the Letters

word = input("Please enter a word")
for letter in word:
    print(letter)

=========================================================
=========================================================

Reversi the Wordi!

word = input("Please enter a word")
for letter in word[::-1]:
    print(letter)

=========================================================
=========================================================

Teacher's Test Score Calculator

testCount = int(input("How many test results? "))
scoreSum = 0
remainingTests = testCount

while remainingTests > 0:
    testScore = int(input("Enter test score (0-100): "))
    if testScore in range(0, 101):
        scoreSum += testScore
        remainingTests -= 1

print("Number of tests was", testCount)
print("Total score was", scoreSum)
average = scoreSum / testCount
print("Average score was", average)

=========================================================
=========================================================

A Better Password Check

resultStatus = "FAILED"

for attemptNum in range(3):
    userPassword = input("Please enter your password: ")
    hasCapital = False

    for char in userPassword:
        if char.isupper():
            hasCapital = True
            break

    if len(userPassword) > 8 and ('!' in userPassword or '@' in userPassword) and hasCapital:
        resultStatus = "PASSED"
        break

print(resultStatus)

=========================================================
=========================================================

The Chef is Back!

while True:
    numEggs = int(input("Enter number of eggs: "))
    milkAmount = int(input("Enter amount of milk (ml): "))
    flourAmount = int(input("Enter amount of flour (g): "))
 
    if numEggs >= 3 and milkAmount in range(50, 201) and flourAmount in range(300, 401):
        break
    print("INVALID INGREDIENTS")

print("READY TO BAKE!")

=========================================================
#-------------------------->∼<--------------------------#
>>>>>>>>>>>>>>>>>>>>>>>>>>Unit-5<<<<<<<<<<<<<<<<<<<<<<<<<
#-------------------------->∼<--------------------------#
=========================================================

Upper or Lower

input_phrase = input("Please enter the word or phrase")
case_selection = input("UPPER or LOWER?")

if case_selection == "UPPER":
    print(input_phrase.upper())
else:
    print(input_phrase.lower())

=========================================================
=========================================================

How Long is a String?

word = input("Please enter a word or phrase")

print(f"{word} has {len(word)} characters.")

=========================================================
=========================================================

Take a Piece of String

original_string = input("Please enter the word or phrase")
start_index = int(input("Please enter the start index"))
end_index = int(input("Please enter the end index"))
print(original_string[start_index:end_index])

=========================================================
=========================================================

Looking for someth'ing'?

input_word = input("Please enter a word")
processed_word = input_word.lower()
if processed_word[-3:] == "ing":
    print("TRUE")
else:
    print("FALSE")

=========================================================
=========================================================

Speaking In Code

sentence = input("Enter sentence")
for letter in sentence:
    print(ord(letter))

=========================================================
=========================================================

String Length

user_word = input("Please enter a word")
word_length = len(user_word)
if word_length in range(5, 8):
    print("VALID")
else:
    print("NOT VALID")

=========================================================
=========================================================

What's There?

user_input_word = input("Please enter a word")
index_position = int(input("Please enter a position"))
try:
    if index_position > -1:
        print(user_input_word[index_position])
    else:
        print("NOT VALID")
except:
    print("NOT VALID")

=========================================================
=========================================================

Any Space?

user_sentence = input("Please enter a sentence")
space_count = 0
for character in user_sentence:
    if character == " ":
        space_count += 1
print(f"Spaces = {space_count}")

=========================================================
=========================================================

Palindrome

input_string = input("Please enter a word")
current_index = -1
reversed_string = ""
for character in input_string:
    reversed_string += input_string[current_index]
    current_index -= 1
if reversed_string == input_string:
    print("is a palindrome")
else:
    print("Not a palindrome")

=========================================================
=========================================================

The Longest Word

first_word = input("Enter word 1")
second_word = input("Enter word 2")
third_word = input("Enter word 3")
fourth_word = input("Enter word 4")

length_first = len(first_word)
length_second = len(second_word)
length_third = len(third_word)
length_fourth = len(fourth_word)

if length_first > length_second and length_first > length_third and length_first > length_fourth:
    print(f"{first_word} is the longest word")
elif length_second > length_first and length_second > length_third and length_second > length_fourth:
    print(f"{second_word} is the longest word")
elif length_third > length_first and length_third > length_second and length_third > length_fourth:
    print(f"{third_word} is the longest word")
elif length_fourth > length_first and length_fourth > length_second and length_fourth > length_third:
    print(f"{fourth_word} is the longest word")

=========================================================
=========================================================

Don't Be Silly

while True:
    word1 = input("Enter first 9-letter word: ")
    if len(word1) == 9:
        break
while True:
    word2 = input("Enter second 9-letter word: ")
    if len(word2) == 9:
        break
while True:
    word3 = input("Enter third 9-letter word: ")
    if len(word3) == 9:
        break
print(word1[0:3] + word2[3:6] + word3[6:])

=========================================================
=========================================================

Code Breaker

sentence = input("Enter sentence")
shift = int(input("Enter shift amount"))
new_word = ""
for char in sentence:

    
    if ord(char) + shift > 90:
        overflow = 90 - (ord(char) + shift)
        new_word += chr(65 + abs(overflow) - 1)
    else:
        new_word += chr(ord(char) + shift)
print(new_word)

=========================================================
#-------------------------->∼<--------------------------#
>>>>>>>>>>>>>>>>>>>>>>>>>>Unit-6<<<<<<<<<<<<<<<<<<<<<<<<<
#-------------------------->∼<--------------------------#
=========================================================

Believe Me

first_number = int(input("Enter first number"))
second_number = int(input("Enter second number"))

if first_number % second_number == 0:
    print("TRUE")
else:
    print("FALSE")

=========================================================
=========================================================

Counting the Divisions

while True:
    user_number = int(input("Enter number (1-10): "))
    if user_number in range(1, 11):
        break

count_multiples = 0
for current_num in range(1, 1001):
    if current_num % user_number == 0:
        count_multiples += 1

print(count_multiples, "numbers")

=========================================================
=========================================================

Introducing MOD and DIV

first_value = int(input("Enter first number"))
second_value = int(input("Enter second number"))
print(f"{first_value // second_value} remainder {first_value % second_value}")

=========================================================
=========================================================

The Sweet Tooth

total_sweets = int(input("Please enter the number of sweets"))
number_of_people = int(input("Please enter the number of people"))
print(f"Each person will get {total_sweets // number_of_people} sweets each")
print(f"There will be {total_sweets % number_of_people} sweets left over")

=========================================================
=========================================================
Converting Correctly

centimeters_input = int(input("Enter centimetres"))
print(f"That is {centimeters_input // 100} metres and {centimeters_input % 100} centimetres")

=========================================================
