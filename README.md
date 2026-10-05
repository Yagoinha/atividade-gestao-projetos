# Sistema Hipotético para Atividade Prática

Yago Barbosa Dini - Prontuário: BP3062813
  
## Propósito do Projeto
Simulação de desenvolvimento de uma miniaplicação web com controle de versão utilizando Git e hospedagem no GitHub, aplicando conceitos de branches, pull requests, tags e releases para a disciplina de Gestão de Projetos de Software (4º ADS - IFSP Câmpus Bragança Paulista).

## Plano de Releases Previsto

**Release 1 (v0.1)**:
  - Construção da tela inicial de login (`index.html`).
  - Redirecionamento ao clicar em entrar para página de aviso "Em construção" (`working.html`).

**Release 2 (v0.2)**:
  - Criação da página inicial do usuário Administrador (`pg001.html`).
  - Atualização do login para chamar diretamente a página do administrador sem consistência/validação.

**Release 3 (v1.0)**:
  - Implementação completa das validações via JavaScript:
    - Campo usuário vazio: exibe página de mensagem de erro (`msg.html`).
    - Usuário "admin": redireciona para a página do Administrador (`pg001.html`).
    - Qualquer outro usuário: redireciona para a página do Operador (`pg002.html`).
  - Criação das páginas `pg002.html` (Operador) e `msg.html` (Mensagem de erro).
  - Inclusão do arquivo `CHANGELOG.md` e tags de versão.
