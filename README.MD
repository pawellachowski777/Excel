# Zautomatyzowany grafik

Projekt zrealizowany na zlecenie ma³ego przedsiêbiorcy. Moim zadaniem by³o stworzenie narzêdza, które przyœpieszy proces rêcznego rysowania grafików pracy robionych w Excelu. Dodatkowym zadaniem, które wyznaczy³em sobie sam, by³o zaprojektowanie grafiku tak, aby konstrukcja by³a zbli¿ona do orygina³u, jednak wygl¹daj¹ca bardziej estetycznie i profesjonalnie. Bardzo istotnym by³o te¿ kryterium ³atwoœci w obs³udze.  
___
Na pasku szybkiego dostêpu znajduj¹ siê dwa przyciski przypisane do makr.  
![makra](https://drive.google.com/uc?export=view&id=1DI5qar2KTKf-HZO3BPw2BgRvVKvmaoLY)
Pierwszy s³u¿y do rysowania godzin za pomoc¹ input boxów.  
Drugi zapisuje wszystkie arkusze w formie pliku *.pdf*.
___
Kolejnym udogodnieniem jest zdefiniowana przezemnie funkcja LiczGodziny, która oblicza iloœæ godzin dla ka¿dego z pracowników w danym tygodniu.
![licz](https://drive.google.com/uc?export=view&id=1qYYyrHKzE4j9yRyV0Nkwac0zh0OkMGhd)Obok obliczone s¹ tak¿e godziny przepracowane w ca³ym miesi¹cu. Ze wzglêdów optymalizacyjnych postanowi³em wy³¹czyæ automatyczne obliczanie formu³. Do grafiki obok tabeli jest przypisane makro, które odœwie¿a wszystkie oblicznia w skoroszycie.  
___
Ostatni¹, ale nie mniej wa¿n¹ funkcj¹ jest mo¿liwoœæ automatycznego uzupe³niania dni w miesi¹cu.
![kalendarz](https://drive.google.com/uc?export=view&id=1-bQRePxONt1rHcFWVJ01YdBsx_9HrLRE)  
Po wybraniu miesi¹ca i roku nale¿y klikn¹æ grafikê kalendarza, a program ponumeruje dni zgodnie z kalendarzem. Zaktualizowane zostaj¹ tak¿e nazwy arkuszy.