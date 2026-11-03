# tasks-flask-crud
# 📋 Tasks Manager API (CRUD)

Uma API REST desenvolvida em Python com o microframework **Flask** para gerenciamento de tarefas (CRUD). Projeto desenvolvido durante a trilha de especialização em Python da **Rocketseat**.

---

## 🚀 Tecnologias Utilizadas

* **[Python 3](https://www.python.org/)**: Linguagem principal do projeto.
* **[Flask](https://flask.palletsprojects.com/)**: Microframework web para criação dos endpoints REST.
* **Git & GitHub**: Versionamento de código e documentação.

---

## ⚙️ Funcionalidades (Endpoints da API)

A API fornece rotas para executar as quatro operações fundamentais de persistência (CRUD):

| Método | Endpoint | Descrição |
| :--- | :--- | :--- |
| `POST` | `/tasks` | Cria uma nova tarefa |
| `GET` | `/tasks` | Lista todas as tarefas cadastradas |
| `GET` | `/tasks/<id>` | Retorna os detalhes de uma tarefa específica |
| `PUT` | `/tasks/<id>` | Atualiza o título, descrição ou status da tarefa |
| `DELETE` | `/tasks/<id>` | Remove uma tarefa do sistema |

---

## 🛠️ Como Executar o Projeto Localmente

### Pré-requisitos
* Ter o **Python 3.10+** e o **Git** instalados na máquina.

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/chrislecterpro/tasks-flask-crud.git
   cd tasks-flask-crud