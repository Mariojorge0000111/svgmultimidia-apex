# svgmultimidia-apex

Redireciona `svgmultimidia.com.br` (sem www) para `https://www.svgmultimidia.com.br`, mantendo o caminho.

O site de verdade fica no repositório `svgmultimidia` (Cloudflare Pages, só no `www`). Aqui é só o GitHub Pages servindo o domínio raiz,
porque o DNS fica no Registro.br, que não aceita CNAME na raiz. No Registro.br, o domínio raiz tem 4 registros A apontando para o GitHub Pages:
185.199.108.153, 185.199.109.153, 185.199.110.153 e 185.199.111.153.
