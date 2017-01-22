# Blackboard
TeX-paket för föreläsnings- och övningsanteckningar.

## Kommandon för att initiera paketet
\usepackage[kurskod, typ]{blackboard}
Där kurskod är ex. SG1113, eller SI1140II för SI1140 del 2. Typ kan vara 'lecture', 'excercise' eller 'handin'.

\classno{#} anger vilken lektion, eller uppgiftsnummer det är.

## Miljöer för lektionsanteckningar

definition, sats, exempel, bevis
Samtliga har frivilligt argument för namn på miljön

Exempelvis ger
\begin{sats}[Additionsformel]
  Test
\end{sats}
