# TCS_2025_3-4Bimesters
# TCS_2025_3-4Bimesters

This repository contains all the research, assets and assembly plans for our secondary school final project on Portuguese influences in the formation of Brazil during the colonial period. You’ll find:

- Theoretical background and sources
- Markdown drafts and HTML outputs for each section
- Images, audios and hosting guidelines
- A structured plan to build a physical or virtual exhibition

---

## 📁 Estrutura do Projeto

.
├── index.html                  ← página-raiz para navegação
├── Pesquisa/                   ← todo o conteúdo pesquisado
│   ├── Cronologia/             ← linha do tempo e bandeiras
│   ├── Culinaria/              ← culinária colonial
│   ├── Danca/                  ← danças e ritmos
│   ├── Decoracao/              ← propostas de ambientação
│   ├── Lingua/                 ← genealogia e raízes do português
│   ├── Mapas/                  ← mapas históricos e rotas
│   ├── Mitologia/              ← lendas e coloniais
│   ├── Musica/                 ← pesquisa e “Rádio Colonial”
│   ├── OrgSocial/              ← organização social e estamentos
│   └── Religiao/               ← práticas e festas religiosas
└── Roadmap.html                ← checklist de etapas

---

## 🎯 Conteúdo de Cada Seção

- **Cronologia**: linha do tempo ilustrada, evolução de bandeiras e mini-legendas.
- **Culinária**: subseções de receitas (nome e descrição) e fontes históricas.
- **Dança**: dinâmicas de dança portuguesa, indígena e africana e citações.
- **Decoração**: guia para decorar a sala que será montada para a apresentação do trabalho.
- **Língua**: genealogia do português, fases históricas e curiosidades.
- **Mapas**: ilustram a visão de mundo dos portugueses durante o período colonial.
- **Mitologia**: narrativas e ilustrações de mitos coloniais.
- **Música**: roteiro de blocos para rádio colonial, texto de introdução e áudios.
- **OrgSocial**: descrição dos grupos sociais, dinâmica cotidiana e documentos históricos.
- **Religião**: influências, festas, irmandades e iconografia religiosa.

---

## 🚀 Como Usar

1. Clone o repositório:
   ```bash
   git clone https://github.com/SEU_USUARIO/TCS_2025_3-4Bimesters.git
   ```  
2. Abra `index.html` em qualquer navegador para navegar pelas seções.

---

## 🎧 Áudios Externos

Não versionamos `.mp3` no repositório. Hospedamos os arquivos em:

- **Dropbox**: usando o link compartilhado trocando `dl=0` por `raw=1`.
- **Google Drive**: usando `https://docs.google.com/uc?export=download&id=SEU_ID`.
- **Mega**: utilizando o iframe provido na aba de compartilhamento, no lugar da tag de áudio do HTML. (Método atual)
- **GitHub Releases**: anexando os MP3s a uma release e use a URL gerada.

No HTML:

```html
<audio controls preload="none"
       src="link do arquivo hospedado">
</audio>
```

---

## 📋 Git & Commits

- Adicione um `.gitignore` com:
  ```
  *.mp3
  ```
  para garantir que nenhum áudio entre no repositório.

- Se algum `.mp3` já estiver rastreado, remova do índice:
  ```bash
  git rm --cached '*.mp3'
  git commit -m "Remove MP3s do repositório"
  ```

---

## 🤝 Contribuindo

1. Crie uma branch por seção (ex: `feature/culinaria`).
2. Atualize os arquivos `.md` ou `.html` e adicione novas imagens em `Pesquisa/<seção>/images`.
3. Faça um Pull Request descrevendo a mudança com título curto e corpo detalhado.
