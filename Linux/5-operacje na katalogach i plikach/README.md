1. W swoim katalogu za pomoca polecenia mkdir nazwaKatalogu utwórz katalog o nazwie ImieINazwisko
2. W katalogu który utworzyles utwórz poprzez jedno polecenie trzy podkatalogi o nazwie katalogA, katalogB i katalogC uzywajac spacji jako separatora ich tworzenia - mkdir katalog1 katalog2
3. Za pomoca polecenia mv zmien nazwe katalogu katalogC na nazwe KatalogDoUsuniecia - mv katalog1 katalog2 
4. Usun katalog o nazwie KatalogDoUsuniecia poprzez polecenie rmdir
5. W katalogu katalogB utwórz pliki o nazwie plikA, plikB, plikC i NieUsuwalny za pomoca polecenia touch
6. Do katalogu katalogB zapisz dokument o nazwie plikD utworzony w dowolnym edytorze dokumentów.
7. Zmien nazwe dokumentu plikD na plikDoUsuniecia za pomoca polecenia mv. Zmien nazwe pliku plikA na plikB. Co sie stalo w wyniku operacji? – zapisz odpowiedz dla prowadzącego. Ponownie utwórz plik o nazwie plikA a nastepnie zmien jego nazwe na plikB uzywajac najpierw atrybutu –b a nastepnie –i
8. Usun plik o nazwie plikDoUsuniecia za pomoca polecenia rm
9. Usun wszystkie pliki o nazwie rozpoczynajacej sie od plik - rm plik* w trybie interaktywnym -i
10. Spróbuj usunac katalog katalogB za pomoca polecenia rmdir. Czy mozliwe jest jego usuniecie?
11. Spróbuj usunac katalog za pomoca polecenia rm z parametrem –r. Czy operacja sie udala?
12. Ponownie utwórz katalog o nazwie katalogB z plikami o nazwach plikA, plikB, plikC. Przenies zawartosc katalogu katalogB do katalogu katalogA za pomoca polecenia mv - mv katalog1/* katalog2.
13. Skopiuj plik plikA z katalogu katalogA do katalogu katalogB za pomoca polecenia cp zmieniajac nazwe na plikTymaczasowy- cp ../katalog1/plik1 katalog2/plik2
14. Utwórz wpisujac kilka dowolnych linijek tekstu w katalogu katalogB plik tekstowy o nazwie plikDoDowiazania. Za pomoca polecenia ln utwórz odnosnik staly o nazwie plikDowiazany do pliku plikDoDowiazania - ln plik1 plik2. Sprawdz za pomoca polecenia cat zawartosc pliku plikDowiazany. Edytorem tekstowym zmien zawartosc pliku i sprawdz ponownie poleceniem cat zawartosc pliku plikDowiazany. Czy ulegla ona zmianie. Usun plik o nazwie plikDoDowiazania. Czy plik plikDowiazany nadal istnieje i wyswietla jakas zawartosc? A pomoca polecenia ln z parametrem –s dokonaj dowiazanie symboliczne do pliku plikDowiazany o nazwie plikDowiazany2 - ln -s plik1 plik2. Wykonaj operacje analogiczne jak we wczesniejszym przypadku. Czym rózni sie odnosnik staly od dowiazania symbolicznego?
