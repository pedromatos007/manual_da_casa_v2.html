[README.md](https://github.com/user-attachments/files/26161960/README.md)
# 🌿 Habitar a vida com beleza
### Manual da Casa — Planner de Limpeza & Organização

> *"Habitar a vida com beleza"* — um app completo para transformar a rotina da sua casa em um ritual de cuidado e organização.

---

## ✨ Sobre o projeto

**Habitar a vida com beleza** é um planner digital de limpeza e organização doméstica, desenvolvido como uma aplicação web de página única (`index.html`) — sem dependências de backend, sem banco de dados externo, sem instalação. Abre direto no navegador e funciona offline.

A paleta de cores foi inspirada em tons de **verde-eucalipto**, **dourado** e **bege creme**, trazendo elegância e leveza à rotina doméstica.

---

## 🖥️ Demo

🔗 **[Acesse o app online](https://SEU-USUARIO.github.io/habitar-a-vida-com-beleza/)**

> Substitua `SEU-USUARIO` pelo seu nome de usuário do GitHub após o deploy.

---

## 📋 Funcionalidades

### Dashboard — Hoje
- Visão geral do dia com estatísticas em tempo real
- Indicador de dias da semana com progresso visual
- Gráfico de histórico semanal de tarefas concluídas
- Barra de progresso diária e contador de dias consecutivos (streak)
- Campo para adicionar tarefas personalizadas

### Checklists interativos
Todas as tarefas são clicáveis — o estado é salvo automaticamente por dia via `localStorage`:

| Frequência | Itens |
|---|---|
| ✅ Tarefas Diárias | 17 itens (inclui o Furacão 15 min) |
| 📋 Tarefas Semanais | 9 itens |
| 🔄 Tarefas Trimestrais | 5 itens |
| 🛠 Tarefas Semestrais | 12 itens |

### Semanas por Ambiente
Checklists completos com passo a passo detalhado para cada área da casa:

| Semana | Ambiente | Itens |
|---|---|---|
| 1ª | 🛏 Quartos | 17 |
| 2ª | 🛋 Salas & Escritórios | 19 |
| 3ª | 🍳 Cozinha & Lavanderia | 22 |
| 4ª | 🚿 Banheiros | 18 |
| 5ª | 🌿 Quintais & Varandas | 10 |

### Guias de referência
- **Guia da Lavanderia** — símbolos de lavagem (lavar, alvejar, secar, passar) com descrições completas e instruções gerais de cuidado com as roupas
- **9 Passos da Organização** — metodologia completa para organizar qualquer ambiente, do descarte à identificação

---

## 🎨 Design

| Elemento | Detalhe |
|---|---|
| **Paleta principal** | Verde-eucalipto `#6B8F7E`, Dourado `#C9A84C`, Bege creme `#FDFAF5` |
| **Tipografia** | Playfair Display (títulos e logo) + Lato (corpo) |
| **Padrão de fundo** | Listras verticais sutis, inspiradas na embalagem do projeto |
| **Sidebar** | Verde sálvia escuro com acentos dourados |
| **Cards** | Superfícies brancas com bordas suaves e sombras delicadas |

---

## 🗂️ Estrutura do repositório

```
habitar-a-vida-com-beleza/
│
├── index.html       ← o app completo (HTML + CSS + JS em um único arquivo)
└── README.md        ← este arquivo
```

O projeto é intencionalmente de **arquivo único** — toda a lógica, estilos e dados estão contidos no `index.html`, facilitando hospedagem, compartilhamento e manutenção.

---

## 🚀 Como usar localmente

Não requer instalação de nenhuma dependência.

**Opção 1 — abrir direto no navegador:**
```bash
# Clone o repositório
git clone https://github.com/SEU-USUARIO/habitar-a-vida-com-beleza.git

# Abra o arquivo no navegador
open index.html          # Mac
start index.html         # Windows
xdg-open index.html      # Linux
```

**Opção 2 — servidor local simples (recomendado):**
```bash
# Com Python (já vem instalado na maioria dos sistemas)
cd habitar-a-vida-com-beleza
python3 -m http.server 8000

# Acesse no navegador:
# http://localhost:8000
```

---

## ☁️ Deploy no GitHub Pages

1. Vá em **Settings** → **Pages** no seu repositório
2. Em *Branch*, selecione `main` e pasta `/ (root)`
3. Clique em **Save**
4. Aguarde 1–2 minutos
5. Acesse: `https://SEU-USUARIO.github.io/habitar-a-vida-com-beleza/`

---

## 🔧 Como atualizar o app

```bash
# Edite o index.html com suas alterações, depois:
git add .
git commit -m "Descreva o que mudou"
git push origin main
```

O GitHub Pages publica a atualização automaticamente em 1–2 minutos.

---

## 💾 Persistência de dados

O app utiliza `localStorage` do navegador para salvar o estado das tarefas. Os dados são:

- **Salvos por dia** — cada dia tem seu próprio estado de progresso
- **Locais ao dispositivo** — não são enviados a nenhum servidor
- **Sem necessidade de conta ou login**

> ⚠️ Limpar o cache/dados do navegador apaga o histórico de tarefas.

---

## 🛠️ Tecnologias utilizadas

| Tecnologia | Uso |
|---|---|
| HTML5 | Estrutura e semântica |
| CSS3 | Estilos, variáveis CSS, animações, grid e flexbox |
| JavaScript (Vanilla) | Lógica de checklists, progresso, navegação e persistência |
| Google Fonts | Playfair Display + Lato |
| localStorage API | Persistência de dados no dispositivo |

Nenhum framework, nenhuma dependência npm, nenhum build step.

---

## 📄 Licença

Este projeto é de uso pessoal. Sinta-se livre para adaptar para a sua casa. 🏡

---

<p align="center">
  <em>Feito com 🌿 e muito carinho — para tornar a rotina doméstica mais bela e intencional.</em>
</p>
