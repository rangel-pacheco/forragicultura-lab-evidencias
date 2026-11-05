# Forragicultura Lab · Portfólio de evidências

Página estática de apresentação acadêmica do protótipo local. Edição 1.0 de 05/11/2026. A tipologia proposta do PTT é Software/Aplicativo.

## Conferir localmente

Abra `index.html` em um navegador. A navegação, a galeria e os documentos funcionam diretamente do disco. Também é possível executar, **dentro desta pasta**, `python -m http.server 8080 --bind 127.0.0.1` e abrir o endereço local informado pelo servidor. Encerre com Ctrl+C. A apresentação e os documentos podem ser salvos em PDF pela caixa de impressão do navegador.

## Estrutura

- `index.html` reúne apresentação, fluxo, recursos, metodologia, aderência à Área 49, evidências, galeria, impacto, histórico e vínculo docente.
- `assets/` contém o estilo, a marca gráfica própria do portfólio, uma ilustração botânica e o pequeno script do botão de impressão.
- `assets/imagens/` contém oito capturas WebP do ambiente de demonstração fictício.
- `documentos/` contém ficha técnica, memorial e relatório dos testes, redigidos para divulgação, com estilo de impressão próprio.
- `.nojekyll` permite servir a raiz diretamente no GitHub Pages.

O site usa HTML, CSS e JavaScript nativos. Todos os recursos de exibição são locais. As referências à CAPES e à ONU são links de consulta voluntária.

## Atualizar conteúdo e evidências

1. Verifique o comportamento na versão documentada. Separe implementação, verificação, planejamento e impacto medido. Registre a data, a origem e o limite de cada afirmação.
2. Edite a página e as fichas afetadas. Atualize versão e data. Mantenha links relativos, textos alternativos e legendas de demonstração.
3. Produza novas capturas somente em base isolada com dados fictícios. Revise os pixels e os metadados. Confira todos os arquivos, inclusive ocultos e o histórico Git, antes de cada divulgação.
4. Teste âncoras, documentos, imagens, impressão e larguras pequenas. Faça uma revisão específica da área de publicação antes de registrar a versão.

## Publicar no GitHub Pages após autorização

Copie apenas os arquivos desta edição revisada para uma pasta independente fora de qualquer checkout de desenvolvimento. Inicie ali um repositório com histórico novo e confira os arquivos e o destino remoto antes de enviar. Na configuração de Pages do novo repositório, selecione **Deploy from a branch**, a branch aprovada e a pasta raiz. Confira o URL informado pelo GitHub, incluindo as imagens ampliadas e os três documentos. Registre a data e o endereço definitivo na documentação da proposta. Para atualizar, revise e envie a alteração para essa mesma branch, mantendo nomes e caminhos estáveis.
