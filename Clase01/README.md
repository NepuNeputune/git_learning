# MARKDOWN
Lenguaje de marcado como el HTML

# H1
## H2
### H3
#### H4
##### H5
###### H6

**Esto es negrita**

*Esto es cursiva*

# Snippets de código

```js
function sumar(a,b) {
    return a + b
}
```

# GIT

## Inicializar repositorio

```sh
git init
```

## Verifico el estado de mi repo

```sh
git status
```

## Como agrego los archivos al area temporal (staging) de confirmación

```sh
git add . #El . es un comodín que indica todos los archivos (como * en python)
```

## Configuramos GIT.

```sh
git config --global user.name "Santiago Aimetta"
git config --global user.email "santiagoaimetta@hotmail.com" #En caso de equivocarse se envía de nuevo con el mail/nombre correcto. Se sobre-escribe.
```

> Un repositorio en particular, tenga otro name y otro email.


```sh
#Para cuando queres poner otra cuenta
git config --local user.name "Santiago Aimetta Figallo"
git config --local user.email "santiagoaimetta@hotmail.com"
```

