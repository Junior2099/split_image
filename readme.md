# ▦ Recorta — Divisor de Imagens

O **Recorta** é uma aplicação web simples, leve e segura que permite dividir qualquer imagem em partes organizadas em uma grade de colunas e linhas. Todos os recortes são gerados e compactados diretamente no navegador do usuário em um arquivo ZIP.

---

## 🚀 Funcionalidades

- 📁 **Upload Simples:** Suporte para imagens nos formatos **PNG**, **JPG** e **WebP** (até 30 MB / 40 MP).
- 🎛️ **Configuração de Grade Personalizada:** Escolha de 1 a 20 colunas e linhas, com opções rápidas (*presets*) de 2×2, 2×3, 3×3 e 3×4.
- 👁️ **Pré-visualização em Tempo Real:** Veja exatamente como e onde cada corte será realizado antes de efetuar o download.
- ✂️ **Linhas de Corte Opcionais:** Inclua marcas tracejadas nos limites de cada imagem para facilitar impressões e recortes manuais.
- 📦 **Download em ZIP:** Baixe todos os recortes de uma única vez compactados em `.zip`.
- 🔒 **Privacidade Total (Client-Side):** Todo o processamento de imagem e criação do arquivo ZIP é feito localmente no próprio navegador, sem envio de dados a servidores externos.
- ⚡ **Zero Dependências Directas:** Desenvolvido em **HTML, CSS e JavaScript Vanilla** puro, sem bibliotecas externas.

---

## 📁 Estrutura do Projeto

O projeto é mantido em uma arquitetura de arquivo único (*single-file*), o que facilita sua execução e distribuição:

```text
.
├── index.html     # Código HTML, estilização CSS e lógica JavaScript
└── README.md      # Documentação do projeto
```

---

## 🛠️ Como Executar

Por ser uma aplicação totalmente *client-side*, você não precisa instalar nenhuma dependência ou servidor Node.js/Python:

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).

---

## 💡 Como Usar

1. **Escolha uma Imagem:** Arraste e solte o arquivo ou clique no painel para selecionar uma imagem no seu dispositivo.
2. **Configure a Divisão:**
   - Ajuste a quantidade desejada de colunas e linhas.
   - Escolha o formato de saída dos recortes (`PNG`, `JPG` ou `WebP`).
   - Marque ou desmarque a opção de **Incluir linhas de corte**.
3. **Baixe os Recortes:** Clique no botão **Baixar partes em ZIP** para receber a pasta compactada contendo todas as imagens numeradas sequencialmente.

---

## 📄 Licença

Este projeto é de uso livre para fins pessoais e comerciais.