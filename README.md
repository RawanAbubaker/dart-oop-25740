\# Dart OOP Assignment: Kigali Bus Card



\*\*Name:\*\* Rawan Abubaker

\*\*Student ID:\*\* 25740



\## My numbers

\- D = 40, L = 0

\- Starting balance = 1000 + (40 x 10) = 1400 RWF

\- Bus fare = 200 + 40 = 240 RWF

\- Student discount = 10 + 0 = 10%



\## Part 5

My prediction: it prints 1 and then 5.



Why: For Bag a, add() makes \_items 1. Then a.items = -5 is refused because the setter only accepts values that are 0 or more, so \_items stays 1 and it prints 1. For BigBag b, add() calls super.add() twice, so each add() adds 2. After two add() calls \_items is 4. Then b.items = b.items + 1 makes it 5, which the setter accepts, so it prints 5.

