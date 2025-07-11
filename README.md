# ComandosGit
</br>

## Dá pra visualizar se o commit tá ali, em qual branch, se foi pro remoto, etc.
</br>

```bash 
git log --oneline --graph --decorate --all  
```

## Precisei limpar arquivos nao rastreados e descartar alteraçoes locais para poder fazer o pull:


```bash
git clean -fd

git reset --hard

git pull
```
