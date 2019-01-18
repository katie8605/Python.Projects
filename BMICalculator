#Author: Katie Chen
#Completed: 01/21/2018

z = False
while z == False:
    system = input("Please pick one (metric system/english system): ")
    x = False
    y = False
    if system == "metric system":
        z = True
        while x == False:
            try:
                weightM = float(input("Please enter your weight(kg): "))
                if weightM < 0 or weightM == 0:
                    print('Please enter a valiid number')
                else:
                    while y == False:
                        try:
                            heightM = float(input("Please enter your height(m): "))
                            if heightM < 0 or heightM == 0:
                                print('Please enter a valiid number')
                            else:
                                bmiM = weightM / heightM**2
                                bmiRounded = round(bmiM, 2)
                                if bmiRounded <= 24.99:
                                   print('Your BMI is', bmiRounded, "and your BMI category is normal")
                                   y = True
                                   x = True
                                elif 25 <= bmiRounded <= 29.99:
                                    print('Your BMI is', bmiRounded, 'and your BMI category is overweight')
                                    y = True
                                    x = True
                                elif 30 <= bmiRounded <= 39.99:
                                    print ('Your BMI is', bmiRounded, 'and your BMI category is obsese')
                                    y = True
                                    x = True
                                elif bmiRounded >= 40:
                                    print ('Your BMI is', bmiRounded, 'and your BMI category is extreme obesity')
                                    y = True
                                    x = True
                                else:
                                    print ('Your BMI is', bmiRounded, 'and your BMI category is underweight')
                                    y = True
                                    x = True
                        except:
                            print('Plese enter a valid number')
             
            except:
                print('Plese enter a valid number')
    elif system == "english system":
        z = True
        while x == False:
            try:
                weightE = float(input("Please enter your weight(lb): "))
                if weightE < 0 or weightE == 0:
                    print('Please enter a valiid number')
                else:
                    while y == False:
                        try:
                            heightE = float(input("Please enter your height(in): "))
                            if heightE < 0 or heightE == 0:
                                print('Please enter a valiid number')
                            else:
                                bmiE = (weightE / heightE**2) * 703
                                bmiRounded = round(bmiE, 2)
                                if bmiRounded <= 24.99:
                                   print('Your BMI is', bmiRounded, "and your BMI category is normal")
                                   y = True
                                   x = True
                                elif 25 <= bmiRounded <= 29.99:
                                    print('Your BMI is', bmiRounded, 'and your BMI category is overweight')
                                    y = True
                                    x = True
                                elif 30 <= bmiRounded <= 39.99:
                                    print ('Your BMI is', bmiRounded, 'and your BMI category is obsese')
                                    y = True
                                    x = True
                                elif bmiRounded >= 40:
                                    print ('Your BMI is', bmiRounded, 'and your BMI category is extreme obesity')
                                    y = True
                                    x = True
                                else:
                                    print ('Your BMI is', bmiRounded, 'and your BMI category is underweight')
                                    y = True
                                    x = True
                        except:
                            print('Plese enter a valid number')
            except:
                print('Plese enter a valid number')
    else:
        print('Plese enter metric system or english system')

'''
Test #1: English system, normal BMI
Please pick one (metric system/english system): english system
Please enter your weight(lb): 108
Please enter your height(in): 60
Your BMI is 21.09 and your BMI category is normal

Test #2: English, overweight
Please pick one (metric system/english system): english system
Please enter your weight(lb): 145
Please enter your height(in): 61
Your BMI is 27.39 and your BMI category is overweight

Test #3: English, obese
Please pick one (metric system/english system): english system
Please enter your weight(lb): 200.23
Please enter your height(in): 63
Your BMI is 35.47 and your BMI category is obsese

Test #4: English, extreme obesity
Please pick one (metric system/english system): english system
Please enter your weight(lb): 286.54
Please enter your height(in): 60
Your BMI is 55.95 and your BMI category is extreme obesity

Test #5: Metric, normal
Please enter your weight(kg): 48.6
Please enter your height(m): 1.54
Your BMI is 20.49 and your BMI category is normal

Test #6: Metric, overweight
Please pick one (metric system/english system): metric system
Please enter your weight(kg): 60.54
Please enter your height(m): 1.53
Your BMI is 25.86 and your BMI category is overweight

Test #7: Metric, obese
Please pick one (metric system/english system): metric system
Please enter your weight(kg): 100.45
Please enter your height(m): 1.72
Your BMI is 33.95 and your BMI category is obsese

Test #8: Metric, extreme obesity
Please pick one (metric system/english system): metric system
Please enter your weight(kg): 121.16
Please enter your height(m): 1.58
Your BMI is 48.53 and your BMI category is extreme obesity

Test #9: Error due to wrong data format
Please pick one (metric system/english system): metric system
Please enter your weight(kg): fourty one
Plese enter a valid number
Please enter your weight(kg): 41
Please enter your height(m): one point six one
Plese enter a valid number
Please enter your height(m): 1.61
Your BMI is 15.82 and your BMI category is normal

Test #10: Error due to wrong data values
Please pick one (metric system/english system): english system
Please enter your weight(lb): -105.4
Please enter a valiid number
Please enter your weight(lb): 105.4
Please enter your height(in): -61
Please enter a valiid number
Please enter your height(in): 61
Your BMI is 19.91 and your BMI category is normal

Test #11: Error due to wrong user choice
Please pick one (metric system/english system): i dont know
Plese enter metric system or english system
Please pick one (metric system/english system): system
Plese enter metric system or english system
Please pick one (metric system/english system): metric system
Please enter your weight(kg): 65.4
Please enter your height(m): 1.53
Your BMI is 27.94 and your BMI category is overweight

Test #12: Error due to wrong data values
Please pick one (metric system/english system): metric system
Please enter your weight(kg): -343432
Please enter a valiid number
Please enter your weight(kg): 0
Please enter a valiid number
Please enter your weight(kg): 78
Please enter your height(m): 0
Please enter a valiid number
Please enter your height(m): 1.78
Your BMI is 24.62 and your BMI category is normal
'''
