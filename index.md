# Header
![Image of cato](https://static1.e621.net/data/56/b4/56b4f015e8cab1a0b5fd5249cd6a800e.png)
## Eso es un gato

```
""" rock paper scissors game """

import random 


computer = random.randint(1,5)
again = 'y'
print('================================')
print('Rock Paper Scissors Lizard Spock')
print('================================')

while again == 'y':

    computer = random.randint(1,3)
    emoji = '' 

    if computer == 1:
        emoji = '✊'
    elif computer == 2:
        emoji = '✋'
    elif computer == 3:
        emoji = '✌️'
    elif computer == 4:
        emoji = '🦎'
    elif computer == 5:
        emoji = '🖖'

    print('1)✊')
    print('2)✋')
    print('3)✌️')
    print('4)🦎')
    print('5)🖖')

    player = int(input('Choose your weapon: '))

    if player == 1:
        print('You chose ✊')
        print(f'Computer chose {emoji}')
        if computer == 1:
            print('It\'s a tie!')
        elif computer == 2:
            print('You lose!')
        elif computer == 3:
            print('You win!')
        elif computer == 4:
            print('You win!')
        elif computer == 5:
            print('You lose!')

    elif player == 2:
        print('You chose ✋')
        print(f'Computer chose {emoji}')
        if computer == 1:
            print('You win!')
        elif computer == 2:
            print('It\'s a tie!')
        elif computer == 3:
            print('You lose!')
        elif computer == 4:
            print('You lose!')
        elif computer == 5:
            print('You win!')
        
    elif player == 3:
        print('You chose ✌️')
        print(f'Computer chose {emoji}')   
        if computer == 1:
            print('You lose!')
        elif computer == 2:
            print('You win!')
        elif computer == 3:
            print('It\'s a tie!')
        elif computer == 4:
            print('You win!')
        elif computer == 5:
            print('You lose!')
    elif player == 4:
        print('You chose 🦎')
        print(f'Computer chose {emoji}')
        if computer == 1:
            print('You lose!')
        elif computer == 2:
            print('You win!')
        elif computer == 3:
            print('You lose!')
        elif computer == 4:
            print('It\'s a tie!')
        elif computer == 5:
            print('You win!')
    elif player == 5:
        print('You chose 🖖')
        print(f'Computer chose {emoji}')
        if computer == 1:
            print('You win!')
        elif computer == 2:
            print('You lose!')
        elif computer == 3:
            print('You win!')
        elif computer == 4:
            print('You lose!')
        elif computer == 5:
            print('It\'s a tie!')

    else:
        print('Invalid choice')
        continue
    
    again = input('Play again? (y/n): ')
```
