# GIT Mini Project

Simulasi rilis project menggunakan gitHub flow, Conventional commits, annotated tag, pre-commit hook, dan dokumentasi realease workflow

## Git Hooks

Project ini menggunakan pre-commit hook untuk mendeteksi secret sederhana seperti:

- PASSWORD dengan format assignment
- API_KEY dengan format assignment

Aktifkan hook dengan:

```bash
git config core.hooksPath .githooks