# viimsi-sundmused

Viimsi valla sündmuste kalender: https://paremveebileht.ee/viimsisundmused2/

- `viimsisundmused2/index.html` – leht (kujundus ja loogika)
- `viimsisundmused2/events.json` – sündmused, allikad ja piirkonnad. Uue sündmuse lisamiseks lisa rida `events` massiivi ja uuenda `updated` kuupäev.

Sündmuse väljad: `title`, `d` (kuupäevad) või `range` ([algus, lõpp]), `t` (kellaaeg), `place`, `room`, `cats`, `url`, `ticket`, `img`, `src` (võti `sources` hulgast), `note`, `weekly`, `info`.
