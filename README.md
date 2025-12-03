# Simple Gaming Quiz

score = 0

print("🎮 Welcome to the Gaming Quiz! 🎮")

q1 = input("1. Which game features the character Mario? ")
if q1.lower() == "super mario":
    score += 1

q2 = input("2. In which game do you fight Ender Dragon? ")
if q2.lower() == "minecraft":
    score += 1

q3 = input("3. PUBG stands for? ")
if q3.lower() == "playerunknown's battlegrounds":
    score += 1

print(f"\nYour final score: {score}/3")
print("Thanks for playing!")# Manjufile02
