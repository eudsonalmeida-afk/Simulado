# Simulado 02 — SEDUC-CE 2026 · P2 Biologia

Simulado autoral com 50 questões de alternativas A–D, 17 eixos e 11 diagramas vetoriais interpretativos.

## Publicar no GitHub Pages

1. Abra o repositório `Simulado` e carregue o arquivo **`index.html`** na raiz da branch `main` (o site funciona com esse arquivo sozinho).
2. Em **Settings → Pages**, selecione **Deploy from a branch**, a branch `main` e a pasta `/ (root)`; salve.
3. Abra o endereço publicado pelo GitHub Pages após o processo de publicação.

Os demais arquivos do ZIP são apenas auxiliares, para editar o banco de questões; não são necessários para executar o site.

## Aplicação e exportação

- O gabarito só é exibido ao finalizar.
- Cada item pode receber confiança 25, 50, 75 ou 100%, e origem da resposta (Lembrei, Inferi, Chutei).
- Respostas, marcações e tempo permanecem no `localStorage` deste navegador. Não há sincronização entre aparelhos.
- No relatório final, use **Exportar JSON** para enviar a correção e o mapa de desempenho ao ChatGPT. CSV permite análise em planilhas.
- **Atenção:** não reinicie o simulado antes de exportar os resultados.

## Arquivos

- `index.html` — aplicação completa autônoma, incluindo SVGs.
- `questoes_editaveis.json` — versão legível do banco de questões e gabarito, útil para manutenção. **Não publique este arquivo se quiser que o gabarito não fique facilmente acessível**, pois ele contém as respostas.
- `figures.json` — código fonte das 11 figuras vetoriais (também está incorporado no HTML).

Observação: em uma aplicação estática, alguém com acesso ao código-fonte pode inspecionar o gabarito mesmo antes de concluir o simulado. A interface não mostra as respostas antes da entrega.
