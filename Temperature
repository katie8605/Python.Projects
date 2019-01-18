#Author: Katie Chen
#Completed: 02/27/2018


def initList (inFile):
    g = ''
    value = []
    try:
        file = open(inFile, "r")
        '''
        for line in file:
            print(line)
        file.close()
        '''
        for line in file:
            for word in line.split():
                value.append(float(word))
           
        file.close()
       
    except:
        return False

    for i in range (len(value)) :
        g += str(value[i]) + "\n"
    return g    



def getSize (aList):
    value = []
    h = aList.split()
    for word in h:
        value.append(float(word))
    return len(value)
       
def getHighest(aList):
    value = []
    h = aList.split()
    for word in h:
        value.append(float(word))
        
    maxNumber = 0
    for i in range(len(value)) :
        if maxNumber < value[i]:
            maxNumber = value[i]
    return maxNumber

def getLowest (aList):
    value = []
    h = aList.split()
    for word in h:
        value.append(float(word))
    minNumber = value[1]
    
    for i in range(len(value)) :
        if minNumber > value[i]:
            minNumber = value[i]
    return minNumber

def getAverage(aList):
    value = []
    h = aList.split()
    for word in h:
        value.append(float(word))

    sum = 0
    for i in range(len(value)) :
         sum += value[i]
         
    average = sum / (len(value))
    return average
    
def main():
    count = 0
    while count < 3:
        inFile = input('Please enter a filename (ie. exmaple.txt): ')
        x = initList(inFile)
        
        if x == False:
            count += 1
            print('Error, file not found')
        else :
            print('The list below is the values in the data:' + '\n' + x)
            y = getSize(x)
            print("There are", y, "numbers in the list")

            z = getHighest(x)
            print("The highest temperature is", z)
            a = getLowest(x)
            print("The lowest temperature is", a)
            b = getAverage(x)
            print("The average temperature is", b)
            count = 4
    
        
main()


'''
Please enter a filename (ie. exmaple.txt): temp.txt
The list below is the values in the data:
-0.07
-0.68
-0.26
-0.16
0.32
-0.2
-0.49
-0.5
-0.17
0.0
-0.52
-0.4
-0.81
-0.7
-0.37
-0.01
-0.35
-0.99
0.32
-0.27
0.21
-0.19
-0.26
-0.17
-0.21
-0.53
-0.16
-0.22
-0.27
-0.6
-0.57
-0.31
-0.82
-0.58
-0.93
-0.56
-0.54
-0.46
-0.75
-0.6
-0.72
-0.77
-0.77
-0.53
-0.5
-0.78
-0.45
-0.35
-0.64
-0.53
-0.64
-0.12
-0.97
-0.96
-1.05
-0.6
-0.6
-0.92
-0.79
-0.86
-0.63
-0.62
-1.09
-1.06
-0.6
-0.64
-0.48
-0.54
-0.75
-0.66
-0.52
-0.3
-0.69
-0.63
-0.66
-0.58
-0.67
-0.3
-0.45
-0.67
-0.32
-0.15
-0.47
-0.27
-0.39
-0.38
-0.09
-0.21
-0.29
-0.26
-0.32
-0.27
-0.46
-0.4
-0.39
-0.6
-0.43
-0.41
-0.51
-0.62
-0.75
-0.47
-0.27
-0.26
-0.58
-0.51
-0.82
-0.55
-0.61
-0.51
-0.53
-0.52
-0.46
-0.38
-0.64
-0.75
-0.39
-0.55
-0.73
-0.55
-0.49
-0.69
-0.61
-0.39
-0.58
-0.49
-0.83
-0.44
-0.69
-0.45
-0.36
-0.32
-0.38
-0.09
-0.45
-0.66
-0.53
-0.15
-0.01
-0.13
-0.22
0.04
-0.81
-0.45
0.0
-0.01
-0.1
-0.04
0.49
0.05
0.06
0.24
0.45
0.17
0.02
0.49
0.46
0.3
0.23
0.22
0.65
0.43

There are 162 numbers in the list
The highest temperatureis 0.65
The lowest temperatureis -1.09
The average temperature is -0.4016049382716049

'''
