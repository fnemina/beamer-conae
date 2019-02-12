# beamer-conae

Este es el tema de beamer para Latex basado en el archivo powerpoint enviado
el 12 de febrero de 2019. Basado en el style de SABIA-Mar creado por Ivanna
Tropper.

## Consideraciones previas

Para instalar el tema de beamer para Latex debe tenerse una configuración
funcionando de latex que incluya Xetex y lualatex. Esto es necesario para
utilizar la fuente Arial en el documento.

Debe además instalarse la fuente `Arial` en el sistema operativo. En el caso
de utilizar Ubuntu puede instalarse haciendo

```bash
sudo apt-get install ttf-mscorefonts-installer
```

## Uso del estilo

Para utilizar el estilo debe copiarse el contenido de la carpeta beamer-conae
a la carpeta donde se encuentre el archivo de la presentación. Además debe
usarse la linea

```latex
\usetheme{conae}
```

en el archivo de la presentación. El contenido copiado debe incluir la
subcarpeta logos.

## Compilación

Para compilar la presentación debe usarse `lualatex` como

```bash
lualatex presentacion.tex
```
