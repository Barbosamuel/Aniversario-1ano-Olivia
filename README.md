# 🎉 Convite Interativo - Aniversário de 1 Ano da Olívia

Este projeto é um convite digital interativo desenvolvido com HTML, CSS e JavaScript, hospedado via GitHub Pages.

🔗 Acesse o convite:  
https://barbosamuel.github.io/Aniversario-1ano-Olivia/

---

## ✨ Funcionalidades

- 📱 Layout responsivo (formato celular 9:16)
- 🎬 Navegação entre telas com vídeos animados
- 🔔 Efeito sonoro ao abrir o convite
- 🎵 Música de fundo durante a navegação
- ⏳ Contador regressivo para o evento
- 🎭 Transição animada entre telas (efeito papel abrindo)
- 📍 Integração com Google Maps
- 📝 Confirmação de presença via Google Forms
- 🎁 Tela com sugestões de presentes
- 📅 Botão inteligente "Adicionar ao Calendário"
- 🔙 Navegação entre telas com botões invisíveis

---

## 🧭 Estrutura do Projeto
<img width="224" height="394" alt="image" src="https://github.com/user-attachments/assets/f732a00d-a126-4903-a13f-2d6f9cd85cac" />


---

## 🎨 Como Funciona

O convite é dividido em 4 telas:

1. **Tela 1** – Convite inicial com botão invisível  
2. **Tela 2** – Vídeo de abertura do convite  
3. **Tela 3** – Informações do evento + botões interativos  
4. **Tela 4** – Sugestões de presentes  

A navegação ocorre através de áreas clicáveis posicionadas sobre imagens/vídeos.

---

## 🎬 Transições

- Transição suave entre telas com `opacity`
- Efeito especial entre tela 2 → tela 3 simulando:
  - 📜 papel se desdobrando
  - animação com `scale`, `rotateX` e easing customizado

---

## 🔊 Áudio

- 🎵 Música de fundo: `MinhaPaz.mp3`
- 🔔 Efeito sonoro: `MagicChime.mp3`

A música inicia corretamente após interação do usuário devido às políticas de autoplay dos navegadores.

---

## 📅 Integração com Calendário

O botão de calendário é inteligente:

- 🍎 iPhone → abre diretamente no Apple Calendar via `.ics`
- 🤖 Android / 💻 Desktop → abre Google Calendar

Arquivo utilizado:
assets/aniversario.ics


Inclui:
- 📅 Data e horário do evento
- 📍 Local com link do Maps
- ⏰ Lembrete automático (1 hora antes)

---

## 🌐 Publicação

O projeto está hospedado via **GitHub Pages**.

### Para publicar:

1. Vá em **Settings > Pages**
2. Selecione:
   - Branch: `main`
   - Pasta: `/root`
3. Salve e aguarde alguns segundos

---

## 🖼️ Preview ao Compartilhar

O preview (WhatsApp, redes sociais) utiliza Open Graph:

- Imagem: `assets/preview.png`
- Configurado no `<head>` do HTML

⚠️ Pode ser necessário usar parâmetros no link para forçar atualização:
https://barbosamuel.github.io/Aniversario-1ano-Olivia/?v=1


---

## ⚠️ Observações

- O áudio depende de interação do usuário (restrição dos navegadores)
- O layout é otimizado para celular (visual vertical)
- O `.ics` pode baixar ou abrir diretamente dependendo do dispositivo
- GitHub Pages pode levar alguns segundos para atualizar novos arquivos

---

## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3 (animações e responsividade)
- JavaScript (interações e lógica)

---

## Autor

Desenvolvido por Samuel Barbosa
