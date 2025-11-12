# Grupo de Estudos DevOps — UFG

> **Material criado para o grupo de estudos de DevOps da UFG**, abordando conceitos introdutórios e práticos de **versionamento, Git e GitHub**.

---

## Objetivo

Este repositório tem como objetivo reunir materiais e exemplos que auxiliem estudantes e entusiastas a compreender os fundamentos do controle de versões e da colaboração em projetos de software.sicos de git e github

---

# 🧠 Resumo — Git e GitHub  

## 📘 1. Versionamento  
O **versionamento** é o histórico de um projeto. Cada *commit* representa um ponto no tempo, permitindo:  
- Rastrear alterações;  
- Colaborar em equipe;  
- Reverter erros;  
- Trabalhar com **branches** para diferentes versões do código.  

---

## 💻 2. Git  
O **Git** é um sistema de **controle de versão distribuído**, gratuito e open source.  
Permite gerenciar o histórico de alterações localmente, criando *commits* para cada modificação.  

---

## ☁️ 3. GitHub  
O **GitHub** é uma **plataforma online** baseada no Git que oferece ferramentas de colaboração, hospedagem de repositórios e controle de versões em nuvem.  

---

## 🔍 4. Diferenças entre Git e GitHub  

| Aspecto | **Git** | **GitHub** |
|----------|----------|-------------|
| O que é | Sistema de controle de versão | Plataforma online baseada em Git |
| Onde funciona | Local (no computador) | Nuvem (online) |
| Função | Versionar e gerenciar código | Hospedar e compartilhar projetos |
| Criador | Linus Torvalds (2005) | Chris Wanstrath e equipe (2008) |
| Uso offline | Sim | Não |
| Colaboração | Local | Em equipe (PRs, Issues, Forks) |

---

## ⚙️ 5. Principais Comandos Git  

| Comando | Descrição |
|----------|------------|
| `git init` | Cria um novo repositório local |
| `git clone <url>` | Clona um repositório remoto |
| `git add <arquivo>` | Adiciona arquivos ao stage |
| `git commit -m "mensagem"` | Salva alterações com mensagem |
| `git status` | Mostra o estado dos arquivos |
| `git branch` / `git checkout` | Gerencia e troca de branches |
| `git merge <branch>` | Mescla branches |
| `git pull` / `git push` | Atualiza e envia commits |
| `git fetch` | Busca alterações remotas |
| `git revert` / `git reset` | Desfaz alterações |
| `git stash` | Guarda alterações temporariamente |
| `git tag <nome>` | Marca uma versão específica |

---

## 🧾 6. Issue  
Uma **issue** é usada para relatar bugs, propor melhorias e discutir tarefas no projeto.  
**Boas práticas:** use títulos claros, descreva bem o problema e adicione *labels* (bug, feature, etc).  

---

## 🚫 7. .gitignore  
Define quais arquivos o Git deve **ignorar**, como binários, builds, logs e variáveis de ambiente.  

**Exemplo comum:**  
```bash
node_modules/
.env
__pycache__/
dist/
.vscode/
*.log
