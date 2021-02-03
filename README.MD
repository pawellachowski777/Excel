# Zautomatyzowany grafik

Projekt zrealizowany na zlecenie małego przedsiębiorcy. Moim zadaniem było stworzenie narzędza, które przyśpieszy proces ręcznego rysowania grafików pracy robionych w Excelu. Dodatkowym zadaniem, które wyznaczyłem sobie sam, było zaprojektowanie grafiku tak, aby konstrukcja była zbliżona do oryginału, jednak wyglądająca bardziej estetycznie i profesjonalnie. Bardzo istotnym było też kryterium łatwości w obsłudze.  
___
Na pasku szybkiego dostępu znajdują się dwa przyciski przypisane do makr.  
![makra](https://drive.google.com/uc?export=view&id=1DI5qar2KTKf-HZO3BPw2BgRvVKvmaoLY)  
Pierwszy służy do rysowania godzin za pomocą input boxów.  
Drugi zapisuje wszystkie arkusze w formie pliku *.pdf*.
___
Kolejnym udogodnieniem jest zdefiniowana przezemnie funkcja LiczGodziny, która oblicza ilość godzin dla każdego z pracowników w danym tygodniu.  
![licz](https://drive.google.com/uc?export=view&id=1qYYyrHKzE4j9yRyV0Nkwac0zh0OkMGhd)  
Obok obliczone są także godziny przepracowane w całym miesiącu. Ze względów optymalizacyjnych postanowiłem wyłączyć automatyczne obliczanie formuł. Do grafiki obok tabeli jest przypisane makro, które odświeża wszystkie oblicznia w skoroszycie.  
___
Ostatnią, ale nie mniej ważną funkcją jest możliwość automatycznego uzupełniania dni w miesiącu.
![kalendarz](https://drive.google.com/uc?export=view&id=1-bQRePxONt1rHcFWVJ01YdBsx_9HrLRE)  
Po wybraniu miesiąca i roku należy kliknąć grafikę kalendarza, a program ponumeruje dni zgodnie z kalendarzem. Zaktualizowane zostają także nazwy arkuszy.
