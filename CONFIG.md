```TAG: "&a[&7SmartAdmin&a]"```

Tag, gdy operacja zostanie wykonana prawidłowo

```TAG_ERROR: "&4[&7SmartAdmin&4]"```

Tag, gdy coś źle wpiszemy lub operacja nie wykona się prawidłowo

```TAG_ANTYCHEAT: "&6[&eSmartAdmin&6]"```

Tag, przy wiadomościach wysyłanych przez AntyCheat

```JOIN_MESSAGE: "&a{player} &7joined the game"```

Wiadomość przy wejściu gracza na serwer, gdy wpiszemy ```false``` wiadomość zostanie usunięta!

Zmienne:
- ```{player}``` - wyświetla nick gracza.

```LEAVE_MESSAGE: "&a{player} &7left the game"```

Wiadomość przy wyjściu gracza z serwera, gdy wpiszemy ```false``` wiadomość zostanie usunięta!

Zmienne:
- ```{player}``` - wyświetla nick gracza.

```FULL_SERVER_MESSAGE: "&cThe server is full!"```

Wiadomość wyświetlana przy próbie wejścia gracza na serwer, gdy serwer jest pełny

```MAX_PLAYERS: true```

Ustawia liczbę slotów. **Uwaga, funkcja ta omija limity hostingów :D**

Wartośći:
- ```true``` - liczba slotów jest pobierana z server.properties (nie jest poprostu zmieniana),
- ```false``` - ustawia liczbę slotów na nieskończoność (wyświetlany jest zawsze jeden slot więcej, niż ilość graczy),
- liczba (np. ```50```) - ustawia tą liczbę jako liczbę slotów.
