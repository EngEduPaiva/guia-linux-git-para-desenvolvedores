---

## Projeto 3 — Guia Prático de Linux + Git (Repo de apoio)


---

### Arquivo: README.md (Guia Dev)
```markdown
# Guia Prático — Linux & Git (Eduardo Paiva)

## Git - comandos essenciais

- `git init` - inicializa repositório
- `git clone <url>` - clona repositório
- `git status` - mostra status
- `git add .` - adiciona mudanças
- `git commit -m "msg"` - commit
- `git branch nome` - cria branch
- `git checkout nome` - muda branch
- `git merge nome` - merge
- `git rebase nome` - rebase
- `git log --oneline --graph` - visualizar histórico
- `git reset --hard HEAD~1` - voltar commits (cuidado)
- `git checkout -- arquivo` - restaurar arquivo

## Exemplo de fluxo (feature branch)

git checkout -b feat/minha-feature

# desenvolver
git add .
git commit -m "feat: implementar X"
git push origin feat/minha-feature
# abrir PR
```
## Resolução básica de conflitos
```bash

1.	git pull e verifique conflito
2.	abra arquivos em conflito e escolha mudanças
3.	git add arquivo para marcar resolvido
4.	git commit e git push
```

##  Comandos Linux úteis

```bash
•	ls -la - listar
•	cd /caminho - navegar
•	grep -R "erro" . - buscar por palavra
•	ps aux | grep nome_process - procurar processo
•	top - monitorar processos
•	chmod +x script.sh - tornar executável
•	./script.sh - executar
•	cat arquivo - visualizar
•	tail -f arquivo - seguir log
```