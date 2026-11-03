# Minha TV — Catálogo experimental 0.2 (03/11/2026)

## Mudanças
- Mantidos os quatro canais do catálogo 0.1.
- Adicionados candidatos para teste: Record News, SBT News, Record Rio, TV Cultura, Sesc TV, TVC Rio e CINDIE TV.
- Record Rio é listado na fonte como sujeito a restrição geográfica.
- Globo Rio e SBT Rio **não foram adicionados**: nenhuma fonte direta adequada foi confirmada.
- GloboNews já funcional na playlist antiga deve ser preservada; não foi copiada para esta.

## Estado da validação
- TV Câmara: reprodução mostrada pelo usuário no VLC.
- Demais canais: **não testados em reprodução contínua**; a presença na lista não garante funcionamento.
- Condições de licenciamento/incorporação **não verificadas**; uso experimental, não disponibilizar comercialmente sem autorização.

## Publicação
1. No repositório GitHub, abra **Adicionar arquivo > Carregar arquivos**.
2. Envie `canais.m3u` e `catalogo.json` desta versão, substituindo os antigos.
3. Confirme as alterações e aguarde o GitHub Pages atualizar.
4. No VLC: **Mídia > Abrir fluxo de rede**, cole a URL pública terminada em `/canais.m3u`.
5. Teste imagem e áudio por alguns minutos; registre os resultados antes de integrar ao app.

## Referências de descoberta (não equivalem a licenças)
- https://github.com/iptv-org/iptv/blob/master/streams/br.m3u
- https://github.com/Free-TV/IPTV/blob/master/lists/brazil.md
