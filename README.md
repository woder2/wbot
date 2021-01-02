# WAPPS - TeamSpeak3 multifunction bot
# AUTHOR - woder
# VER - 0.0.1

# COMMANDS BOT
Komenda, która tworzy token dla grupy serwera, który bot zabiera po czacie X
      Użycie:
        !addToken add ID_GRUPY_SERWERA CZAS_W_SEKUNDACH     | Dodajemy token
        !addToken help                                      | DostÄ™pne komendy/uzycie

Komenda, która dodaje wpis do funkcji 'clanGroup'
      Użycie:
          !clanGroup add ID_KANAĹU ID_GRUPY       | Dodajemy wpis
          !clanGroup remove ID_KANALU ID_GRUPY    | Usuwamy wpis
          !clanGroup list                         | WyĹ›wietlamy wszystkie wpisy
          !clanGroup help                         | WyĹ›wietlamy dostÄ™pne komendy

Komenda, która dodaje wpis do funkcji 'serverGroupProtection'
       Użycie:
          !serverGroupProtection add DATABASE_ID ID_GRUP_PO_PRZECINKU       | Dodajemy wpis
          !serverGroupProtection remove DATABASE_ID ID_GRUP_PO_PRZECINKU    | Usuwamy wpis
          !serverGroupProtection list                                       | WyĹ›wietlamy wszystkie wpisy
          !serverGroupProtection help                                       | WyĹ›wietlamy dostÄ™pne komendy

Komenda, która dodaje wpis do funkcji 'adminStatusOnChannelComm'
       Użycie:
          !adminStatusOnChannelComm add ID_KANAĹU ID_GRUPY       | Dodajemy wpis
          !adminStatusOnChannelComm remove ID_KANALU ID_GRUPY    | Usuwamy wpis
          !adminStatusOnChannelComm list                         | WyĹ›wietlamy wszystkie wpisy
          !adminStatusOnChannelComm help                         | WyĹ›wietlamy dostÄ™pne komendy

Komenda, która czyĹ›ci czat z botem
        Użycie:
          !clear

Komenda, która dodaje wpis do funkcji 'groupOnline'
        Użycie:
          !groupOnline add ID_KANAĹU ID_GRUPY "WZĂ“R_NAZWY_KANALU"       | Dodajemy wpis   np. !groupOnline add 12 87 "[cspacer001]Aktualnie online: [on]/[all]"
          !groupOnline remove ID_KANALU ID_GRUPY                      | Usuwamy wpis
          !groupOnline list                                           | WyĹ›wietlamy wszystkie wpisy
          !groupOnline help                                           | WyĹ›wietlamy dostÄ™pne komendy

Komenda, która zaczepia wszystkich na serwerze
        Użycie:
          !pokeAll "Twoja wiadomoĹ›Ä‡"

Komenda, która wysyĹ‚a wiadomoĹ›Ä‡ do wszystkich na serwerze
        Użycie:
          !pwAll "Twoja wiadomoĹ›Ä‡"

Komenda, która przenosi administratorĂłw na zebranie
        Użycie:
          !meeting

Komenda, która przenosi na dany kanaĹ‚ gildyjny
        Użycie:
          !warp NUMER_GILDI

```````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````````
