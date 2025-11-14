# Meu Treino - Página Local

Abrir `index.html` no navegador exibe o treino do dia com checklist persistente.

Funcionalidades:
- Seleção automática do treino com base no dia da semana.
- Checklists salvos localmente por data (`localStorage`, chave `treino-checks-YYYY-MM-DD`).
- Templates/customizações salvas localmente (`treinos-custom-v1`).
- Adicionar exercícios ao treino do dia e salvar como template.
- Exportar dados (checks + templates) para JSON e importar de volta.
- Botões: Limpar Checklists, Restaurar Treinos Padrão, Exportar, Importar.

Como usar:
1. Abra `index.html` no navegador (duplo-clique ou `open index.html` no macOS).
2. Marque exercícios no checklist — eles ficam salvos para a data atual.
3. Para salvar alterações no template atual, clique em `Salvar como template`.
4. Para exportar dados (backup), clique em `Exportar Dados` e salve o arquivo JSON.
5. Para restaurar de um export, clique em `Importar Dados` e escolha o JSON exportado.

Observações:
- Tudo é salvo no `localStorage` do navegador — não há sincronia entre dispositivos.
- Para sincronização entre dispositivos, posso adicionar integração com um backend ou Google Drive/Dropbox.

Próximos passos sugeridos (me diga qual quer):
- Adicionar import automático por arrastar & soltar.
- Sincronização via API/conta.
- Melhor UI (tema escuro, animações, impressão).
- Commit das alterações no repositório Git.
