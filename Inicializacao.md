# Iniciando e Conectando

## Iniciando o GIT local e comitando

1. Iniciar o _git_ local: `git init`
2. Mudar o nome da branch: `git branch -m master main`
3. Adicionar os arquivos: `git add .`
4. Fazer o commit: `git commit`

## Conectando ao GitHub e testando

### Conectando

```bash
# Inicialize o repositório local (se ainda não tiver feito)
git init

# Conecte o repositório local ao remoto
git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git

# Adicione arquivos e faça um commit
git add .
git commit -m "Primeiro commit"

# Envie o código para o GitHub
git push -u origin main
```
+ Testando: `git remote -v`