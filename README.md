# Diáconos — protótipo independente

Visitas e Ceias Domiciliares do Tabernáculo da Fé. Demonstração em HTML, CSS e JavaScript, com dados fictícios em memória. Sem backend, autenticação, banco de dados ou integração ao aplicativo atual.

## Abrir localmente

Abra `index.html` no navegador. Recarregar reinicia os dados.

## Cloudflare

Projeto independente configurado em `wrangler.jsonc`, com arquivos estáticos na raiz do repositório.

Após autenticar a conta Cloudflare, publicar a partir desta pasta com `npx wrangler deploy`.
No Cloudflare Workers Builds, conectar este novo repositório GitHub, sem comando de build, e usar `npx wrangler deploy` como comando de implantação.

Configuração baseada na [documentação oficial de arquivos estáticos](https://developers.cloudflare.com/workers/static-assets/).

## Demonstração

Perfis administrativos e operacionais simulados, cadastros, pastas, rodízio mensal revisável, ceias atribuídas manualmente, autorizações de semestrais, visitas avulsas, registros, itinerários fictícios, avisos locais e relatórios.

O rodapé público usa identidade fictícia. Nenhum arquivo de referência com identificação pessoal acompanha a publicação.


## Link público
https://diaconos-prototipo-tabernaculo.amosm-servicos.workers.dev/

Implantação inicial manual no Cloudflare. Atualizações do GitHub ainda não são sincronizadas automaticamente.

