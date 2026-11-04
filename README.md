# Minha TV — Catálogo de Filmes 0.2 (teste VLC)

## Objetivo
Substituir a URL de Sintel que falhou no VLC e testar fontes alternativas publicadas no domínio da Blender Foundation.

## Arquivos
- `filmes.m3u`: playlist experimental de dois filmes.
- `catalogo-filmes.json`: metadados, créditos, licenças e status de teste.

## Aviso importante
As URLs são **candidatas não verificadas em reprodução**. O ambiente de geração não conseguiu acessar os arquivos de vídeo remotamente; por isso não se afirma que funcionam. Não incluir no aplicativo antes do teste manual no VLC.

## Como testar
1. Extraia este ZIP e abra `filmes.m3u` localmente no VLC, sem precisar alterar o GitHub.
2. Dê dois cliques em cada filme; aguarde até 30 segundos e confira imagem, som e progresso.
3. Se falhar, use `Ferramentas > Mensagens` no VLC e registre o erro.
4. Somente após aprovação substitua `filmes.m3u` e `catalogo-filmes.json` no repositório. Não sobrescreva o README principal do repositório sem mesclar a documentação de canais.

## Licenciamento
Big Buck Bunny e Sintel: Blender Foundation, Creative Commons Attribution 3.0. Manter créditos originais e atribuição.
- https://peach.blender.org/
- https://durian.blender.org/about/
- https://durian.blender.org/download/

## Histórico
- 0.1: Sintel com URL `video.blender.org/static/webseed/...` reprovada no teste do usuário.
- 0.2: fontes candidatas em `download.blender.org` para Big Buck Bunny e Sintel; teste VLC pendente.
