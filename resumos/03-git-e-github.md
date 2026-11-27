# Resumo 3 — Git e GitHub

**Git** é o sistema de controle de versão (local); **GitHub** é a plataforma que hospeda os repositórios na nuvem.

## Fluxo básico

```bash
git init                                  # cria o repositório local
git add .                                 # coloca os arquivos no stage
git commit -m "mensagem descritiva"       # registra no histórico
git branch -M main                        # nome da branch principal
git remote add origin <URL-do-repo>       # liga ao GitHub
git push -u origin main                   # envia
```

## Comandos do dia a dia

| Comando | Para que serve |
|---|---|
| `git status` | Ver o que mudou |
| `git log --oneline` | Histórico resumido |
| `git diff` | Ver diferenças |
| `git pull` | Baixar atualizações |
| `git clone <url>` | Copiar um repositório |

## Tags e versionamento semântico

Formato **MAJOR.MINOR.PATCH** (ex.: `1.1.0`):

- **MAJOR** — mudança que quebra compatibilidade
- **MINOR** — nova funcionalidade compatível
- **PATCH** — correção de bug

```bash
git tag 1.1.0
git push origin 1.1.0
```

## No VS Code

Painel **Source Control**: inicializar repositório → escrever mensagem → *Commit* → *Publish Branch*.

## Boas práticas

- Commits pequenos, com mensagens claras
- `.gitignore` para arquivos que não devem subir
- `README.md` explicando o projeto
