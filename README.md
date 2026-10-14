# tutory-personagens

Modelos 3D dos personagens do **Aeroporto de Leads** do Tutory OS (Cadu, Dan, Marlom, marketing, vendas, clientes), servidos pela CDN do jsDelivr:

```
https://cdn.jsdelivr.net/gh/wellmota/tutory-personagens@v1.0.0/quaternius-uac/<Arquivo>.glb
```

Ficam aqui, e não no repositório do Tutory OS, pra não pôr ~60 MB de modelo no Git do projeto. O Tutory OS carrega daqui em produção (`js/quaternius.js`, constante `PASTA`).

- `quaternius-uac/` — "Ultimate Animated Character Pack" (nov. 2019) da Quaternius, convertido de .gltf (buffer em base64) para .glb. Licença CC0 (domínio público), em `quaternius-uac/LICENSE.txt`.
- Pra trocar ou acrescentar um modelo: subir o arquivo, criar uma tag nova (`v1.0.1`...) e atualizar a versão na URL em `js/quaternius.js`. A URL com tag é imutável, então a TV guarda em cache.
