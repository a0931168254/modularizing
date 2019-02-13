# modularizing
模組化成績計算並判斷是否在範圍內
# -*- coding: UTF-8 -*-


def main():
    while True:
        score = eval(raw_input("enter a number between 0 to 100 :"))
        if 0 <= score:
            if score <=100:
                    print "the grade is :", printGrade(score)
            else:
                print"your number is not in the range"
        else:
            print"GG"
            exit()

        
def printGrade(score):

    if score >= 90:
        return  'A'    
    elif score >= 80:
        return  'B'
    elif score >= 70:
        return  'C'
    elif score >= 60:
        return  'D'
    else:
        return  'F'
main()





    
    

    


