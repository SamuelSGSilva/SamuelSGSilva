# README

## LinkedIn

[LinkedIn](https://www.linkedin.com/in/samuel-dos-santos-3a2040241?utm_source=share_via&utm_content=profile&utm_medium=member_android)


## Featured Projects

```
import time
import os

# Simple Snake Game in Terminal
width = 20
height = 20
snake = [(10,10), (10,9), (10,8)]
food = (5,5)

while True:
    os.system('cls' if os.name == 'nt' else 'clear')
    for y in range(height):
        for x in range(width):
            if (x,y) in snake:
                print('S', end='')
            elif (x,y) == food:
                print('F', end='')
            else:
                print('.', end='')
        print()
    time.sleep(0.1)
    # Update the snake's position
    # (Add logic here)
```

# Note: The snake game logic needs to be implemented.