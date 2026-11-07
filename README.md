# Minha TV — Catálogo de Filmes 0.4

## Alterações
- Sintel (2010): fonte 1080p MKV confirmada pelo usuário no VLC.
- Tears of Steel (2012): nova fonte 720p MOV para teste, **não confirmada**.
- Fontes defeituosas das versões 0.1 e 0.2 não foram reutilizadas.
- JSON contém o status individual dos filmes.

## Teste no VLC
Abra `filmes.m3u` pelo menu Mídia > Abrir arquivo. Teste Tears of Steel por pelo menos um minuto, com imagem e áudio. Se falhar, não integre ao aplicativo.

## Publicação
Depois do teste, substitua somente `filmes.m3u` e `catalogo-filmes.json` na raiz do GitHub. Não sobrescreva o README principal, que também documenta os canais.

## Limitações
A reprodução de Tears of Steel e a compatibilidade Android/Media3 não foram testadas. A existência no diretório não garante funcionamento contínuo. Verificar licença e atribuição antes da distribuição.

## Fontes
- https://download.blender.org/demo/movies/
- https://download.blender.org/demo/movies/ToS/
- https://studio.blender.org/films/

## Histórico
0.1 e 0.2: fontes falharam. 0.3: Sintel validado no VLC. 0.4: Tears of Steel adicionado para teste.
