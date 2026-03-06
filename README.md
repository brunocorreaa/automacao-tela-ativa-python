# automacao-tela-ativa
Script em Python para manter a tela ativa movendo o cursor automaticamente.


# Power BI Screen Awake Automation

Pequeno script em **Python** desenvolvido para manter a tela ativa em ambientes onde dashboards ficam expostos continuamente.

Este tipo de automação é útil quando **painéis de monitoramento (Power BI, BI corporativo ou dashboards operacionais)** ficam sendo exibidos em televisores ou monitores ao longo do dia.

O script simula atividade do usuário movendo levemente o cursor do mouse em intervalos regulares, evitando que o sistema entre em modo de suspensão ou bloqueie a tela.

---

# 🎯 Problema Resolvido

Em muitos ambientes corporativos, dashboards são exibidos em telas de monitoramento para acompanhamento de indicadores de negócio.

Entretanto, os sistemas operacionais frequentemente entram em:

- Modo de suspensão
- Bloqueio automático
- Economia de energia

Isso faz com que o painel deixe de ser exibido.

Este script resolve o problema **simulando atividade do usuário** através de pequenos movimentos do cursor.

---

# ⚙️ Como Funciona

O script executa um loop infinito que:

1. Move o cursor para uma posição específica da tela
2. Aguarda alguns segundos
3. Move o cursor para outra posição
4. Repete o processo continuamente

Esse pequeno movimento é suficiente para o sistema entender que o computador está em uso.

---

# 🛠️ Tecnologias Utilizadas

- **Python**
- Biblioteca **pywinauto**
- Automação de mouse

---

# 📦 Instalação

Primeiro instale a biblioteca necessária:

```bash
pip install pywinauto
