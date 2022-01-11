Jesli udalo ci sie przetrwac 5-cio czesciowy wyklad na temat "partycji" pamieci flash, to coz... gratuluje. Mnie zajelo to bardzo dlugo. Ze wzgledu na robienie notatek, wyluskiwanie z paplaniny istotnej tresci i przegladanie kodu samemu.

Na otarcie lez - mala sciaga, ktora sobie zrobilem, abym nie musial przechodzic tej meki kiedys jeszcze raz :)

Zeby nie bylo, ze sie wylacznie czepiam - doceniam fakt, ze Mirkowi musialo zajac ogrom czasu, aby te wszystkie elementy pozbierac w calosc. I za to szacuneczek. Natomiast na koncu trzeba bylo nagrac te lekcje, obejrzec, zrobic skrypt, przygotowac lepsze wizualnie materialy, skasowac nagranie i nagrac jeszcze raz - bez pomylek, bez zbednego gadania. Warto by lepiej zaznaczyc kilka rzeczy, ktore w dokumentacji Espressifa nie do konca trzymaja sie kupy (jak to, ze adresy tych malych obszarow na koncu nie zgadzaja sie z ich podanymi wielkosciami).

Plik pdf z nota nie jest zabezpieczony i pozwala na dodawanie komentarzy i pokreslen. Co wiecej - zgodnie z licencja https://github.com/espressif/ESP8266_NONOS_SDK/blob/master/License tak kod, jak i dokumentacje SDK jest Open Source. Kupno licencji na Adobe Acrobat chyba nie spowodowaloby bankructwa firmy Atnel i mozna by kilka bledow w tych dokumentach poprawic. Bo juz wykorzystywanie ich fragmentow we wlasnej dokumentacji bez zaznaczenia zrodla jest sliskie z prawnego punktu widzenia.

Jedna mala uwaga - nie wydaje sie byc to problem - ale nota ma zalecenie:

In general, ESP Flash Download Tool can be used to download firmware into flash. It is recommended that the user start from the lower bits when downloading the firmware. 

wiec kolejne obszary powinno sie wpisywac do FDT w takiej kolejnosci, w jakiej beda ukladane, a nie jak sie podoba. Nie mam juz dzisiaj zdrowia to testowania, co sie stanie jesli sprobuje sie zaladowac zbyt duza binarke jak na przewidziane w mapie miejsce. Byc moze jest tam jakies zabezpieczenie, ktore tylko wtedy wywola blad, zamiast nadpisac czesc kodu.
