# 🚀 ProjectDump

**ProjectDump** is a Python CLI tool that detects a project's technologies, filters out non-essential files, and compiles the source code and directory structure into a single readable file.

---

## 📦 Features

- 🔍 Auto-detects technologies (Python, JavaScript, Java, etc.)
- 🧹 Skips dependencies, binaries, media, and config clutter
- 🌲 Generates a clean directory tree
- 📄 Dumps readable source code with syntax highlighting
- ⚡ Handles large projects and ignores huge files (>100MB)

---

## 🧑‍💻 Supported Technologies (Partial List)

- **Languages**: Python, JS/TS, Java, Kotlin, PHP, Ruby, Go, Rust, C#, Dart, R, Scala, Elixir
- **Frameworks**: React, Vue, Svelte, Angular, Next.js, Nuxt, Flutter, Android, iOS
- **Infra**: Docker, Kubernetes, Terraform, Ansible
- **CI/CD**: GitHub Actions, GitLab CI, CircleCI

---


Inside `source_dump.txt`demo:
```text
# SOURCE CODE DUMP
# ==================================================
# Path: C:\Users\ASUS\Desktop\projectdump_refactored\New folder
# Detected tech: python
# ==================================================

## DIRECTORY STRUCTURE

my_project/
├── src/
│ ├── main.py
│ └── helper.py
├── requirements.txt
└── README.md

## FILE CONTENTS

### Main.py
import os
def main():

if __name__ == "__main__":
    main()

```

## 🚀 Usage
Run from the command line:
```bash
  python main.py /path/to/your/project
```

## 📁 What It Ignores
- **Dependency folders**: node_modules, venv, etc.

- **Media & binaries**: .jpg, .exe, .log, etc.

- **Config/IDE**: .git, .vscode, .github, etc.

- **Large files over 100MB**

## ✅ Requirements
Python 3.x

## 🤝 Contributing
Feel free to fork and contribute to enhance tech detection, support new stacks, or improve output formatting!

