# Gurgaon Treasure Hunt Adventure

Welcome to the **Gurgaon Treasure Hunt Adventure**! This interactive game takes you on a thrilling journey through the bustling streets of Gurgaon, where you can explore Cyber City or the mysterious Moulsari Avenue in search of hidden treasure.

## Table of Contents

- [Game Overview](#game-overview)
- [How to Play](#how-to-play)
- [Game Instructions](#game-instructions)
- [Game Code](#game-code)
- [Contributing](#contributing)
- [License](#license)

## Game Overview

In this adventure, you are an intrepid explorer on the hunt for hidden treasure rumored to be buried in DLF Phase 3, Gurgaon. Starting at the iconic **Guru Dronacharya Metro Station**, you must make choices to navigate through Cyber City's hustle or Moulsari Avenue's mystery to uncover the treasure.

## How to Play

1. **Run the Game**  
   Make sure you have Python installed. Run the following command in your terminal:
   ```bash
   python treasure_hunt.py
   ```

2. **Follow the Prompts**  
   Follow the on-screen prompts to make choices and navigate through the adventure.

## Game Instructions

- You will be prompted to choose between **Cyber City** and **Moulsari Avenue**.
- Depending on your choices, you will encounter different scenarios that lead you closer to the treasure or to dead ends.
- Make decisions wisely, as they will affect the outcome of your adventure.

## Game Code

Below is the code for the **Gurgaon Treasure Hunt Adventure**:

```python
# Gurgaon Treasure Hunt Adventure Game Code

name = input("Type Your Name: ")
print("Welcome", name, "to this thrilling Gurgaon Treasure Hunt Adventure!")

print("In this adventure, you are an intrepid explorer on the hunt for hidden treasure rumored to be buried in DLF Phase 3, Gurgaon. Starting at the iconic Guru Dronacharya Metro Station, you must make choices to navigate through Cyber City's hustle or Moulsari Avenue's mystery to uncover the treasure. Choose wisely and embrace the challenge!")

answer = input("You’re at the metro station entrance. Do you want to explore Cyber City or head towards Moulsari Avenue? Type 'Cyber City' or 'Moulsari': ")

if answer.lower() == "cyber city":
    print("You decide to head to Cyber City, bustling with skyscrapers and offices. As you wander through the streets, you notice a map sticking out of a planter near a café.")
    answer = input("Do you want to pick up the map or ignore it? Type 'pick' or 'ignore': ")

    if answer.lower() == "pick":
        print("The map shows a route leading towards Ambience Mall with a clue about a secret door near the parking area.")
        answer = input("Do you follow the map to Ambience Mall? Type 'yes' or 'no': ")

        if answer.lower() == "yes":
            print("You arrive at Ambience Mall's parking area and find a hidden lever disguised as a pipe. Pulling it opens a trapdoor!")
            answer = input("Do you climb down the trapdoor? Type 'yes' or 'no': ")

            if answer.lower() == "yes":
                print("You find yourself in a dimly lit underground room. There’s a chest in the center. You open it and find the treasure! Congratulations, you’ve won!")
            else:
                print("You decide not to climb down. The treasure remains undiscovered. Maybe next time!")
        else:
            print("You ignore the map and end up lost in the maze of Cyber City. The treasure hunt ends here.")

    else:
        print("You ignore the map and continue wandering aimlessly. Without a lead, your adventure comes to an uneventful end.")

elif answer.lower() == "moulsari":
    print("You decide to head towards Moulsari Avenue. The quiet streets feel mysterious. You notice an old man sitting on a bench holding a curious-looking box.")
    answer = input("Do you approach the old man or walk past him? Type 'approach' or 'walk': ")

    if answer.lower() == "approach":
        print("The old man smiles and hands you the box. Inside, there’s a riddle: 'To find the gold, follow the bold, under the banyan tree so old.'")
        print("You recall seeing a huge banyan tree near Aravalli Biodiversity Park.")
        answer = input("Do you head to the park? Type 'yes' or 'no': ")

        if answer.lower() == "yes":
            print("You reach the park and find the banyan tree. Digging beneath it, you uncover the hidden treasure chest. Congratulations, you’ve found the treasure!")
        else:
            print("You decide not to follow the clue. The treasure remains hidden, and your adventure ends here.")
    else:
        print("You walk past the old man, missing the vital clue. The treasure hunt comes to an end with no leads.")

else:
    print("Invalid input. Please try again and choose a valid path next time!")

print("Thank you for playing,", name, "! We hope you enjoyed the adventure.")
```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Thank you for playing! We hope you enjoy the adventure.
