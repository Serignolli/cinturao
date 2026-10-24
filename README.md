# Cinturão · estudo 3D

Estudo de interações 3D na web. A rolagem dirige a câmera e puxa a página para dentro de um cinturão de asteroides; no núcleo, um laboratório com física deixa arremessar pedras, criar poços de gravidade e detonar o anel.

Site estático em um único `index.html`, com [three.js](https://threejs.org) carregado por CDN. Não há build nem dependências.

## Rodar localmente

```sh
npx serve .
# ou
python -m http.server 8000
```

Abra o endereço indicado no navegador. É preciso servir por HTTP (abrir o arquivo direto com `file://` bloqueia o módulo ES).

## Deploy na Vercel

Importe o repositório na Vercel e mantenha o preset **Other**, sem comando de build e com o diretório de saída na raiz. A Vercel publica o `index.html` como está.
