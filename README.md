# Dice-game
A basic game that very python coder love to do at learning stage
import random
def roll_dice(num_dice):
    return[random.randint(1,6) for _ in range(num_dice)]
def main():
    num_dice = int(input("how many dice do you want to rokll? "))
roll_count=0
while true:
    results=roll_dice(num_dice)
    print("you rolled: " , results)
    roll_count += 1
again = input("roll again ? (y/n):").lower()
if again != 'y':
    break
print(f"you rolled {roll_count} times.good bye!")
if__name__ == "__main__":
    main()
