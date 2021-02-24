# Aplikacja-sterowana-mimik-twarzy

Wykorzystane Technologie:
- Python
- OpenCV
- dlib
- PyGame
- Anaconda Navigator
- Jupyter-Lab

Opis Aplikacji:
Jest to gra na systemie Windows wzorowana na kultowym "Space Invaders".
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
