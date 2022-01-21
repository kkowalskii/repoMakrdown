# repoMarkdown

Repozytorium stworzone na labortatoria nr 13

Niezły **Markdown**  
*3-ci paragraf*  
pogrubienie oraz kursywa **_na raz_**  
~~przekreślony tekst~~
> cytat 

**Lista numeryczna:**
> 1. First
> 2. Second
> 3. Third
> 4. Fourth

**Lista nienumeryczna:**
> - 5-ty
> - 6-ty

1. Otwórz folder , w którym znajduje się plik , z którego chcesz odczytać co czwartą literę

        def otworz_plik(nazwa_pliku):
            f = open(nazwa_pliku, "r")
            f.close()

        f = open("linie.txt", "r")

        x = -1

        for line in f:
            for znak in line:
                x += 1
                if x == 3:
                    print(znak, end="")
                    x = -1

        f.close()
        
* example

        this.isSomeCode = true;

*  
        addMoreCode();
