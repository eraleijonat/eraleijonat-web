# Helsingin Erä-Leijonien nettisivut

Staattiset sivut -> ei tarvetta webhotellille tai julkaisujärjestelmän päivityksille. Minimaalinen, nollasta kyhätty suhteellisen responsiivinen design. Mukana ei ole ainuttakaan JS-kirjastoa. :)

## Kehitysprosessi

Asenna wintersmith.

```bash
$ npm install wintersmith -g
```

Aja sivua lokaalisti.

```bash
$ wintersmith preview -p <portti>
```

## Deploy

```bash
$ wintersmith build
```

Tee push gh-pages-branchiin, niin sivut päivittyvät @ http://eraleijonat.github.io/eraleijonat-web/.