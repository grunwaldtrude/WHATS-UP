
w = 'n'
total = 0
median = []
while w != 'y':
    number = int(input("Enter a number:  "))
    total = total + number
    median.append(number)
    n = len(median)
    for i in range(n):
        for j in range(0, n-i-1):
            if median[j] > median[j+1] :
                median[j], median[j+1] = median[j+1], median[j]

    w = input("Would you like to quit? Y/N: ").lower()


def mode(median):
    locator = 0
    num = median[0]
    for i in median:
        occuring = median.count(i)
        if(occuring> locator):
            locator = occuring
            num = i

    return str(num)
print("The mean is:   "+str(total/len(median)))
print("The median is:   "+str(median[round(len(median)/2)]))
print("The mode is:   "+mode(median))
