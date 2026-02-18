# ⭐ Ankeiro

Transforme automaticamente questões resolvidas no TecConcursos em flashcards prontos para importar no Anki.

O Ankeiro é uma extensão para navegador que detecta quando você responde uma questão e gera um card estruturado com:

- Enunciado
- Alternativas organizadas
- Comentário com formatação preservada

Sem copiar e colar.  
Sem retrabalho.  
Sem servidor.

---

## 🚀 Funcionalidades

- Detecta quando a questão foi respondida
- Abre automaticamente o comentário
- Preserva negrito, listas e formatação
- Remove elementos desnecessários
- Gera card pronto para importação no Anki
- Funciona 100% local (sem backend)

---

## 🧩 Como instalar (modo desenvolvedor)

1. Baixe ou clone este repositório
2. Extraia os arquivos
3. Abra o Chrome
4. Acesse:

   chrome://extensions/

5. Ative o **Modo do desenvolvedor**
6. Clique em **Carregar sem compactação**
7. Selecione a pasta do projeto

Pronto.

---

## 📝 Como usar

1. Acesse o TecConcursos
2. Clique na extensão
3. Clique em "Começar"
4. Resolva as questões normalmente
5. Após responder, o Ankeiro captura automaticamente
6. Finalize e gere o arquivo
7. Importe no Anki (modelo Básico)

---

## 📦 Estrutura do Projeto

ankeiro/
│
├── manifest.json
├── content.js
├── popup.html
├── popup.js
├── icons/
│ ├── logo.png
└── README.md


---

## ⚠️ Aviso

Este projeto não possui vínculo oficial com o TecConcursos ou o Anki.

Uso educacional.

---

## 🛠 Tecnologias

- JavaScript
- Chrome Extension (Manifest V3)
- MutationObserver

---

## 🤝 Contribuição

Pull requests são bem-vindos.

Se quiser melhorar:

- Detecção de alternativa correta
- Layout dos cards
- Exportação .apkg
- Melhorias de UX

---

## 📜 Licença

MIT License
