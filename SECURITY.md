# Segurança do RetroHub

O site oficial é uma página estática hospedada no GitHub Pages. Ele não recebe
senhas, dados bancários ou informações pessoais e não executa pagamentos. O
apoio ao projeto é feito externamente pelo Ko-fi.

## Escopo

- Site oficial: https://freeeroamtvbrasil.github.io/retrohub-oficial/
- Aplicativo: https://github.com/FreeeRoamTVBRASIL/retrohub-desktop

Relatos de segurança podem ser abertos no repositório oficial sem incluir
credenciais, tokens ou dados pessoais. Se o relato contiver informação
sensível, não a publique em uma issue pública.

## Controles aplicados

- Política de Segurança de Conteúdo restritiva.
- Bloqueio de formulários, frames, objetos, workers e conexões de rede iniciadas
  pelo site.
- Imagens e mídia limitadas ao próprio domínio e conteúdo incorporado.
- Política de referência `no-referrer` para links externos.
- Links externos abertos com isolamento `noopener noreferrer`.
