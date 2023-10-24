# solution for hack 1 (isabelle)
just replace "procedure" with something like "update_quiz_grade"

# solution for hack 2 (jason)
---

# solution for hack 3 (rayane)
def calculate_grade(points_earned):
    if points_earned >= 50:
        return 'Pass'
    else:
        return 'Fail'

#Replace this value with the points you earned on the exam
points_earned = 75

exam_grade = calculate_grade(points_earned)

print(f'Your exam grade: {exam_grade}')