# SKN page

# Jako ze mamy robic ten projekt w kilka osób musi byc on bardzo upozadkowany i kazdy musi miec te same " Folder directories", abysmy mogli to wszystko zlaczyc w kupe i nie trwalo to wieku.

#Podpialem gulpa task runner kto nie wie o co chodzi mysle ze najlepiej nauczysz sie go wlasnie teraz:)
https://gulpjs.com/

# Plikow .gitignore,gulpfile.js i wszystkie inne na roocie prosze nie ruszac bo wszystko sie wysadzi :)

# Pracujemy w src/assets

* src/assets/fonts : fontawesome zalodowane przydadza sie moze.
* src/assets/img : tu trzymamy obrazki " backgroundy i inne..."
* src/assets/js/app.js : tu piszemy JSA
* src/assets/scss : tu piszemy style (cssy)
* folder base jak sama nazwa wskazuje
* plik "\_global.scss" jest opisany w srodku
* plik "\_variables.scss" takze
* folder partials tu umieszczamy swoje sekcje zostawilem kilka przykladowaych jak ma to wygladac kazdy plik tworzymy zaczynajac od "\_" np \_example.scss (podlogi :)
  \*ponizej znajduje sie plik style.scss ktory jest naszym glownym plikem css to to z tego pliku importujemy swoje sekcje example :
  @import "base/\_variables"; - import pliku \_variables z folderu base;
  @import "base/\_global";
  @import "partials/\_header"; import pliku \_header z folderu partials.
  @import "partials/\_navigation";
  @import "partials/\_about";

ponizej jest folder temp to tu jest wszystko wyplute i zlozena w jedna kupe w tym folderze nic nie piszemy i nic tam nie zmieniamy!
jakby kto byl ciekawy temp/css/bottstrap.css to style bootstrapa,
temp/css/font-awesome.min.css to font awesome
temp/css/style.css to nasz jeden glowny plik styli css ktore pisalismy powyze laczane sa w ten jeden wielki plik mozecie sobie zerknac jak to wyglada ale tam nic zmieniac.
to samo z folderem temp/js to jest nasz glowny folder js i to z tego jest wszystko zaciagane i podpiete do index.html
wyjasnienie
"

 <script src="temp/js/jquery.min.js"></script>

 <script src="temp/js/popper.min.js"></script>

 <script src="temp/js/bootstrap.min.js"></script>

 <script src="temp/js/app.js"></script>"

"
napisane jest moze troche chaotycznie ale w miare zrozumiale.
Jak zauwzyliscie uzywamy sass jak ktos nie wiem z czym to sie je zapraszam do zapoznania sie z https://sass-guidelin.es/pl/ pozatym mysle ze najlepiej nauczysz sie go wlasnie teraz:);
Folder node_modules to Pliki NPM dla chetnych zapraszam do zapoznania sie https://www.npmjs.com/
wszystko jest juz zaciagniete wiec kto nie che nie musi sie tym interesowac.

Teraz najwazniejsze folder node_modules jest bardzo duzy po to jest na roocie plik .gitignore zeby go nie ladowac na githuba.

#⛔Instalacja
1.instal node on your computer https://nodejs.org/en/ - recomended LTS version.
2.Open your Command Line as a superuser or administrator default windows or gitbash and type npm install -g gulp-cli
3.Then open the app folder `SKN` in your command line, and install the needed dependencies: `### Example###->> 'cd C:\Users\Piotr\Desktop\JobTask\SKN'`
4.type in Command Line npm install
5.In command line type gulp watch

w razie problemow piszcie.

Jezeli ktos ma inny pomysl na naz workFlow to piszcie;

Ps jestesmy tutaj zeby sie uczyc jezli ktos nie pracowal w gulpie sassie npmach itd to wlasnie w tym momencie jest najlepszy czas zeby zaczac wrazie zego sluze swoja pomoca.
