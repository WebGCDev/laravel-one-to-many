<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## LARAVEL-AUTH

### 06-02-2024

Creiamo con Laravel il nostro sistema di gestione del nostro Portfolio di progetti.
Oggi iniziamo un nuovo progetto che si arricchirà nel corso delle prossime lezioni: man mano aggiungeremo funzionalità e vedremo la nostra applicazione crescere ed evolvere, utilizzando anche SASS.

Descrizione:
Iniziamo un nuovo progetto Laravel con autenticazione.
Iniziamo con il definire il layout, modello, migrazione, controller e rotte necessarie per il sistema PORTFOLIO:

1. Autenticazione: si parte con l'autenticazione e la creazione di un layout per back-office
2. Creazione del modello Project con relativa migrazione, seeder, controller e rotte
3. Per la parte di back-office creiamo un resource controller Admin\ProjectController per gestire tutte le operazioni CRUD dei progetti

Bonus:

Implementiamo la validazione dei dati dei Progetti nelle operazioni CRUD che lo richiedono usando due form requests.

### 07-02-2024

Completa la parte di CRUD (Create, Read, Update, Delete).

Poi, concentratevi sulla personalizzazione e migliorate la User Experience aggiungendo notifiche relative alle azioni compiute (record aggiornato / modificato / cancellato correttamente).
Approfittatene anche per fare un refactor del vostro layout, utilizzando @include per eventuali parti di codice che si ripetono (vedi messaggi di notifica e di errore).
