# python_ch1
my first assignment
# This program asks the user to input a value(interger) and calculates the the input squared and cubed. Next, the user inserts a second input, and the program add both inputs, then multiply them.

userNum = int(input('Enter integer:\n'))

print('You entered:', userNum)
userSquared = userNum * userNum
print(userNum, 'squared is',userSquared)
userCubed = userNum * userNum * userNum
print('And',userNum,'cubed is',userCubed,'!!')
userNum2 = int(input('Enter another integer:\n'))

userSome = userNum + userNum2
print(userNum,'+',userNum2,'is',userSome)
userMult = userNum * userNum2
print(userNum,'*',userNum2,'is',userMult)
