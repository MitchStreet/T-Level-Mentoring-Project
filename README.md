
# T-Level Mentoring Project

The following is documentation on a program made in collaboration with a 2nd year T-Level DPDD student and two 1st year T-Level DPDD students.

## What was required?
A brief was provided and the following requirements were extracted from it. 

A console-based program made for a uniform shop to allow customers to select a school, the items for that school and purchase all these items from the cart.
The user experience is top priority due to console-based programs being non-user friendly by design.
Data validation and other features were implemented to improve beyond the spec but the main requirements were still met – only improved upon.

## Features

- Main menu
- User can select the school
- User can select items
- Program calculates saved order value
- User can choose between collection and delivery
- Program stores confirmed orders in an external file
- Modularisation
The program only runs code as and when needed in the program, saving on resources.

Data validation is present throughout the whole program, errors and invalid data inputs are handled gracefully without the program erroring.

## Python modules used

#### Pandas

```http
  import pandas as pd
```

| Function | Description                |
| :-------- | :------------------------- |
| `pd.read_csv` | Opens the .csv file |


#### Colorama

```http
  from colorama import Fore
```

| Function | Description                |
| :-------- | :------------------------- |
| `Fore.COLOUR` | Sets text colour |

‘Colorama’ is seen throughout the program, it is a vital asset in improving the UX by clearly diversifying the different outputs on the screen.

Colours are the best – if not the only – way to improve the appearance of a console-based program. 

#### Time

```http
  import time
```

| Function | Description                |
| :-------- | :------------------------- |
| `time.sleep()` | Pauses program for specified time |

Pauses in the program help break up the flow of the program and make outputs easier to read.

#### Random

```http
  import random
```

| Function | Description                |
| :-------- | :------------------------- |
| `random.randint(min, max)` | Generates random  number |

Used in the order number generation process.


## Screenshots and explanations

### The main menu:
![The main menu](https://github.com/MitchStreet/T-Level-Mentoring-Project/blob/main/main%20menu.png?raw=true)

The first thing the user sees when the program loads up, the title presented as ASCII art is displayed with each of the options available to the user.

All of the sub-menus are accessible through this main menu and as standard, the input are data validated:
As they are throughout the program.


### Browse items:
![Browse items](https://github.com/MitchStreet/T-Level-Mentoring-Project/blob/main/browse%20items.png?raw=true)

Once the user has selected their desired school, the items tagged with that school are displayed with all their relevant information. 
Rather than complicating the selection process, there is no further filtering other than by schools, due to the tediousness of exiting menus to select different items.


### Selected school:
![Selected school](https://github.com/MitchStreet/T-Level-Mentoring-Project/blob/main/selected%20school.png?raw=true)


### Empty cart:
![Empty cart](https://github.com/MitchStreet/T-Level-Mentoring-Project/blob/main/empty%20cart.png?raw=true)


### Populated cart:
![Populated cart](https://github.com/MitchStreet/T-Level-Mentoring-Project/blob/main/populated%20cart.png?raw=true)

Once all of the items are selected, the user can view the final price and choose to either order them online (delivery), arrange a collection or exit to continue shopping.
For example, if the user decides they want them delivered then their name, address and payment details are requested and saved
All orders are saved in the attached log.txt file.



### Confirm order:
![Confirm order](https://github.com/MitchStreet/T-Level-Mentoring-Project/blob/main/confirm%20order.png?raw=true)


## Created by

- [Eliyan Riasat](https://github.com/eriasat112)
- [Sean Stewart]()
- [Mitchell Street](https://github.com/MitchStreet)

