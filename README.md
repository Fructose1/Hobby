import random

def play_game():
    # Simulating a football game
    team1_score = random.randint(0, 5)
    team2_score = random.randint(0, 5)
    
    print("Team 1 score:", team1_score)
    print("Team 2 score:", team2_score)
    
    if team1_score > team2_score:
        print("Team 1 wins!")
    elif team2_score > team1_score:
        print("Team 2 wins!")
    else:
        print("It's a draw!")

play_game()
