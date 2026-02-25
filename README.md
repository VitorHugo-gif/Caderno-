# Caderno++

> Micro‑app de estudos **local** que roda 100% com recursos do navegador (HTML/CSS/JS).  
> Edição inline, TTS com leitura acompanhada, camadas **Texto / Resumo / P&R**, múltiplos cadernos com temas, **Exportar Markdown** e **Backup/Import JSON**.
---

## ✨ Destaques

- ✅ **Sem instalações**: um único `Caderno++.html` abre direto no **Chrome/Edge** e funciona totalmente local, sem bibliotecas externas.  
- ✅ **Edição inline** com barra de formatação (negrito, itálico, lista, título/subtítulo).  
- ✅ **TTS por capítulo** (voz PT selecionável, velocidade e timbre) com **Leitura Acompanhada** (highlight durante a narração).  
- ✅ **Camadas** por capítulo: **Texto principal**, **Resumo** e **Perguntas & Respostas** (liga/desliga global).  
- ✅ **Múltiplos cadernos** (criar/renomear/excluir), cada um com **tema** próprio.  
- ✅ **Auto‑save** contínuo em armazenamento local + **Exportar/Importar JSON** (backup/portabilidade).  
- ✅ **Exportar Markdown** nativo (inclui *front‑matter* com metadados do caderno).  
- ✅ **Busca** por capítulos na sidebar e **TOC** clicável com rolagem suave.

> 💡 **Importante:** não renomeie o arquivo `Caderno++.html`. O app usa o **nome do arquivo** para montar a chave do armazenamento local; se renomear, parecerá que suas notas “sumiram” (ficam em outra chave). Mantenha o nome para não confundir o `localStorage`.

---

## 🧪 Uso rápido

1. Baixe/clique em `Caderno++.html`.  
2. O app abre no navegador e já vem com um capítulo de exemplo.  
3. Clique em qualquer texto para editar; use a barra inferior para formatar.  
4. Use **▶ Ler** no capítulo para ouvir o TTS (opcional com **Leitura Acompanhada**).

> Se quiser publicar uma demo, você pode subir este arquivo no seu repositório e ativar **GitHub Pages** apontando para a branch com o HTML.

---

## 🚀 Como usar

### 1) Organização em **Cadernos** e **Capítulos**
- Na sidebar, escolha o **Caderno Ativo** (select) ou crie um novo (**+**).  
- Renomeie (✎) ou exclua (🗑) cadernos.  
- Cada caderno guarda seu **tema**, conteúdos e **preferências** (camadas, TTS).  
- Adicione capítulos com **+ Novo capítulo** (sidebar).  

### 2) **Edição e Formatação**
- Clique para editar (modo *contenteditable*).  
- Barra flutuante: **Negrito (Ctrl+B)**, **Itálico (Ctrl+I)**, **Lista**, **Título**, **Subtítulo**, **Texto**.  
- **Ctrl+S** salva manualmente (há *auto‑save* automático).  
- `Enter` em Títulos cria um parágrafo logo abaixo.

### 3) **Camadas de Estudo**
- **Texto principal**  
- **Resumo**  
- **Perguntas & Respostas**  

Ligue/desligue globalmente em **Exibição → Camadas** (valem para todos os capítulos do caderno).

### 4) **Leitura em voz alta (TTS)**
- Em cada capítulo aparece a *toolbar* com **▶ Ler** e **⏹ Parar**.  
- Escolha a **voz PT** em *Narrador (PT)*, ajuste **Velocidade** e **Timbre**.  
- **Leitura Acompanhada** destaca na tela o trecho sendo narrado (opcional).

### 5) **Temas**
- Sidebar → **Cores → Personalizar** e selecione chips de cores (ex.: *Vermelho*, *Roxo/Azul*, *Preto/Cinza*, etc.).  
- O tema é salvo **por caderno**.

### 6) **Busca e Navegação**
- Pesquise títulos na **Busca** da sidebar.  
- A **TOC** lista os capítulos; clique para rolar suave até o alvo.

---

## 💾 Exportar / Importar

### Exportar **JSON** (backup do caderno)
- **Exportar JSON** baixa um arquivo com **todos os cadernos** + **caderno ativo**.  
- Use **Importar** para carregar em outra máquina/navegador.

### Exportar **Markdown** (texto livre)
- **Exportar MD** converte **capítulos** e **camadas** em **Markdown** com *front‑matter*:
  ```yaml
  ---
  caderno: "nome"
  tema: "Tema atual"
  criado: 2026-02-24T12:34:56.000Z
  modificado: 2026-02-24T13:21:00.000Z
  ---
 
