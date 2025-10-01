### SCHOOL-GRADING-SYSTEM
 A REPO FOR SCHOOL GRADING SYSTEM
print("good morning")
name= input(" enter your name:")
score=int(input("enter your score:"))


if score>= 80 and score <= 100:
    print(f"{name} you got an A")
elif score>= 70 and score<= 79:
    print(f"{name} you got B")
elif score>= 60 and score <= 69:
    print(f"{name} you got C")
elif score >= 45 and score <= 59:
    print(f"{name} you got D")
elif score >= 35 and score <= 44:
    print(f"{name} you got E")
elif score >= 0 and score <= 34:
    print(f"{name} you got F")
else:
    print("oga u will never make it")
