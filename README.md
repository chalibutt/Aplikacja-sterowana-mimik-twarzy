# Aplikacja-sterowana-mimik-twarzy

Wykorzystane Technologie:
- Python
- OpenCV
- dlib
- PyGame
- Anaconda Navigator
- Jupyter-Lab

Opis Aplikacji:
Jest to gra na systemie Windows, wzorowana na kultowym "Space Invaders".
Gracz steruje statkiem za pomocą 5 ruchów twarzy:
- Zamknięcie lewego oka - ruch statku w lewo
- Zamknięcie prawego oka - ruch statku w prawo
- Uśmiech - strzał laserem
- Podniesienie brwi do góry - ruch statku w górę
- Zmarszczenie brwi - ruch statku w dół

Po uruchomieniu pokazują się dwa okna. Pierwsze główne okno gry i okno dodatkowe
pokazujące obraz z kamerki internetowej dzięki któremu możemy śledzić poprwaność
detekcji. Użytkownik ma 15 szans i 100 punktów zdrowia. Przepuszczenie przeciwnika poza dolną krawędź
skutkuje utratą szansy a zderzenie z innym statkiem lub laserem powoduje utrate 10 punktów zdrowia. W obu przypadkach gdy zdrowie lub szanse spadna do zera rozgrywka jest przerywana i grę można zacząc od poczatku. Po pokonaniu wszystkich wrogów gracz wchodzi na nastepny poziom a liczba przeciwników się zwiększa o 3 co z czasem znacznie utrudnia rozgrywke.

# Application-controlled-by-facial-expressions

Technologies used:
- Python
- OpenCV
- dlib
- PyGame
- Anaconda Navigator
- Jupyter-Lab

Application Description:
It is a Windows game, modeled on the "Space Invaders".
The player controls the Spaceship with 5 face movements:
- Left eye closure - ship moves left
- Right eye closure - ship moves right
- Smile - laser shot
- Raising eyebrows up - movement of the ship up
- Frowning - downward movement of the ship

After starting, two windows appear. First main game window and additional window
showing the image from the webcam, thanks to which we can track the accuracy of
detection. The user has 15 chances and 100 health points. Passing the opponent over the bottom edge
results in the loss of the chance. The collision with another ship or laser causes the loss of 10 health points. In both cases, when health or chances are reduced to zero, the game is over and can be started from the beginning. After defeating all the enemies, the player enters the next level and the number of enemies increases by 3, which makes the game much more difficult with time.
