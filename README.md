# Sprint 05 — Proteção de Entidade Filha (Pergunta)

Implementação dos tickets da Sprint 05:

- Componente Blade `danger-button`
- `PerguntaPolicy` com autorização para exclusão
- Autorização no back-end antes do `delete`
- Proteção do botão de exclusão na interface

## Regra

O usuário pode excluir uma pergunta quando:
1. é o dono da própria pergunta; ou
2. é o dono do evento ao qual a pergunta pertence.

> Observação: os arquivos `PATCH_EVENTO_CONTROLLER.txt` e `PATCH_EVENTOS_SHOW.txt` mostram exatamente onde aplicar as alterações no projeto-base. Eles são instruções de integração porque o código original do repositório não foi fornecido.
