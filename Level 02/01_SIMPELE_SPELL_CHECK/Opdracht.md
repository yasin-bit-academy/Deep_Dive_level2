## Opdracht 01: Simpele spellchecker

### In te leveren bestanden
1) `spellchecker.php`

### Opdracht
Een veelgemaakte fout in teksten is het per ongeluk toevoegen van een dubbele spatie. Tijd om dit weg te automatiseren. Schrijf een programma dat dubbele en trailing spaties
weghaald uit een stuk tekst. Let op dat de tekst meegegeven wordt als parameter aan het programma

### Nieuwe Technieken
- Command line arguments

### Output
```bash
> php spellchecker.php 
> php spellchecker.php "Hallo,   Hoe gaat het   programmeren  tot nu toe?"
> Hallo, Hoe gaat het programmeren tot nu toe?
> php spellchecker.php "   Hi   "
> Hi
```