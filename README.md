# Comandos do Git:
```
git add .
```

```
git commit -m "mensagem"
```

```
git push
```

# Comandos para Copiar o Repositório:

## 1. Clonar o repositório original com `--mirror`:
```
git clone --mirror https://github.com/seu-usuario/repositorio-original.git
```

## 2. Entrar na pasta:
```
cd repositorio-original.git
```

## 3. Criar um novo repositório no GitHub (com outro nome, exemplo: repositorio-copiado)
O novo repositório não deve conter o arquivo README.md.

## 4. Empurrar (push) tudo pro novo repositório:
```
git push --mirror https://github.com/seu-usuario/repositorio-copiado.git
```
