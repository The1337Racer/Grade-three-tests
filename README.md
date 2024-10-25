# Grade-three-tests
A_score = 90
B_score = 80
C_score = 70
D_score = 60


#User enters score of three tests
coursework1 = float(input('Enter your score for coursework1: '))
coursework2 = float(input('Enter your score for coursework2: '))
coursework3 = float(input('Enter your score for coursework3: '))

#The average of the three parts of coursework
average = (coursework1 + coursework2 + coursework3) / 3

#print the average
print('The average score is', average)


#Get the test average score from the user
score = float(input('Enter your test score: '))
                    
#The user grade
if score >= A_score:
        print('Your grade is A.')
elif score >= B_score:
        print('Your grade is B.')
elif score >= C_score:
        print('Your grade is C.')
elif score >= D_score:
        print('Your grade is D.')
else:
    print('Your grade is F.')

