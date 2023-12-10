# Array
ef display_names_and_scores(names, scores):
    for i in range(len(names)):
        print(f"{names[i]} - Exam Score: {scores[i]}")

# Assign 10 last names and exam scores to parallel arrays
last_names = ["Smith", "Johnson", "Williams", "Jones", "Brown", "Davis", "Miller", "Wilson", "Moore", "Taylor"]
exam_scores = [85, 92, 78, 95, 88, 90, 87, 93, 89, 91]

# Display the names and exam scores
print("Names and Exam Scores:")
display_names_and_scores(last_names, exam_scores)
