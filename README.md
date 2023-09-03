# Pomodoro V1 pour tester et apprendre des trucs
une heure par tous les dimanches
aussi 3 tuto pour comprandre
1 A circuit and program that has different modes and a pause button. [Pomodoro technique.](https://en.wikipedia.org/wiki/Pomodoro_Technique)
2 un autre git
3 un tuto sur instructable
4 la doc générale arduino pour trouver comment connecter l'ecran sans potard... (le plus dur c'est pas bien explique a mon gout)


## Function

1. A timer that displays how many seconds you have left.
2. Study timer: 25 mins
(avec un joli txt c'est mieux "arduino suck! par exemple...)
3. Short break timer: 5 mins
(fo arreter de regarder l'ecran, on bosse ! mais ou est le bip? on entand rien !)
4. Long break timer: 10 mins
(pareil pas de bip audible ?)
5. After each timer has passed it goes to the next mode.
6. You can also pause the timer and then resume it with the same button. (ca a pa l'air de marcher ...)

## What I learned

0.1 c'est quoi git en vrais (sous unbuntu nul, sous win c'est mal mais ca marche mieux)

0.2 commznt le mettre sur win et ubuntu (je vais changer c'est nul)
0.3 mise a jour up et down

1. How to take input using a push button.
2. How to display and wire an LCD module.
3. How to make a rudimentary timer using delay().
4. How to receive input while the program is running.

## Notes

I had to figure out a way to make a timer that didn't keep the program stalled at delay(). I had to use a for loop that would delay for 1 sec each loop. The problem with this was that you would have to hold down the button for 1-2 seconds for it to actually receive the input and there was a chance for it to keep recieving the input afterwards. I added a two second delay between each input beind received to prevent unwanted inputs. The former issue could be solved by counting milliseconds instead of seconds.

## Images

![Diagram](https://i.ibb.co/XbHFDQ2/pomodoro-diagram.png)
![Finished product](https://cdn.discordapp.com/attachments/577007309461389312/578139617509769216/image0.png)

*The contrast can be adjusted by adding a potentiometer to the contrast pin of the LCD*
