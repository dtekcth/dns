[![WordPress](wp-admin/images/wordpress-logo.png)](http://wordpress.org/)\
Version 3.5 (Svensk) {#logo}
==========================================================================

Några ord att börja med
=======================

Välkommen. WordPress är ett väldigt speciellt projekt för mig. Varje
utvecklare och medarbetare deltar med något unikt till mixen, och
tillsammans skapar vi något vackert som jag är stolt att vara en del av.
Tusentals timmar har gått åt till WordPress, och vi är hängivna för att
göra det bättre för varje dag. Tack för att du gör det till en del av
din värld.

— Matt Mullenweg

Vad innebär den svenska versionen?
==================================

För att underlätta för alla svenska användare så skapar vi på [WordPress
Sverige](http://sv.wordpress.org) en svensk version av
WordPress-paketet. Detta innebär att WordPress är konfigurerat med de
svenska språkfilerna (adminpanel på svenska), temana Twenty Eleven och
Twenty Twelve är översatt till svenska och installationsinstruktionerna
är på svenska. Man är välkommen att delta med förslag på ändringar osv.
för de svenska språkfilerna i WordPress Sveriges
[forum](http://wpsv.se/forum/) eller i vår
[trac](http://wpsv.se/tracker/).

De svenska paketen kan hittas på [WordPress Sverige](http://wpsv.se) och
på [sv.wordpress.org](http://sv.wordpress.org).

— Mattias Tengblad, WordPress Sverige

Installation: Den berömda 5-minutersinstallationen
==================================================

1.  Packa upp paketet i en tom mapp och ladda upp allt till servern.
2.  Gå till &lt;url-till-din-installation&gt;<span
    class="file">[/wp-admin/install.php](wp-admin/install.php)</span> i
    din webbläsare. Fyll i dina uppgifter och klicka dig vidare. Detta
    bör skapa en `wp-config.php`-fil med inställningar
    för databasanslutningen.
    1.  Om det av någon anledning inte skulle fungera, oroa dig inte.
        Det fungerar inte på alla webbhotell. Öppna filen
        `wp-config-sample.php` med en textredigerare så som t.ex WordPad
        eller liknande och fyll sedan i dina databasuppgifter.
    2.  Spara filen som `wp-config.php` och ladda upp den.
    3.  Gå till &lt;url-till-din-installation&gt;/<span
        class="file">[wp-admin/install.php](wp-admin/install.php)</span>
        i din webbläsare.

    Om det uppstår problem, dubbelkolla din <span
    class="file">`wp-config.php`</span> fil så att alla
    uppgifter stämmer. Försök sedan igen. Om det fortfarande uppstår
    problem så kan du besöka [WordPress Sverige](http://wpsv.se) för att
    få svensk support. Alternativt besök den officiella webbplatsen och
    dess [support forum](http://wordpress.org/support/).
3.  När din konfigurationsfil har skapats så kommer installeraren att
    skapa de databastabeller som krävs. Om du får felmeddelanden,
    dubbelkolla uppgifterna i din `wp-config.php` och försök igen. Har
    du fortfarande problem så kan du med så mycket information som
    möjligt om felet besöka det officiella
    [supportforumet](http://wordpress.org/support/ "WordPress support") (engleska)
    eller [WordPress Sverige](http://wpsv.se) för att få hjälp.
4.  **Om du inte angivit något lösenord, notera lösenordet som visas
    vid installationen.** Angav du inget så är ditt användarnamn
    `admin`.
5.  Installationen bör sedan skicka dig till
    [inloggningssidan](wp-login.php). Logga in med det användarnamn och
    lösenord du angav vid installationen. Om ett lösenord genererades
    automatiskt så kan du klicka på 'Profil' för att ändra lösenordet.

Uppdatering
===========

Automatisk uppdatering
----------------------

Om du uppdaterar från 2.7 eller senare så kan du använda den automatiska
uppdateringen:

1.  Gå till &lt;url-till-din-installation&gt;/<span
    class="file">[wp-admin/update-core.php](wp-admin/update-core.php)</span>
    i din webbläsarein och följ instruktionerna.
2.  Ville du ha mer att göra kanske? Men det var allt!

Manuell uppdatering
-------------------

1.  Innan du uppdaterar försäkra dig om att du har tagit backup av filer
    du modifierat så som t.ex `index.php`, teman och andra filer.
2.  Radera dina gamla WordPress-filer och spara de du modifierat.
3.  Ladda upp de nya filerna på servern (förslagsvis via FTP).
4.  Gå till &lt;url-till-din-installation&gt;<span
    class="file">[/wp-admin/upgrade.php](wp-admin/upgrade.php) i
    din webbläsare.</span>
5.  Ville du ha mer att göra kanske? Men det var allt!

Ändringar för temamallar
------------------------

Om du har modifierat dina temamallar så kan du behöva genomföra
ändringar mellan huvudversioner av WordPress.

Migrering från andra system
===========================

WordPress kan [importera från ett flertal olika
system](http://codex.wordpress.org/Importing_Content). Innan du kan
använda WordPress [verktyg för att importera
innehåll](wp-admin/import.php "Importera till WordPress") så behöver du
installera WordPress som beskrivet ovan.

Systemkrav
==========

-   [PHP](http://php.net/) version **5.2.4** eller senare.
-   [MySQL](http://www.mysql.com/) version **5.0** eller senare.

Systemrekommendationer
----------------------

-   Apache modulen
    [mod\_rewrite](http://httpd.apache.org/docs/2.2/mod/mod_rewrite.html).
-   En länk till [http://wordpress.org](http://wordpress.org/) på
    din webbplats.

Onlineresurser
==============

Om du har frågor om något som inte tagits upp i detta dokument så kan du
ta del av någon av alla de WordPress resurser som finns att tillgå
online:

[WordPress Sverige](http://wpsv.se/)
:   Den officiella svenska portalen. WordPress Sverige
    tillhandahåller bl.a. dom officiella svenska språkfilerna. Här
    hittar du även översättningar till många tillägg och teman. Besök
    forumet för support.

[WordPress Codex](http://codex.wordpress.org/) (engelska)
:   Codex är den officiella dokumentationen för allt vad
    WordPress innebär.

[The WordPress Blog](http://wordpress.org/news/) (engelska)
:   Detta är bloggen där alla nyheter om WordPress utveckling postas.
    Som standard så finns detta flöde med i WordPress adminpanel.

[WordPress Planet](http://planet.wordpress.org/) (engelska)
:   WordPress Planet är en nyhetsportal för inlägg om WordPress runt om
    på webben.

[WordPress Support Forum](http://wordpress.org/support/) (engelska)
:   Det officiella supportforumet för WordPress.

[WordPress IRC-kanal](http://codex.wordpress.org/IRC) (engelska)
:   Till sist så finns det även en chat för oss som använder WordPress.
    ([irc.freenode.net \#wordpress](irc://irc.freenode.net/wordpress))

XML-RPC och Atom-gränssnitt
===========================

Du kan posta innehåll i din WordPressblogg med verktyg som [Windows Live
Writer](http://download.live.com/writer),
[Ecto](http://illuminex.com/ecto/), [w.bloggar](http://bloggar.com/),
[Radio Userland](http://radio.userland.com/) (vilket betyder att du kan
använda Radio's email-to-blog funktion),
[NewzCrawler](http://www.newzcrawler.com/), och andra verktyg som har
stöd för blogg APIs! :) Du kan läsa mer om [XML-RPC stöd i
Codex](http://codex.wordpress.org/XML-RPC_Support).

Inlägg via E-post
=================

Du kan posta inlägg från en e-postklient! För att konfigurera detta gå
till Inställningar-&gt;Skriva och ange inställningar för ditt hemliga
POP3-konto. Sedan behöver du ställa in `wp-mail.php` att köras periodvis
för att kolla inkorgen efter nya inlägg. Detta kan du göra genom att
använda "[Cron](http://en.wikipedia.org/wiki/Cron)-jobs", eller om ditt
webbhotell inte tillåter det så kan du kolla in de olika
sidövervakningstjänsterna som finns för att låta dem kolla din
`wp-mail.php` URL.

Att post inlägg är enkelt: Alla mail skickade till adressen du angett
kommer att postas i din blogg, med ämne som titel. Det är med andra ord
bra att hålla e-postadressen hemlig. WP-mail raderar automatiskt mail
som har postas från inkorgen.

Användarroller
==============

Vi introducerade ett väldigt flexibelt rollsystem i version 2.0. Du kan
[läsa allt om användarroller och dess egenskaper i
Codex](http://codex.wordpress.org/Roles_and_Capabilities).

Slutord
=======

-   Om du har några förslag, idéer, kommentarer eller om du (gäsp!)
    hittat en bugg, besök det officiella
    [supportforumet](http://wordpress.org/support/) (engelska).
-   WordPress har ett robust API för tillägg som gör utveckling av
    kodbasen väldigt enkel. Om du är en utvecklare som är intresserad av
    att använda detta, besök [dokumentation för tillägg i
    Codex](http://codex.wordpress.org/Plugin_API). Du bör inte modifiera
    huvudfilerna för WordPress.

Dela med dig av kärleken!
=========================

WordPress har ingen marknadskampanj för miljoner eller stora sponsorer,
men vi har något ännu bättre—dig. Om du gillar WordPress fundera på att
tipsa en vän, hjälp någon mindre kunnig att installera WordPress eller
skriv en artikel om oss.

WordPress är den officiella fortsättningen av
[b2/cafélog](http://cafelog.com/), som skapades av Michel V. Utveckling
har fortsatts av [WordPress-utvecklarna](http://wordpress.org/about/).
Om du vill stödja WordPress, fundera på att göra en
[donering](http://wordpress.org/donate/).

Licens
======

WordPress är fri programvara som släpps under licensen GPL version 2
eller (enligt eget tycke) någon senare version. Se
[license.txt](license.txt) *(På svenska
[licens-sv\_SE.txt](licens-sv_SE.txt))*.
