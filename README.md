# ✅ todo-drag-drop-js

Uma lista de tarefas interativa (To-Do List) com suporte a **Drag & Drop**, desenvolvida com **HTML, CSS e JavaScript puro**. Ideal para organizar tarefas e testar interações modernas com armazenamento local e manipulação de DOM.

---

## 📌 Tópicos

- [📖 Sobre o Projeto](#-sobre-o-projeto)
- [🚀 Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [⚙️ Como Executar](#️-como-executar)
- [🛠️ Funcionalidades](#️-funcionalidades)
- [🧠 Explicação do Código](#-explicação-do-código)
- [📄 Licença](#-licença)
- [🤝 Contribuindo](#-contribuindo)

---

## 📖 Sobre o Projeto

Esta aplicação permite adicionar tarefas em uma lista e reordená-las facilmente com **drag and drop** (arrastar e soltar). As tarefas são salvas automaticamente no `localStorage`, garantindo que elas permaneçam salvas mesmo após recarregar a página.

---

## 🚀 Tecnologias Utilizadas

- HTML5
- CSS3
- JavaScript (vanilla)
- API de `localStorage` e eventos `drag and drop`

---

## ⚙️ Como Executar

1. **Clone o repositório:**

```bash
git clone https://github.com/rafaelmoreirax/todo-drag-drop-js.git
cd todo-drag-drop-js
```

2. **Abra o arquivo HTML no navegador:**

```bash
start index.html
```

Ou clique duas vezes no arquivo `index.html`.

---

## 🛠️ Funcionalidades

- [x] Adicionar novas tarefas
- [x] Reordenar tarefas com `drag & drop`
- [x] Persistência automática com `localStorage`
- [ ] Editar tarefas existentes (em planejamento)
- [ ] Remover tarefas (em planejamento)

---

## 🧠 Explicação do Código

- As tarefas são salvas em um array e persistidas via `localStorage`.
- Cada `<li>` da lista é **draggable** e escuta os eventos `dragstart`, `dragover`, `drop`, e `dragend`.
- A lógica de movimentação reorganiza o array de tarefas com `splice()` com base nos índices arrastados.
- O `renderTasks()` atualiza a exibição e o armazenamento a cada alteração.

---

## 📄 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

## 🤝 Contribuindo

Contribuições são muito bem-vindas!

1. Faça um fork deste repositório.
2. Crie uma branch: `git checkout -b minha-feature`
3. Commit suas alterações: `git commit -m 'feat: nova funcionalidade'`
4. Push para sua branch: `git push origin minha-feature`
5. Abra um Pull Request.

---

## 👤 Autor

Feito com 📝 por [Rafael Moreira](https://github.com/rafaelmoreirax)
