# Grade-claculater-python
Simple grade calculator code for python 


Your_marks = ("Input your number")
Marks = [0, 10 , 20 , 30 , 40 , 50 , 60 , 70 , 80 , 90]

if Your_marks > Marks[0] and Your_marks <= Marks[1]:
	print("You got E grade")
elif Your_marks >= Marks[1] and Your_marks <= Marks[2]:
	print("You got D grade")
elif Your_marks >= Marks[2] and Your_marks <= Marks[3]:
	print("You got D + grade")
elif Your_marks >= Marks[3] and Your_marks <= Marks[4]:
	print("You got C grade")
elif Your_marks >= Marks[4] and Your_marks <= Marks[5]:
	print("You got C + grade")
elif Your_marks >= Marks[5] and Your_marks <= Marks[6]:
	print("You got B grade")
elif Your_marks >= Marks[6] and Your_marks <= Marks[7]:
	print("You got B + grade")
elif Your_marks >= Marks[7] and Your_marks <= Marks[8]:
	print("You got  A grade")
elif Your_marks >= Marks[8] and Your_marks <= Marks[9]:
	print("You got A + grade")
elif Your_marks == 100:
	print("You got full marks")
elif Your_marks == 0:
	print("better luck next time")
elif Your_marks > 100:
	print("wrong input")
else:
	print("You got A ++")


