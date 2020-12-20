# RTS-Labs-Coding-Exercise

README file for the coding exercise given by RTS labs. It involves two coding problems with one short answer question. Both coding problems were answered using Python and a file for each is attached. Below is the pasted problems, code, and written response. 

#1  Print the number of integers in an array that are above the given input and the number that are below, e.g. for the array [1, 5, 2, 1, 10] with input 6, print “above: 1, below: 4”.

def aboveBelow(arr, num):
	above = 0
	below = 0
	for i in range(len(arr)):
		if arr[i] == num:
			continue
		elif arr[i] > num:
			above += 1
		else:
			below += 1
	return print(“above: {}, below: {}”.format(above, below) )

#2  Rotate the characters in a string by a given input and have the overflow appear at the beginning, e.g. “MyString” rotated by 2 is “ngMyStri”.

def rotate(s, num):
	s = list(s)
	num = num % len(s)
	temp = s[-num:]
	str[-num:] = s[0:num]
	s[0:num] = temp
	return “”.join(s)

#3  If you could change 1 thing about your favorite framework/language/platform (pick one), what would it be?

I have had a lot of positive experiences with the python programming language, from the diverse array of free downloadable software to easy to learn syntax and coding conventions. One drawback from all of the available software is the nonstop compatibility problems python users run into. If I could change one thing about python, it would be to add some sort of universal updater that can automatically update old versions of python software to be compatible with newer versions of python. This would help speed up the collaboration of rapidly improving technologies such as deep learning and artificial intelligence since so many of these softwares and scripts are written in python or similar languages like MatLab.


