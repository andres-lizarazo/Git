# 📘 Git learning

## 📄 Common commands for Git and GitHub, with examples in HTML and more.

---


### 🛠 Herramientas

- [Git](https://git-scm.com/)
- [GitHub](https://github.com/)
- Terminal / Línea de comandos
- Visual Studio Code (opcional)

---

### 💡 Comandos Básicos de Git

| Comando                        | Descripción                                        |
|-------------------------------|----------------------------------------------------|
| `git init`                    | Inicializa un nuevo repositorio local              |
| `git clone <url>`             | Clona un repositorio remoto                        |
| `git status`                  | Muestra el estado de los archivos                  |
| `git add <archivo>`           | Agrega un archivo al staging area                 |
| `git commit -m "mensaje"`     | Crea un commit con un mensaje                     |
| `git log`                     | Muestra el historial de commits                    |
| `git branch`                  | Lista las ramas disponibles                        |
| `git checkout <rama>`         | Cambia a otra rama                                 |
| `git merge <rama>`            | Fusiona una rama con la actual                    |
| `git pull`                    | Descarga y fusiona los cambios desde el remoto     |
| `git push`                    | Sube los commits al repositorio remoto             |

---

### 🔀 Flujos de Trabajo

- **Main + Feature Branches**: Crear ramas por funcionalidad y luego hacer merge a `main`.
- **Pull Requests**: Usar GitHub para revisión de código y colaboración.
- **Commits atómicos**: Hacer commits pequeños y significativos.

---

### ⚠️ Errores Comunes

- ❌ Olvidé hacer `git add` antes del commit
- ❌ Me equivoqué de rama
- ❌ Hice `push` al repo equivocado



### 📂 Estructura del Repositorio (en progreso)

```bash
📦 git-learning/
├── commands.md
├── index.html
└── README.md
