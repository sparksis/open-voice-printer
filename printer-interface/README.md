# Interface with the printer

## Image generation

Uses text2png:

Example image:

```bash
npm install
npm bin
./node_modules/.bin/text2png -t "$(echo -e Expire: 2021-05-01\\nGenerated: 2021-04-17)" -o hi.png
```
