TWO DISTANCES INTERSECTION PLUGIN FOR QGIS APPLICATION

The plugin allows you get the intersection of two distances (2D Cartesian) and is created with QGIS 3.28 application.

It installs one button. This is 2D tool and it does not take Z into account. You can run it by clicking on the button. You indicate two distances like you were drawing circles (a left click then a right click). If they have two intersections you can point one. The intersection (result) is shown depending on the layer geometry. On point layer it will be a point, on line layer two line segments and on polygon layer a triangle. When using the plugin and want to enter distances by numbers, display the Advanced Digitizing panel from Panels in View menu in QGIS.

To install the plugin from github, download the project as a zip file (click 1.0.14 link below Releases and then Source code (zip)). Run QGIS application. Click the Plugins menu, then Manage and Install Plugins... (wait for a moment here or break fetching list of plugins), next Install from ZIP. Then select the downloaded zip file and click Install Plugin button.

After installing the plugin, help is available in the Help menu, Plugins.

Note 1: Not all coordinate systems (CRS) allow you to enter a distance in the advanced digitization panel. The tool is useful for working with flat coordinate systems, for example for Poland EPSG:2176, EPSG:2177, EPSG:2178, EPSG:2179.

Note 2: After each using the plugin, measure the designated distances with the qgis measurement tool to see the precision is sufficient for you.

Version 1.0.14. RUN RUN ! GOOD LUCK !

Short video:
![Two-distances-intersection-plugin](first_look.gif)

[PL]
PRZECIĘCIE DWÓCH ODLEGŁOŚCI WTYCZKA DO APLIKACJI QGIS

Wtyczka pozwala uzyskać przecięcie dwóch odległości (kartezjańskich 2D) i jest utworzona za pomocą aplikacji QGIS 3.28.

Instaluje jeden przycisk. To jest narzędzie 2D i nie uwzględnia współrzędnej Z. Można je uruchomić klikając na przycisk. Wskazujesz dwie odległości tak, jakbyś rysował okręgi (kliknięcie lewym przyciskiem myszy, a następnie kliknięcie prawym przyciskiem myszy). Jeśli mają dwa przecięcia, możesz wskazać jedno. Przecięcie (wynik) zostanie pokazane w zależności od geometrii warstwy. W warstwie punktowej będzie to punkt, w warstwie linii dwa odcinki, a w warstwie wielokąta trójkąt. Jeśli używasz wtyczki i chcesz wprowadzać odległości liczbowo, wyświetl panel Zaawansowana digitalizacja z menu Panele w menu Widok w QGIS.

Aby zainstalować wtyczkę z githuba, pobierz projekt jako plik ZIP (kliknij link 1.0.14 poniżej Releases, a następnie Source code (zip)). Uruchom aplikację QGIS. Kliknij menu Wtyczki, następnie Zarządzaj i instaluj wtyczki... (poczekaj chwilę tutaj lub przerwij pobieranie listy wtyczek), następnie Instaluj z pliku ZIP. Następnie wybierz pobrany plik zip i kliknij przycisk Zainstaluj wtyczkę.

Po zainstalowaniu wtyczki pomoc dostępna jest w menu Pomoc, Wtyczki.

Uwaga 1: Nie wszystkie układy współrzędnych (CRS) pozwalają na wprowadzenie odległości w panelu zaawansowanej digitalizacji. Narzędzie jest przydatne do pracy z płaskimi układami współrzędnych, np. dla Polski EPSG:2176, EPSG:2177, EPSG:2178, EPSG:2179.

Uwaga 2: Po każdym użyciu wtyczki zmierz wyznaczone odległości narzędziem pomiarowym qgis, aby sprawdzić, czy precyzja jest dla Ciebie wystarczająca.

Wersja 1.0.14 BIEGNIJ BIEGNIJ ! POWODZENIA !
