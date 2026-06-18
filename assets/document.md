# Cel ćwiczenia

Celem projektu było przeprowadzenie symulacji przepływu wokół przeszkody.

# Wyniki pomiarów

Przeprowadzono symulacje

## Funkcja potencjału prędkości ($\phi$)

Poniższy wykres przedstawia rozkład potencjału prędkości dla przepływu jednorodnego z przeszkodą.

```{figure} plot1.png
Rozkład potencjału prędkości dla przepływu jednorodnego.
```

W obszarach oddalonych od przeszkody widoczny jest liniowy charakter funkcji zgodny z warunkiem $\phi(x,y)=u_0x$. W rejonie przeszkody oraz przy dolnym brzegu obserwuje się wyraźne zaburzenia linii ekwipotencjalnych wynikające z warunków Neumanna, które wymuszają brak przepływu przez ściany oraz symetrię względem osi.

## Funkcja prądu ($\psi$)

Na poniższym wykresie przedstawiono funkcję prądu pokazującą linie strumienia przepływu cieczy.

```{figure} plot2.png
Rozkład trajektorii przepływu.
```

Linie te są równoległe do kierunku przepływu w obszarze swobodnym i ulegają odkształceniu w pobliżu przeszkody. Dolny brzeg oraz powierzchnia przeszkody stanowią linie strumienia ($\psi = const$), co zapewnia brak przepływu przez te obszary. W efekcie linie prądu „opływają” przeszkodę, zachowując ciągłość przepływu.

# Podsumowanie

Oba rozwiązania są zgodne jakościowo z fizyką przepływu potencjalnego:

- $\phi$ opisuje pole potencjału (linie prostopadłe do przepływu),
- $\psi$ opisuje linie prądu (trajektorie przepływu).

# Literatura

1. Kod źródłowy <https://github.com/gucio321-studies/MOFProj6>
