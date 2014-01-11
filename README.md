<!DOCTYPE html>
<html>
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# githubog: http://ogp.me/ns/fb/githubog#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>rdyrda/labsp</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub" />
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub" />
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png" />
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png" />
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png" />
    <link rel="logo" type="image/svg" href="https://github-media-downloads.s3.amazonaws.com/github-logo.svg" />
    <meta property="og:image" content="https://github.global.ssl.fastly.net/images/modules/logos_page/Octocat.png">
    <meta name="hostname" content="github-fe118-cp1-prd.iad.github.net">
    <meta name="ruby" content="ruby 2.1.0p0-github-tcmalloc (60139581e1) [x86_64-linux]">
    <link rel="assets" href="https://github.global.ssl.fastly.net/">
    <link rel="conduit-xhr" href="https://ghconduit.com:25035/">
    <link rel="xhr-socket" href="/_sockets" />
    


    <meta name="msapplication-TileImage" content="/windows-tile.png" />
    <meta name="msapplication-TileColor" content="#ffffff" />
    <meta name="selected-link" value="repo_source" data-pjax-transient />
    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="594714D9:06F2:C6A416E:52D129B1" name="octolytics-dimension-request_id" /><meta content="5872601" name="octolytics-actor-id" /><meta content="reamider" name="octolytics-actor-login" /><meta content="5305766443f4c2f5b93d86854f6215571fde3067191ca8a84bd6ce84e5a9f588" name="octolytics-actor-hash" />
    

    
    
    <link rel="icon" type="image/x-icon" href="/favicon.ico" />

    <meta content="authenticity_token" name="csrf-param" />
<meta content="EXE1gxXasPA+BxYAnfHFq5YN4OIgj/kkxBzJ+uQrLGM=" name="csrf-token" />

    <link href="https://github.global.ssl.fastly.net/assets/github-e0318ec03abae32f266109d4e5ecb65a0ec7ab19.css" media="all" rel="stylesheet" type="text/css" />
    <link href="https://github.global.ssl.fastly.net/assets/github2-cb9092efb14f24f935f2ceaa5e139d61b58daec1.css" media="all" rel="stylesheet" type="text/css" />
    

    

      <script src="https://github.global.ssl.fastly.net/assets/frameworks-d4d23eefcbed557582cde6209ccd824fb98255d8.js" type="text/javascript"></script>
      <script src="https://github.global.ssl.fastly.net/assets/github-2a93856bd56c545b500393f229515bfcb515f71c.js" type="text/javascript"></script>
      
      <meta http-equiv="x-pjax-version" content="b642137d481deb5aea0154fc9e20903f">

        <meta property="og:title" content="labsp"/>
  <meta property="og:type" content="githubog:gitrepository"/>
  <meta property="og:url" content="https://github.com/rdyrda/labsp"/>
  <meta property="og:image" content="https://github.global.ssl.fastly.net/images/gravatars/gravatar-user-420.png"/>
  <meta property="og:site_name" content="GitHub"/>
  <meta property="og:description" content="labsp - Laboratorium ze Środowiska Programisty 2012/13"/>

  <meta name="description" content="labsp - Laboratorium ze Środowiska Programisty 2012/13" />

  <meta content="2733154" name="octolytics-dimension-user_id" /><meta content="rdyrda" name="octolytics-dimension-user_login" /><meta content="6558276" name="octolytics-dimension-repository_id" /><meta content="rdyrda/labsp" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="false" name="octolytics-dimension-repository_is_fork" /><meta content="6558276" name="octolytics-dimension-repository_network_root_id" /><meta content="rdyrda/labsp" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/rdyrda/labsp/commits/master.atom" rel="alternate" title="Recent Commits to labsp:master" type="application/atom+xml" />

  </head>
<body>
<a name="laboratorium-1" class="anchor" href="#laboratorium-1"><span class="octicon octicon-link"></span></a>Laboratorium 1</h1>

<p>Zad.1 Używając linii poleceń stwórz strukturę katalogów:</p>

<p>temp
|-- dom
|-- nauka
|   |-- c
|   |-- logo
|   <code>-- pascal
</code>-- praca
    |-- dokumenty
    <code>-- zlecenia
        |-- niezrealizowane
</code>-- zrealizowane</p>

<div class="highlight highlight-sh"><pre>ODP. mkdir -p temp/dom
     mkdir -p temp/nauka/<span class="o">{</span>c,logo,pascal<span class="o">}</span>
     mkdir -p temp/praca/<span class="o">{</span>dokumenty,zlecenia<span class="o">}</span>
     mkdir -p temp/praca/zlecenia/<span class="o">{</span>niezrealizowane,zrealizowane<span class="o">}</span>
     <span class="nb">cd </span>temp <span class="p">|</span> tree
</pre></div>

<p>Zad.2 Przejdź do katalogu dom i utwórz katalog wazne-sprawy.</p>

<div class="highlight highlight-sh"><pre>ODP. <span class="nb">cd </span>dom
     mkdir wazne-sprawy
</pre></div>

<p>Zad.3 Wejdź do katalogu wazne-sprawy i utwórz tam pusty plik rachunki.txt.</p>

<div class="highlight highlight-sh"><pre>ODP. <span class="nb">cd </span>wazne-sprawy
     touch rachunki.txt
</pre></div>

<p>Zad.4 Będąc w katalogu wazne-sprawy skopiuj plik rachunki.txt do katalogu zrealizowane.</p>

<div class="highlight highlight-sh"><pre>ODP. cp rachunki.txt ../../praca/zlecenia/zrealizowane/rachunki.txt
</pre></div>

<p>Zad.5 Przejdź do katalogu zrealizowane i zmień nazwę pliku rachunki.txt na wykonano.txt.</p>

<div class="highlight highlight-sh"><pre>ODP. <span class="nb">cd</span> ../..
     <span class="nb">cd </span>praca/zlecenia/zrealizowane
     mv rachunki.txt wykonano.txt
</pre></div>

<p>Polecenia: split, cat, diff</p>

<p>Zad.6 Utwórz plik wykonano.txt wielkości 11 bajtów, następnie podziel go pliki wielkości 5 bajtów. W ten sposób otrzymasz 3 pliki. (split)</p>

<div class="highlight highlight-sh"><pre>ODP. cat &gt; wykonano.txt 
    12345678901 <span class="o">(</span>potem wcisnąć Ctrl+D<span class="o">)</span>
    split -b 5 wykonano.txt
</pre></div>

<p>Zad.7 Będąc w katalogu logo skopiuj powyżej otrzymane 3 pliki do katalogu dokumenty.</p>

<div class="highlight highlight-sh"><pre>ODP. cp ../../praca/zlecenia/zrealizowane/x* ../../praca/dokumenty
</pre></div>

<p>Zad.8 Będąc w katalogu dokumenty połącz skopiowane 3 pliki w plik odtworzono.txt, tak aby otrzymać plik o zawartości identycznej z wykonano.txt. Następnie plik odtworzono.txt skopiuj do katalogu wazne-sprawy.</p>

<div class="highlight highlight-sh"><pre>ODP. cat xaa xab xac &gt; odtworzono.txt
     cp odtworzono.txt ../../dom/wazne-sprawy/odtworzono.txt
</pre></div>

<p>Zad.9 Będąc w katalogu wazne-sprawy sprawdź, czy są jakieś różnice w zawartości plików wykonano.txt i odtworzono.txt.</p>

<div class="highlight highlight-sh"><pre>ODP. diff -a ../../praca/zlecenia/zrealizowane/wykonano.txt odtworzono.txt
</pre></div>

<p>Zad.10 Wyświetl kalendarz na październik 2009 r. (cal)</p>

<div class="highlight highlight-sh"><pre>ODP. cal 10 2009
</pre></div>

<p>Wyświetl kalendarz na wrzesień, październik i listopad 2009 r. z miesiącami obok siebie (cal):</p>

<div class="highlight highlight-sh"><pre>ODP. cal -3 2009
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cal 11 2009 -3m
</pre></div>

<p>Zad.11 Jaki był dzień tygodnia 25 maja 1975 r. (cal i date)</p>

<div class="highlight highlight-sh"><pre>ODP. date -d 1975-05-25 +%A
</pre></div>

<h1>
<a name="laboratorium-2" class="anchor" href="#laboratorium-2"><span class="octicon octicon-link"></span></a>Laboratorium 2</h1>

<p>Zad.1 Wyświetl na ekran 2 pierwsze wiersze pliku program.c. (head)</p>

<div class="highlight highlight-sh"><pre>ODP. head -n 2 program.c
</pre></div>

<p>Zad.2 Wyświetl na ekran 4 ostatnie wiersze pliku program.c. (head,tail)</p>

<div class="highlight highlight-sh"><pre>ODP. tail -n 4 program.c
</pre></div>

<p>Zad.3 W pliku program.c znajdź wszystkie wiersze z wystąpieniem słowa „main”. (grep)</p>

<div class="highlight highlight-sh"><pre>ODP. grep <span class="s2">"main"</span> program.c
</pre></div>

<p>Zad.4 Plikowi program.c nadaj następujące uprawnienia: właściciel – czytanie, pisanie, grupa – czytanie, pozostali użytkownicy: brak uprawnień. (chmod)</p>

<div class="highlight highlight-sh"><pre>ODP. chmod 650 program.c
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. chmod u+rw program.c
     chmod g+r program.c
     chmod o-rwx program.c
</pre></div>

<p>Zad.5 Będąc w katalogu temp przenieś katalog wazne-sprawy do katalogu praca.</p>

<div class="highlight highlight-sh"><pre>ODP. mv dom/wazne-sprawy praca/wazne-sprawy
</pre></div>

<p>Zad.6 Zarchiwizuj cały katalog temp. (zip i tar)</p>

<div class="highlight highlight-sh"><pre>ODP. tar -cvf temp.tar temp
     gzip temp.tar
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. zip -r temp.zip temp
</pre></div>

<p>Zad.7 Usuń katalog temp.</p>

<div class="highlight highlight-sh"><pre>ODP. rm -rf temp
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. rm -R temp
</pre></div>

<p>Zad.8 Odtwórz z archiwum katalog temp. (unzip i tar)</p>

<div class="highlight highlight-sh"><pre>ODP. tar -zxf temp.tar.gz
     unzip temp.zip
</pre></div>

<p>Zad.9 Posprzątaj na swoim koncie.</p>

<div class="highlight highlight-sh"><pre>ODP. <span class="nb">cd</span> ~/tmp
     rm -rf *
</pre></div>

<h1>
<a name="laboratorium-3" class="anchor" href="#laboratorium-3"><span class="octicon octicon-link"></span></a>Laboratorium 3</h1>

<p>Zad.1 Wyświetl plik /etc/passwd z podziałem na strony przyjmując, że strona na 5 linii tekstu.</p>

<div class="highlight highlight-sh"><pre>ODP. more -5 /etc/passwd
</pre></div>

<p>Zad.2 Korzystając z polecenia cat utwórz plik tekst3.txt, który będzie składał się z zawartości pliku tekst1.txt, ciągu znaków podanego ze standardowego wejścia (klawiatury) i pliku tekst2.txt.</p>

<div class="highlight highlight-sh"><pre>ODP. cat tekst1.txt - tekst2.txt &gt; tekst3.txt
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cat tekst1.txt &gt; tekst3.txt
     cat &gt;&gt; tekst3.txt
     cat tekst2.txt &gt;&gt; tekst3.txt
</pre></div>

<p>Zad.3 Wyświetl po 5 pierwszych linii wszystkich plików w swoim katalogu domowym w taki sposób, aby nie były wyświetlane ich nazwy.</p>

<div class="highlight highlight-sh"><pre>ODP. head <span class="nv">$HOME</span>/* -n 5 -q
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. head -qn 5 *
</pre></div>

<p>Zad.4 Wyświetl linie o numerach 3, 4 i 5 z pliku /etc/passwd.</p>

<div class="highlight highlight-sh"><pre>ODP. head -n 5 /etc/passwd <span class="p">|</span> tail -n 3
</pre></div>

<p>Zad.5 Wyświetl linie o numerach 7, 6 i 5 od końca pliku /etc/passwd.</p>

<div class="highlight highlight-sh"><pre>ODP. tail -n 7 /etc/passwd <span class="p">|</span> head -n 3 
</pre></div>

<p>Zad.6 Wyświetl zawartość pliku /etc/passwd w jednej linii.</p>

<div class="highlight highlight-sh"><pre>ODP. cat /etc/passwd <span class="p">|</span> tr <span class="s2">"n"</span> <span class="s2">" "</span>
</pre></div>

<p>Zad.7 Za pomocą filtru tr wykonaj modyfikację pliku plik.txt, polegającą na umieszczeniu każdego słowa w osobnej linii.</p>

<div class="highlight highlight-sh"><pre>ODP. cat plik.txt <span class="p">|</span> tr <span class="s2">" \t"</span> <span class="s2">"\n"</span>
</pre></div>

<p>Zad.8 Zlicz wszystkie pliki znajdujące się w katalogu /etc i jego podkatalogach. </p>

<div class="highlight highlight-sh"><pre>ODP. find /etc -type f 2&gt; dev/null/ wc -l
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find /etc -type f 2&gt; errors <span class="p">|</span> wc -l
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find /etc -type f -follow <span class="p">|</span> wc -l
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. head -n 0 /etc/* <span class="p">|</span> tr -s <span class="s1">'[n*2]'</span> <span class="s1">'n'</span> <span class="p">|</span> wc -l
</pre></div>

<p>Zad.9 Napisać polecenie zliczające ilość znaków z pierwszych trzech linii pliku /etc/passwd.</p>

<div class="highlight highlight-sh"><pre>ODP. find /etc/ <span class="p">|</span> head -3 <span class="p">|</span> wc <span class="p">|</span> tr <span class="s1">'''\n'</span> <span class="p">|</span> tail -1
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find /etc/ <span class="p">|</span> head -3 <span class="p">|</span> wc -c
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cat /etc/passwd/ <span class="p">|</span> head -n 3 <span class="p">|</span> wc -m
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. head /etc/passwd -n 3 <span class="p">|</span> wc -c
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cut /etc/passwd <span class="p">|</span> head -n 3 <span class="p">|</span> wc -n
</pre></div>

<h1>
<a name="laboratorium-4" class="anchor" href="#laboratorium-4"><span class="octicon octicon-link"></span></a>Laboratorium 4</h1>

<p>Zad.1 Wyświetl listę plików z aktualnego katalogu, zamieniając wszystkie małe litery na duże.</p>

<div class="highlight highlight-sh"><pre>ODP. ls <span class="p">|</span> tr <span class="o">[</span>:lower:<span class="o">]</span> <span class="o">[</span>:upper:<span class="o">]</span> <span class="o">(</span>nie obsługuje znaków narodowych<span class="o">)</span>
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. ls <span class="p">|</span> tr a-z A-Z
</pre></div>

<p>dla polskich liter:</p>

<div class="highlight highlight-sh"><pre>ODP. ls <span class="p">|</span> tr <span class="o">[</span>:lower:<span class="o">]</span>ąęćłóśżź <span class="o">[</span>:upper:<span class="o">]</span>ĄĘĆŁÓŚŻŹ
</pre></div>

<p>Zad.2 Wyświetl listę praw dostępu do plików w aktualnym katalogu, ich rozmiar i nazwę.</p>

<div class="highlight highlight-sh"><pre>ODP. ls -l <span class="p">|</span> awk <span class="s1">'{print $1,$5,$9}'</span>
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find . -type f -exec ls -l <span class="s1">'{}'</span> <span class="s1">';'</span> <span class="p">|</span> cut -d <span class="s1">' '</span> -f1,5,9 <span class="o">(</span>nie działa dla plików z datami dwucyfrowymi<span class="o">)</span>
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. ls --format<span class="o">=</span>long --human-readable
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find . -printf <span class="s2">"Plik: %f Rozmiar: %s Prawa: %M \n"</span> -maxdepth 1
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. ls -l <span class="p">|</span> cut --byes<span class="o">=</span>1-10,29-33,46-
</pre></div>

<p>Zad.3 Wyświetl listę plików w aktualnym katalogu, posortowaną według rozmiaru pliku.</p>

<div class="highlight highlight-sh"><pre>ODP. ls -l <span class="p">|</span> sort -k5,5
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. ls -lrS
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find . -maxdepth 1 -not - <span class="nb">type </span>d -exec ls -l <span class="s1">'{}'</span> <span class="s1">';'</span> <span class="p">|</span> sort -n -t <span class="s1">' '</span> -k6,6
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. ls --sort<span class="o">=</span>size -1
</pre></div>

<p>Zad.4 Wyświetl zawartość pliku /etc/passwd posortowaną według numerów UID w kolejności od największego do najmniejszego.</p>

<div class="highlight highlight-sh"><pre>ODP. cat /etc/passwd <span class="p">|</span> sort -n -t <span class="s1">':'</span> -k3,3
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. sort -t : -n -k3 -r /etc/passwd
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cat /etc/passwd <span class="p">|</span> sort -r -t: -g -k 3
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. sort -t : -k3 -nr /etc/passwd
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cat /etc/passwd/ <span class="p">|</span> sort --reverse --general-numeric-sort
</pre></div>

<p>Zad.5 Wyświetl zawartość pliku /etc/passwd posortowaną najpierw według numerów GID w kolejności od największego do najmniejszego, a następnie UID.</p>

<div class="highlight highlight-sh"><pre>ODP. sort -t : -k4 -r /etc/passwd <span class="p">|</span> sort -t : -k3 
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cat /etc/passwd <span class="p">|</span> sort --field-separator<span class="o">=</span><span class="s2">":"</span> 
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cat /etc/passwd <span class="p">|</span> sort -r --field-separator<span class="o">=</span><span class="s2">":"</span> -g -k 4,3
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. cat /etc/passwd <span class="p">|</span> sort --field-separator<span class="o">=</span><span class="s2">":"</span> --general-numeric-sort --key 4,3 --reverse
</pre></div>

<p>Zad.6 Podaj liczbę plików każdego użytkownika.</p>

<div class="highlight highlight-sh"><pre>ODP. find <span class="nv">$HOME</span> -not -type d <span class="p">|</span> wc -l
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find / -printf <span class="s2">"%u\n"</span> 2&gt; /dev/null <span class="p">|</span> sort <span class="p">|</span> uniq -c
</pre></div>

<p>Zad.7 Sporządź statystykę praw dostępu (dla każdego z praw dostępu podaj ile razy zostało ono przydzielone).</p>

<div class="highlight highlight-sh"><pre>ODP. find -printf <span class="s2">"%m\n"</span> <span class="p">|</span> sort <span class="p">|</span> uniq -c
</pre></div>

<p>Zad.8 Efekt wykonania poniższych poleceń?</p>

<p>1) ls -l &gt; lsout.txt </p>

<div class="highlight highlight-sh"><pre>ODP. Utwotrzenie pliku lsout.txt i wypelnienie jej lista plikow w akutalnym katalogu
</pre></div>

<p>2) ls -la &gt;&gt; lsout.txt</p>

<div class="highlight highlight-sh"><pre>ODP. Dopisuje <span class="k">do </span>pliku lsout.txt liste uruchomionych procesów
</pre></div>

<p>3) ps &gt;&gt; psout.txt</p>

<div class="highlight highlight-sh"><pre>ODP. Dopisuje ilosc wolnej pamięci
</pre></div>

<h1>
<a name="laboratorium-5" class="anchor" href="#laboratorium-5"><span class="octicon octicon-link"></span></a>Laboratorium 5</h1>

<p>Zad.1 Znajdź w swoim katalogu domowym (bez podkatalogów) wszystkie pliki, które zostały zmodyfikowane w ciągu ostatnich dziesięciu dni i wyświetl ich nazwy.</p>

<div class="highlight highlight-sh"><pre>ODP. find ~/ -maxdepth 1 -mtime -10 -type f <span class="o">(</span>maxdepth podać pierwsze w kolejności<span class="o">)</span>
</pre></div>

<p>Zad.2 Znajdź wszystkie pliki zwykłe w systemie, które mają w nazwie ciąg znaków „conf” i wyświetl ich nazwy na ekranie.</p>

<div class="highlight highlight-sh"><pre>ODP. find  /etc -name <span class="se">\*</span>config<span class="se">\*</span> -type f 2&gt; /dev/null
</pre></div>

<p>Zad.3 Znajdź w swoim katalogu domowym wszystkie pliki, które nie były używane w ciągu ostatnich 20 dni.</p>

<div class="highlight highlight-sh"><pre>ODP. find ~/ <span class="se">\(</span> -type d -name <span class="s2">".git"</span> -prune <span class="se">\)</span> -o <span class="se">\(</span> -type f -print <span class="se">\)</span> 
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find ~/ -atime 20 <span class="o">(</span>nie <span class="k">do </span>końca<span class="o">)</span>
</pre></div>

<p>lub </p>

<div class="highlight highlight-sh"><pre>ODP. find . -path <span class="s1">'*/.git/*'</span> - prune -o -print
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. -mtime -20 <span class="p">|</span> egrep -v <span class="s1">'/\.git'</span> <span class="o">(</span>praktyczniejsza wersja z mtime<span class="o">)</span>
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find . ! -regex <span class="s2">".*/\.git/?.*"</span>
</pre></div>

<p>Zad.4 Znajdź w katalogu /etc wszystkie niepuste podkatalogi i pliki o nazwach zaczynających się na literę „a”.</p>

<div class="highlight highlight-sh"><pre>ODP. find /etc <span class="se">\(</span> -type f -and -name a* <span class="se">\)</span> -or <span class="se">\(</span> -type d -and ! -empty <span class="se">\)</span> 2&gt; /dev/null <span class="o">(</span>nie działa <span class="k">do </span>końca - w podkatalogach nie wyznacza plików rozpoczynających się na <span class="s2">"a"</span><span class="o">)</span>
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find /etc<span class="se">\(</span>-type d -and ! empty<span class="se">\)</span> -or <span class="se">\(</span>-type f -and -name a*<span class="se">\)</span> 2&gt; /dev/null
</pre></div>

<p>Zadania różne</p>

<p>Zad.5 Z bieżącego katalogu usuń pliki, których nazwa zaczyna się na literę „x” i zawiera dokładnie trzy znaki.</p>

<div class="highlight highlight-sh"><pre>ODP. rm x?? <span class="o">(</span>dotyczy bieżącego katalogu<span class="o">)</span>
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. find. -minidepth 2 -maxdepth 2 -name x?? -exec rm -rf <span class="se">\(\)</span> <span class="se">\;</span>
</pre></div>

<p>lub </p>

<div class="highlight highlight-sh"><pre>ODP. find. -minidepth 2 -maxdepth 2 -name x?? -delete <span class="o">(</span>jest krótsze<span class="o">)</span>
</pre></div>

<p>Zad.6 Skonstruuj polecenie tworzące katalog, którego nazwą będzie aktualna (w momencie wywołania) systemowa data w formacie rrrr-mm-dd.</p>

<div class="highlight highlight-sh"><pre>ODP. mkdir <span class="s1">'date +%Y-%m-%d'</span> lub mkdir <span class="k">$(</span>date +%Y-%m-%d<span class="k">)</span>
</pre></div>

<h1>
<a name="laboratorium-6" class="anchor" href="#laboratorium-6"><span class="octicon octicon-link"></span></a>Laboratorium 6</h1>

<p>Zad.1 W pliku plik.txt znajdź wiersze zawierające co najmniej jeden znak.</p>

<div class="highlight highlight-sh"><pre>ODP. grep . plik.txt
</pre></div>

<p>Zad.2 Znajdź w plikach pl* wiersze rozpoczynające się od cyfry.</p>

<div class="highlight highlight-sh"><pre>ODP. grep ^<span class="o">[</span>0-9<span class="o">]</span> pl*
</pre></div>

<p>Zad.3 Znajdź pliki, zawierające wiersz w którym na 9 pozycji występuje litera r.</p>

<div class="highlight highlight-sh"><pre>ODP. ls -1 <span class="p">|</span> grep -E <span class="s1">'^.{8}r.*'</span>
</pre></div>

<p>Zad.4 Policz, ilu użytkowników systemu używa powłoki bash (zgodnie z zapisami w pliku /etc/passwd).</p>

<div class="highlight highlight-sh"><pre>ODP. grep -c bash /etc/passwd
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. grep -c <span class="s2">"/bash$"</span> /etc/passwd
</pre></div>

<p>Zad.5 Znajdź wiersze zawierające liczby rzymskie w pliku plik.txt.</p>

<div class="highlight highlight-sh"><pre>ODP. egrep <span class="s2">"(X|D|C|M|V|L|I){1,}"</span> plik.txt
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. grep <span class="o">[</span>IVXLCDM<span class="o">]</span> plik.txt <span class="o">(</span>niedokładne<span class="o">)</span>
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. egrep -iw <span class="o">[</span>IVXLCDM<span class="o">]</span>+ plik.txt
</pre></div>

<p>lub</p>

<div class="highlight highlight-sh"><pre>ODP. egrep -i <span class="se">\\</span>b<span class="o">[</span>IVXLCDM<span class="o">]</span>+<span class="se">\\</span>b plik.txt
</pre></div>
</body>
</html>