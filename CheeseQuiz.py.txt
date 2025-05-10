def cheese_quiz():
    score = 0

    print("Welcome to the Cheese Quiz!\n")

    # Question 1
    print("1. Which country is famous for Roquefort cheese?")
    print("A. Italy\nB. France\nC. Switzerland\nD. Spain")
    answer = input("Your answer: ").strip().upper()
    if answer == "B":
        print("Correct!\n")
        score += 1
    else:
        print("Wrong. The correct answer is B. France\n")

    # Question 2
    print("2. What type of milk is traditionally used to make mozzarella?")
    print("A. Cow\nB. Goat\nC. Buffalo\nD. Sheep")
    answer = input("Your answer: ").strip().upper()
    if answer == "C":
        print("Correct!\n")
        score += 1
    else:
        print("Wrong. The correct answer is C. Buffalo\n")

    # Question 3
    print("3. Which cheese is known for having holes in it?")
    print("A. Brie\nB. Cheddar\nC. Emmental\nD. Gouda")
    answer = input("Your answer: ").strip().upper()
    if answer == "C":
        print("Correct!\n")
        score += 1
    else:
        print("Wrong. The correct answer is C. Emmental\n")

    # Question 4
    print("4. What cheese is commonly used on pizza?")
    print("A. Feta\nB. Mozzarella\nC. Blue cheese\nD. Camembert")
    answer = input("Your answer: ").strip().upper()
    if answer == "B":
        print("Correct!\n")
        score += 1
    else:
        print("Wrong. The correct answer is B. Mozzarella\n")

    print(f"You got {score} out of 4 correct.")

cheese_quiz()
