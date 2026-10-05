# Changelog

Todas as alterações notáveis deste projeto serão documentadas neste arquivo.

## [1.0.0] - 2026-10-05 (Terceiro Release - v1.0)
### Adicionado
- Validação completa de formulário via JavaScript na página `index.html`.
- Página inicial do usuário Operador (`pg002.html`) com menu restrito.
- Página de erro `msg.html` com aviso "Preencher usuário" e botão de retorno.
- Suporte a redirecionamento dinâmico:
  - Usuário em branco -> `msg.html`.
  - Usuário "admin" -> `pg001.html`.
  - Demais usuários -> `pg002.html`.

## [0.2.0] - 2026-10-05 (Segundo Release - v0.2)
### Adicionado
- Página inicial do usuário Administrador (`pg001.html`) contendo menu completo de opções.
### Alterado
- Página de login (`index.html`) atualizada para direcionar diretamente para `pg001.html` sem validação de campos.
### Removido
- Página temporária `working.html` descontinuada do fluxo de login.

## [0.1.0] - 2026-10-05 (Primeiro Release - v0.1)
### Adicionado
- Estrutura inicial do projeto com `README.md` descritivo.
- Interface básica da tela de login (`index.html`).
- Página provisória `working.html` indicando sistema em construção.
