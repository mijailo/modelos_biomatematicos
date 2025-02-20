# Modelos Biomatemáticos I

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mijailo/bach_mate/master)

Este repositorio tiene la finalidad de compartir con la comunidad de profesores y alumnos de Modelos Biomatemáticos I de la Facultad de Ciencias, de la [Universidad Nacional Autónoma de México](https://www.unam.mx/) (y de todo el mundo xd), algunos recursos didácticos:

- Cuadernillos de [Jupyter](https://jupyter.org/).
- Plantillas de [![Latex](https://wikimedia.org/api/rest_v1/media/math/render/svg/45c5b62b0f454f4ed8caa486d6d3cd0e0c065232)](https://es.wikipedia.org/wiki/TeX) para tareitas.
- Secuencias didácticas.

## Preámbulos

> Ver [esta](https://github.com/alan-turing-institute/the-turing-way/blob/main/workshops/boost-research-reproducibility-binder/workshop-presentations/zero-to-binder-python.md) referencia.

Para poder acceder a una serie de cuadernillos de Jupyter, es necesario darle click al botoncito ![Binder](https://mybinder.org/badge_logo.svg) de arriba (esquina superior izquierda de este `README.md`) y esperar una poquita. Mientras tanto, [BinderHub](https://binderhub.readthedocs.io/en/latest/index.html) (el _backend_ de Binder) estará:

- Recolectando el contenido de este repositorio de GitHub.
- Analizando ese contenido.
- Creando un [Dockerfile](https://docs.docker.com/engine/reference/builder/) basado en el contenido de este repositorio.
- Lanzando la [imagen Docker](https://docs.docker.com/engine/reference/commandline/images/) correspondiente en la nube.
- Conectando tu navegador al contenedor.

## Alumnos

En esta carpeta hay material didáctico para los estudiantes de Biología (plan 2025) de acuerdo con los planes de estudio vigentes de la UNAM.

## Profesores

En esta carpeta hay:

* Algunos prototipos de _notebooks_ de [Jupyter](https://jupyter4edu.github.io/jupyter-edu-book/), enfocados a la elaboración y presentación de secuencias didácticas de matemáticas. Estos _notebooks_ se encuentran en la carpeta `Secuencias didácticas` y `Cursos`.
* Plantillas de [![Latex](https://wikimedia.org/api/rest_v1/media/math/render/svg/45c5b62b0f454f4ed8caa486d6d3cd0e0c065232)](https://es.wikipedia.org/wiki/TeX), con la que se puede escribir una tarea con símbolos y fórmulas matemáticas. Se puede compilar con [PDFLaTeX](https://miktex.org/) para producir un archivo con formato `PDF`.
