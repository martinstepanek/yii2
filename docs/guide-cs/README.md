Příručka pro Yii 2.0
====================

Tento návod je publikován pod [Podmínkami Yii dokumentace](http://www.yiiframework.com/doc/terms/).

Všechna práva vyhrazena.

2014 (c) Yii Software LLC.


Úvod
----

* [O Yii](intro-yii.md)
* [Přechod z verze 1.1](intro-upgrade-from-v1.md)


Začínáme
--------

* [Co potřebujete vědět](start-prerequisites.md)
* [Instalace Yii](start-installation.md)
* [Spouštění aplikace](start-workflow.md)
* [První stránka](start-hello.md)
* [Práce s formuláři](start-forms.md)
* [Práce s databázemi](start-databases.md)
* [Generování kódu pomocí Gii](start-gii.md)
* [Co dále](start-looking-ahead.md)


Struktura aplikace
------------------

* [Přehled struktury aplikace](structure-overview.md)
* [Spouštěcí scripty](structure-entry-scripts.md)
* [Aplikace](structure-applications.md)
* [Komponenty aplikace](structure-application-components.md)
* [Kontrolery](structure-controllers.md)
* [Modely](structure-models.md)
* [Pohledy](structure-views.md)
* [Moduly](structure-modules.md)
* [Filtry](structure-filters.md)
* [Widgety](structure-widgets.md)
* [Assety](structure-assets.md)
* [Rozšíření](structure-extensions.md)


Zpracování požadavků
--------------------

* [Přehled zpracování požadavků](runtime-overview.md)
* [Příprava prostředí](runtime-bootstrapping.md)
* [Routování a tvorba URL](runtime-routing.md)
* [Požadavky](runtime-requests.md)
* [Odpovědi](runtime-responses.md)
* [Sessions a cookies](runtime-sessions-cookies.md)
* [Zpracování errorů](runtime-handling-errors.md)
* [Logování](runtime-logging.md)


Klíčové koncepty
----------------

* [Komponenty](concept-components.md)
* [Vlastnosti](concept-properties.md)
* [Události](concept-events.md)
* [Chování](concept-behaviors.md)
* [Konfigurace](concept-configurations.md)
* [Aliasy](concept-aliases.md)
* [Automatické načítání tříd](concept-autoloading.md)
* [Správce služeb](concept-service-locator.md)
* [Předávání závislostí](concept-di-container.md)


Práce s databázemi
------------------

* [Database Access Objects](db-dao.md): Připojení k databázi, základní dotazy, transakce a manipulace se schématem databáze
* [Query Builder](db-query-builder.md): Dotazování databáze pomocí jednoduché abstraktní vrstvy
* [Active Record](db-active-record.md): Aktivní záznam (ORM), načítání a manipulace se záznamy, definování vazeb 
* [Migrace](db-migrations.md): Verzovaní databáze v týmovém vývojovém prostředí
* [Sphinx](https://www.yiiframework.com/extension/yiisoft/yii2-sphinx/doc/guide)
* [Redis](https://www.yiiframework.com/extension/yiisoft/yii2-redis/doc/guide)
* [MongoDB](https://www.yiiframework.com/extension/yiisoft/yii2-mongodb/doc/guide)
* [ElasticSearch](https://www.yiiframework.com/extension/yiisoft/yii2-elasticsearch/doc/guide)


Získávání dat od uživatele
--------------------------

* [Vytváření formulářů](input-forms.md)
* [Validace vstupu](input-validation.md)
* [Nahrávání souborů](input-file-upload.md)
* [Získávání více vstupů](input-tabular-input.md)
* [Získání dat z více modelů](input-multiple-models.md)
* [Rozšiřování ActiveForm na klientově straně](input-form-javascript.md)


Zobrazování dat
---------------

* [Formátování dat](output-formatting.md)
* [Stránkování](output-pagination.md)
* [Třídění](output-sorting.md)
* [Data Providers](output-data-providers.md)
* [Widgety pro data](output-data-widgets.md)
* [Práce s kódem na straně klienta](output-client-scripts.md)
* [Témata](output-theming.md)


Zabezpečení
-----------

* [Přehled zabezpečení](security-overview.md)
* [Autentifikace](security-authentication.md)
* [Autorizace](security-authorization.md)
* [Práce s heslem](security-passwords.md)
* [Šifrování](security-cryptography.md)
* [Auth Clients](https://www.yiiframework.com/extension/yiisoft/yii2-authclient/doc/guide)
* [Best Practices](security-best-practices.md)


Caching
-------

* [Přehled cachingu](caching-overview.md)
* [Caching dat](caching-data.md)
* [Caching fragmentů](caching-fragment.md)
* [Caching stránek](caching-page.md)
* [HTTP Caching](caching-http.md)


RESTful webové služby
--------------------

* [Úvod](rest-quick-start.md)
* [Data / Zdroje](rest-resources.md)
* [Kontrolery](rest-controllers.md)
* [Routování](rest-routing.md)
* [Formátování odpovědi](rest-response-formatting.md)
* [Autentifikace](rest-authentication.md)
* [Limitování požadavků](rest-rate-limiting.md)
* [Verzování](rest-versioning.md)
* [Zpracování errorů](rest-error-handling.md)


Vývojové nástroje
-----------------

* [Debugovací panel nástrojů a Debugger](https://www.yiiframework.com/extension/yiisoft/yii2-debug/doc/guide)
* [Generování kódu pomocí Gii](https://www.yiiframework.com/extension/yiisoft/yii2-gii/doc/guide)
* [Generování API dokumentace](https://www.yiiframework.com/extension/yiisoft/yii2-apidoc)


Testování
---------

* [Přehled testování](test-overview.md)
* [Nastavení testovacího prostředí](test-environment-setup.md)
* [Unit testy](test-unit.md)
* [Testy funkčnosti](test-functional.md)
* [Akceptační testy](test-acceptance.md)
* [Nastavení proměnných](test-fixtures.md)


Speciální témata
----------------

* [Pokročilá šablona projektu](https://www.yiiframework.com/extension/yiisoft/yii2-app-advanced/doc/guide)
* [Vlastní struktura aplikace](tutorial-start-from-scratch.md)
* [Konzolové příkazy](tutorial-console.md)
* [Validace](tutorial-core-validators.md)
* [Docker](tutorial-docker.md)
* [Internacionalizace](tutorial-i18n.md)
* [Posílání emailů](tutorial-mailing.md)
* [Optimalizace rychlosti aplikace](tutorial-performance-tuning.md)
* [Sdílené prostředí](tutorial-shared-hosting.md)
* [Šablonovací nástroje](tutorial-template-engines.md)
* [Práce s kódem třetí strany](tutorial-yii-integration.md)
* [Používání Yii jako microframework](tutorial-yii-as-micro-framework.md)


Widgety
-------

* [GridView](https://www.yiiframework.com/doc-2.0/yii-grid-gridview.html)
* [ListView](https://www.yiiframework.com/doc-2.0/yii-widgets-listview.html)
* [DetailView](https://www.yiiframework.com/doc-2.0/yii-widgets-detailview.html)
* [ActiveForm](https://www.yiiframework.com/doc-2.0/guide-input-forms.html#activerecord-based-forms-activeform)
* [Pjax](https://www.yiiframework.com/doc-2.0/yii-widgets-pjax.html)
* [Menu](https://www.yiiframework.com/doc-2.0/yii-widgets-menu.html)
* [LinkPager](https://www.yiiframework.com/doc-2.0/yii-widgets-linkpager.html)
* [LinkSorter](https://www.yiiframework.com/doc-2.0/yii-widgets-linksorter.html)
* [Bootstrap Widgety](https://www.yiiframework.com/extension/yiisoft/yii2-bootstrap/doc/guide)
* [jQuery UI Widgety](https://www.yiiframework.com/extension/yiisoft/yii2-jui/doc/guide)


Pomocné nástroje
----------------

* [Přehled pomocných nástrojů](helper-overview.md)
* [ArrayHelper](helper-array.md)
* [Html](helper-html.md)
* [Url](helper-url.md)

