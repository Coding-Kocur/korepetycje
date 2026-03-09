# Dwie proste przecięte trzecią. Suma kątów w trójkącie

## Zadania

**Zadanie 1 (Bardzo łatwe)**
W trójkącie ABC kąt przy wierzchołku A ma miarę 50°, a przy wierzchołku B miara wynosi 65°. Jaka jest miara trzeciego kąta przy wierzchołku C? Jak nazwiemy ten trójkąt ze względu na boki?

**Zadanie 2 (Łatwe)**
Dwie proste równoległe k i l zostały przecięte nową prostą m. Jeden z powstałych kątów ostrych ma miarę 40°. Oblicz miary wszystkich pozostałych 7 kątów (ostrych i rozwartych).

**Zadanie 3 (Średnie)**
Oblicz pole trójkąta prostokątnego o kątach 30°, 60° i 90°, którego przeciwprostokątna ma długość 10. Wykorzystaj własności trójkątów szczególnych.

**Zadanie 4 (Trudne)**
Wewnątrz płaskiego pasa utworzonego przez dwie proste równoległe a i b wybrano punkt P. Z punktu P poprowadzono półproste - jedną do punktu A na prostej a, a drugą do punktu B na prostej b. Kąt ostry pomiędzy prostą a i odcinkiem AP wynosi 35°. Kąt ostry pomiędzy prostą b i odcinkiem BP wynosi 45° (kąty leżą po tej samej stronie łamanej). Oblicz miarę kąta APB, jeśli wierzchołek P jest wklęsły w stosunku do prostych (czyli stanowi punkt załamania łamanej APB między prostymi).

**Zadanie 5 (Bardzo trudne)**
Wykaż, wykorzystując własności kątów utworzonych przez dwie proste równoległe przecięte trzecią prostą, że suma miar kątów wewnętrznych w dowolnym trójkącie wynosi dokładnie 180°.

---

## Rozwiązania

**Rozwiązanie 1**
Suma miar kątów w trójkącie wynosi 180°. Miara kąta przy wierzchołku C wynosi zatem:
$180^\circ - (50^\circ + 65^\circ) = 180^\circ - 115^\circ = 65^\circ$.
Ponieważ trójkąt ten ma dwa kąty o równej mierze (65° i 65°), jest to trójkąt równoramienny.

**Rozwiązanie 2**
Z własności kątów wierzchołkowych i naprzemianległych wynika, że wszystkie 4 kąty ostre w tym układzie mają jednakową miarę równą 40°. Kąt ostry i kąt rozwarty leżące przy tej samej prostej (na jedno ramię i prostą docelową) to kąty przyległe, a więc ich suma to 180°. Zatem każdy kąt rozwarty ma miarę:
$180^\circ - 40^\circ = 140^\circ$.
Odpowiedź: 3 pozostałe kąty ostre mają miarę 40°, a 4 kąty rozwarte mają miarę 140°.

**Rozwiązanie 3**
Trójkąt prostokątny o kątach 30°, 60° i 90° stanowi połowę trójkąta równobocznego o boku długości równej długości przeciwprostokątnej (czyli $a = 10$). 
Krótsza przyprostokątna (leżąca naprzeciw kąta 30°) ma długość połowy przeciwprostokątnej, czyli $\frac{10}{2} = 5$.
Dłuższa przyprostokątna (leżąca naprzeciw kąta 60°) to jednocześnie wysokość wyjściowego trójkąta równobocznego, więc liczymy ją ze wzoru $h = \frac{a\sqrt{3}}{2} = \frac{10\sqrt{3}}{2} = 5\sqrt{3}$.
Mając długości obu przyprostokątnych, które stanowią odpowiednio podstawę i wysokość naszego trójkąta prostokątnego, liczymy jego pole:
$P = \frac{1}{2} \cdot 5 \cdot 5\sqrt{3} = 12,5\sqrt{3}$.

**Rozwiązanie 4**
Aby rozwiązać to zadanie, prowadzimy przez punkt P dodatkową prostą $c$, równoległą do prostych $a$ i $b$. Prosta ta dzieli szukany kąt $APB$ na dwa mniejsze kąty. 
Górny z tych kątów (między odcinkiem AP a prostą c) tworzy wraz z kątem 35° przy prostej $a$ parę kątów naprzemianległych. Ponieważ proste $a$ i $c$ są równoległe, miary tych kątów są równe, więc kąt ten ma 35°.
Dolny z tych kątów (między odcinkiem BP a prostą c) tworzy wraz z kątem 45° przy prostej $b$ parę kątów naprzemianległych. Podobnie, miary te są równe, więc kąt ten ma 45°.
Szukany kąt $APB$ to suma tych dwóch kątów, więc $\angle APB = 35^\circ + 45^\circ = 80^\circ$.

**Rozwiązanie 5**
Rozważmy dowolny trójkąt $ABC$. Poprowadźmy przez wierzchołek $C$ prostą $k$ równoległą do prostej zawierającej przeciwległy bok trójkąta (bok $AB$).
Przy wierzchołku $C$ powstał kąt półpełny wyznaczony przez prostą $k$, którego miara to oczywiście 180°. Kąt ten podzielony jest przez ramiona kąta wewnętrznego trójkąta na trzy mniejsze kąty.
Środkowy kąt to po prostu kąt wewnętrzny trójkąta przy wierzchołku $C$.
Kąt skrajnie po lewej leży naprzemianlegle do kąta wewnętrznego przy wierzchołku $A$ (przecinającą prostą jest prosta $AC$). Ponieważ rozważane proste są równoległe, kąty te mają równe miary.
Kąt skrajnie po prawej leży naprzemianlegle do kąta wewnętrznego przy wierzchołku $B$ (przecinającą prostą jest prosta $BC$). Proste są równoległe, więc kąty te mają równe miary.
Widzimy zatem, że kąt oznaczający na górze miarę 180°, stanowiący jeden wielki stelaż na osi płaskiej, to dosłownie suma miar trzech kątów naszego trójkąta. To wprost i bezwzględnie dowodzi stwierdzenie, że suma miar wewnętrznych kątów każdego trójkąta wynosi 180°.
