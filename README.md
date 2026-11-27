<p align="center">
  <img src="docs/logo.png" alt="Logo do Tasker" width="140">
</p>

<h1 align="center">Tasker</h1>

<p align="center">
  Gerenciador de tarefas para Windows, simples e direto, para organizar a rotina do dia.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flet-0F172A?logo=flutter&logoColor=white" alt="Flet">
  <img src="https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/Windows-0078D6?logo=windows&logoColor=white" alt="Windows">
</p>

---

## Tela

<p align="center">
  <img src="https://github.com/user-attachments/assets/36147b3b-f33b-4c3d-b9e0-480d2b43fb6a" alt="Tela do Tasker" width="420">
</p>

## Funcionalidades

- Criar, editar e excluir tarefas, com confirmação antes de excluir
- Prioridade baixa, média ou alta, cada uma com sua cor
- Abas para ver todas as tarefas, as em andamento ou as finalizadas
- Filtro por prioridade
- Tarefas salvas num banco SQLite no próprio computador

## Como usar

### Pelo executável (Windows)

Não precisa ter o Python instalado.

1. Baixe o repositório e extraia os arquivos.
2. Abra o `TASKER.exe`.

> Para colocar o Tasker na área de trabalho, crie um **atalho** para o `TASKER.exe` em vez de mover o arquivo. Ele precisa ficar na mesma pasta que `database` e `img`.

### Pelo código

Com Python 3.11 instalado:

```bash
git clone https://github.com/henryco-meneghetti/Tasker.git
cd Tasker
pip install flet
python TASKER.PY
```

## Tecnologias

| Parte | Tecnologia |
|---|---|
| Interface | Python com [Flet](https://flet.dev) |
| Dados | SQLite |
| Executável | PyInstaller |

## Autor

Feito por [Henryco Meneghetti](https://www.linkedin.com/in/henryco-meneghetti-1659b035b/).
