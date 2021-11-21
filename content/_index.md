---
title: ""
date: 2021-11-21T16:39:13+01:00
draft: false
---

## Presentación

Hola, me llamo Diana y estoy cursando DAW a distancia. Este es mi primer sitio web estático hecho con Hugo.

{{% expand "Leer más..." %}}
La web está dividida en diferentes secciones creadas con el tema relearn.
{{% /expand %}}

{{% notice note "Tecnologías que han sido necesarias:" %}}
- Hugo
- Git
- Ubuntu (en mi caso)
{{% /notice %}}

### Instalar hugo en ubuntu
{{< tabs >}}
{{% tab name="apt-get" %}}
```Bash
sudo apt-get install hugo
```
{{% /tab %}}
{{% tab name="snap" %}}
```Bash
sudo snap install hugo --classic
```
{{% /tab %}}
{{< /tabs >}}

### Pasos seguidos para el desarrollo de la web

{{< mermaid align="center" >}}
graph LR;
    A(Instalación) --> B(Temas)
    B --> C(Contenido)
    C --> D(Shortcode)
    D --> E(Personalizar plantilla)
    E --> F(Multilenguaje)
    F --> G(Plantillas)
    G --> H(Datos ecternos)
{{< /mermaid >}}

### IDE utilizado
Para completar los apartados del apartado anterior que requieren la edición de diversos archivos he utilizado VisualStudio Code, dado que entre los diversos IDE's que hay disponibles de forma gratuita, es de mis favoritos.

Para descargar el paquete para ubuntu hacer click en el siguiente botón:

{{% button href="https://code.visualstudio.com/Download" icon="fas fa-download" %}}Descargar VS Code{{% /button %}}

