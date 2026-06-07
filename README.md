# 🙏 Ho'oponopono — Prática de Cura

Uma página web interativa para a prática meditativa do **Ho'oponopono**, a técnica havaiana de cura e reconciliação interior baseada em quatro frases sagradas.

---

## ✨ O que é Ho'oponopono?

Ho'oponopono é uma prática espiritual havaiana de perdão e cura. Ela consiste na repetição de quatro mantras:

> **Sinto muito · Me perdoe · Eu te amo · Sou grato**

A repetição dessas intenções com o uso de um **japamala de 108 contas** cria um ritual de concentração, presença e abertura interior.

---

## 🌐 Funcionalidades da Página

### 🪷 Japamala interativo
- Exibe um **japamala circular com 108 contas** desenhado em SVG
- A cada toque no centro (bead Sumeru), **uma conta é preenchida**
- As contas mudam gradualmente de cor: **azul ardósia → dourado**, acompanhando o progresso da prática
- Um brilho sutil destaca a última conta preenchida

### 🔢 Contador de contas
- Exibe em destaque o número de contas já realizadas: **0 / 108**
- Atualizado em tempo real a cada toque

### ✅ Mensagem de conclusão
- Ao atingir 108 contas, aparece a mensagem: **"Concluído — Gratidão 🙏"**
- Indica que o ciclo completo foi realizado

### ⏱️ Cronômetro
- Exibe o tempo decorrido da prática no formato `MM:SS`
- Inicia ao clicar em **Iniciar** e para ao concluir as 108 contas

### 👁️ Mostrar / Ocultar japamala
- Um botão permite ocultar o japamala visualmente
- A contagem e o cronômetro **continuam funcionando** mesmo com o japamala oculto

### 🎛️ Botões de controle
- **Iniciar** — começa a prática; fica opaco durante a sessão para evitar cliques acidentais; volta ao normal ao concluir
- **Reiniciar** — reseta tudo: contador, cronômetro e cores do japamala

---

## 📱 Design

- **Responsivo**: funciona em celulares, tablets e desktops
- Tema escuro com paleta espiritualizada (dourado, ardósia, pérola)
- Tipografia refinada com fontes Cinzel e Cormorant Garamond
- Atmosfera contemplativa com gradientes suaves e efeito glow nas contas

---

## 🗂️ Estrutura do projeto

```
/
├── hoponopono.html   # Página principal (arquivo único, sem dependências locais)
└── README.md         # Este arquivo
```

A página é **totalmente autocontida** — fontes carregadas via Google Fonts, sem backend, sem dependências locais.

---

## 🚀 Como hospedar no GitHub Pages

1. Crie um repositório no GitHub (ex.: `hoponopono` ou dentro do seu `usuario.github.io`)
2. Faça upload dos arquivos `hoponopono.html` e `README.md`
3. Vá em **Settings → Pages**
4. Em *Source*, selecione a branch `main` e a pasta `/ (root)`
5. Salve — em alguns segundos sua página estará disponível em:
   `https://seuusuario.github.io/hoponopono/hoponopono.html`

> **Dica**: Renomeie `hoponopono.html` para `index.html` para que a URL fique mais limpa: `https://seuusuario.github.io/hoponopono/`

---

## 🤍 Intenção

Esta página foi criada para apoiar práticas meditativas pessoais com uma interface simples, bonita e funcional — sem distrações, sem anúncios, apenas a prática.

---

*Sinto muito · Me perdoe · Eu te amo · Sou grato* 🌺
