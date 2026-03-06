# 🖱️ Automação para Manter Tela Ativa (Python)

Este projeto consiste em um pequeno script em **Python** desenvolvido para manter a tela do computador ativa através de movimentos automáticos do cursor do mouse.

O objetivo principal é evitar que o sistema entre em **modo de suspensão ou bloqueie automaticamente**, especialmente em ambientes onde **dashboards ou painéis de monitoramento precisam permanecer visíveis continuamente**, como telas exibindo relatórios de **Power BI**.

---

# 🎯 Problema Resolvido

Em muitos ambientes corporativos, dashboards são exibidos em **monitores ou televisores para acompanhamento contínuo de indicadores de negócio**.

Entretanto, sistemas operacionais possuem políticas automáticas de:

- Bloqueio de tela
- Suspensão do sistema
- Economia de energia

Isso pode interromper a visualização dos dashboards.

Este script resolve esse problema simulando **atividade do usuário através de pequenos movimentos do cursor do mouse**.

---

# ⚙️ Como o Script Funciona

O script executa um loop contínuo que:

1. Move o cursor do mouse para uma posição específica da tela
2. Aguarda um determinado intervalo de tempo
3. Move o cursor para outra posição
4. Repete o processo continuamente

Esse pequeno movimento é suficiente para que o sistema interprete que o computador ainda está em uso.

---

# 🛠️ Tecnologias Utilizadas

- **Python**
- **pywinauto** (automação de mouse)
- Automação simples de interface
