 name = input("what is your name:")
test = int(input("what is your test score:"))
second_test = int(input("what is your test score:"))
attendance = int(input("what is the score for your attendance:"))
exam = int(input("what is the score for your exam:"))
print("------------------------------------------------")
total_score = test + second_test + attendance + exam

if total_score >= 70:
    grade = "A"
elif total_score >= 60:
    grade  = "B"
elif total_score >= 50:
    grade = "C"
elif total_score >= 45:
    grade = "D"
elif total_score >= 40:
    grade = "E"
else:
    grade = "F"
    
print(f"hello {name}, Your total score is {total_score} and your grade is {grade}")

<!---
Emmaprof/Emmaprof is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
