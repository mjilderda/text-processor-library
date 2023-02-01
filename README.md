# Text-processor library

### Beschrijving
Text-processor library voor het doen van analyses op een tekst.<br />
De functionaliteit zit in de `service` & `utils` packages. 

### WordfrequencyService
In de `WordFrequencyService` class zitten de functionaleiten. Deze class bevat de volgende 3 public methods:

#### calculateHighestFrequency(String text)
Retourneerd het aantal voorkomens van het meestvoorkomende woord in de tekst.

#### calculateFrequencyForWord(String text, String word)
Retourneerd het aantal keer dat het ingevoerde woord in de tekst voorkomt.

#### List<WordFrequency> calculateMostFrequentNWords(String text, int n)
Retourneerd een list met de meestvoorkomende woorden en bijbehorende frequentie. De value `n` geeft de maximale size van de list aan. <br />
Indien de tekst minder woorden dan deze `n` waarde bevat, worden alle woorden geretourneerd.

### UtilityClass WordUtils
Ondersteunend aan de functionaliteiten in de bovenstaande methodes worden bewerkingen op de teksten en woorden worden gedaan in de `WordUtils` class.
Dit is een `UtilityClass` met static methods.
