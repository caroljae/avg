# avg
**Python Averages College Level


def main():

    total = 0.0
    grades = [0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0]
    tests = ["Test 1: ","Test 2: ","Test 3: ","Test 4: ","Test 5: ","Test 6: ","Test 7: "]

    for i in range(7):
        grades[i] = float(input("Please enter the student test score for " + tests[i]))

    for number in grades:
        total += number

    size = len(grades)
    average = total / size

    print("******Student Test Scores********")
    print("Score\t\tNumeric Score")
    print("Score 1:\t", format(grades[0],'.1f'))
    print("Score 2:\t", format(grades[1],'.1f'))
    print("Score 3:\t", format(grades[2],'.1f'))
    print("Score 4:\t", format(grades[3],'.1f'))
    print("Score 5:\t", format(grades[4],'.1f'))
    print("Score 6:\t", format(grades[5],'.1f'))
    print("Score 7:\t", format(grades[6],'.1f'))
    print("Total:\t\t", format(total,'.1f'))
    print("Average Score:\t", format(average,'.1f'))
             

main()


