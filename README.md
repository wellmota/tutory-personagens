# tutory-personagens

Modelos 3D dos personagens do **Aeroporto de Leads** do Tutory OS (Cadu, Dan, Marlom, marketing, vendas, clientes), servidos pelo GitHub Pages deste repositório:

```
https://wellmota.github.io/tutory-personagens/quaternius-uac/<Arquivo>.glb
```

Ficam aqui, e não no repositório do Tutory OS, pra não pôr ~60 MB de modelo no Git do projeto. O Tutory OS carrega daqui em produção (`js/quaternius.js`, constante `PASTA`).

- `quaternius-uac/` — "Ultimate Animated Character Pack" (nov. 2019) da Quaternius, convertido de .gltf (buffer em base64) para .glb. Licença CC0 (domínio público), em `quaternius-uac/LICENSE.txt`.
- Pra trocar ou acrescentar um modelo: subir o arquivo em `main`; o Pages publica em ~3 min. O GitHub Pages libera o acesso pra outras páginas (CORS) e responde 304 quando o arquivo não mudou.
- Não usar pelo jsDelivr (`cdn.jsdelivr.net/gh/...`): ele busca no GitHub no primeiro acesso e, quando o GitHub limita, guarda o erro no lugar do modelo.
