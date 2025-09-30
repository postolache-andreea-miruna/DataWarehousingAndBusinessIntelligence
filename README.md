# Data Warehousing & Business Intelligence
TAMBook - librărie online - proiect master an 2
Proiect de echipă: Postolache Andreea Miruna, Dobre Talida Marina, Ion Alexandra

Backend - Oracle, [Frontend](https://github.com/alexion2001/dwbi_tam-book) - React, pentru a face legătura dintre cele două s-a instalat ORDS

TAMBook este o aplicație internă care îi permite administratorului să înregistreze o comandă pe care vrea să o plaseze utilizatorul care i-a cerut aceasta ce va conține cărțile alese în cantitatea dorită. De asemenea, dintre funcționalitățile aplicației se enumeră: vizualizarea comenzilor făcute de un utilizator ales, vizualizarea detaliilor pentru o comandă dată, vizualizarea cărților, editurilor, seriilor, categoriilor, autorilor, comenzilor și a detaliilor acestora, recenziilor, adreselor, orașelor, țărilor. Mai mult, aplicația prezintă o gestionare eficientă a produselor și stocurilor. Totodată aplicația oferă accesul la o serie de grafice dinamice pentru a se putea studia statisticile vânzărilor.

Astfel, un utilizator poate avea mai multe adrese care conțin date de livrare printre care și orașul care face parte dintr-o țară (o țară are mai multe orașe, iar un oraș poate fi inclus în mai multe adrese), iar acesta poate plasa mai multe comenzi la adrese diferite.

În ceea ce privește comanda, aceasta, inițial, se creează pentru un utilizator și adresa selectată, cu totalul pe 0, iar în timp ce sunt adăugate detaliile comenzii – cartea aleasă, cu prețul ei în momentul respectiv, cantitatea și discountul dacă este cazul – atunci totalul din comandă este actualizat pentru a corespunde cu realitatea.

Mai mult, în acest model, o carte este publicată de o singură editură, are o singură serie, o singură categorie și un singur autor, dar o serie, categorie, autor, editură pot avea mai multe cărți. Totodată, un utilizator poate scrie mai multe recenzii pentru cărțile dorite, chiar și mai multe în aceeași zi.

Aplicația are ca scop managementul unei librării online, prin gestionarea produselor și vânzărilor. Focusul principal al acesteia este pe creșterea vânzării produselor prin urmărirea tendințelor de cumpărare a acestora în funcție de mai mulți factori, precum: autor, serie, categorie și editura.
