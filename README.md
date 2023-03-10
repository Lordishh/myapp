<p align='left'>
  <img src="https://www.frba.utn.edu.ar/wp-content/uploads/2019/10/logo-UTNBA-PNC-2016-2019-e1570223041254.png" />
</P>

---

# `Bienvenidos a ReactJs`

---

<a id="top"></a>

## `Bloques temáticos:`

- [**Extensiones y recomendaciones**](#item1)
- [**Instalación de dependencias**](#item2)
- [**homework**](#item3)

---

---

Ha llegado el gran momento esperado por todos. Comenzar a trabajar con ReactJs. El objetivo de esta documentación, además de ver cuál será nuestro desafío, también será conocer algunos consejos y extensiones de VSCode que nos darán ciertas ventajas en React. No vamos a abarcar muchas, como tampoco conoceremos los snippets, ya que preferimos que escriban todo el código manualmente. Nuestra intención es presentarles las que consideramos más importante para el trayecto del curso. Si bien estas extensiones son para VSCode, cada una de ellas tienen sus alternativas para otros editores de textos.

<a id="item1"></a>

## `Extensiones y recomendaciones`

`Bracket Pair Colorizer 2`

Esta era una extensión que hoy ya es parte de VSCode, es decir, que ya está integrada. Esto agrega los colores del arcoíris a los corchetes, paréntesis y llaves, los cuales a través del anidamiento tendrán distintos colores. Te aseguro que te salvará más de una vez.

Para activarla presione "ctrl+," o archivos -> preferencias -> Configuración

En el buscador poner "bracket pair"

Una vez allí, puedes probar esta configuración que les dejo a continuación, tanto en usuario como en área de trabajo:

![img](./img/img-1.png)

resultado:

![img](./img/img-2.png)

`Material icon theme`

Esta extensión lo que hace es agregar un icono a nuestros archivos para que sean más fáciles de reconocer. Parece una pavada, pero a medida que nuestra aplicación crece irá siendo una extensión muy útil.

Para habilitar simplemente debes buscar en el apartado de extensiones "Material icon theme".

![img](./img/img-3.png)

resultado:

![img](./img/img-4.png)

`ESLint`

Esta es la extensión más importante de todas. La considero realmente sagrada. Nos va a ayudar en cualquier proyecto, inclusive con otras librerías o frameworks. Tanto create-react-app como ng new de Angular, traen configuraciones especiales de ESLint, las cuales nos van a marcar problemas de sintaxis y nos darán algo de información de que estamos escribiendo o haciendo mal, pero para ver esto, necesitaríamos de esta grandiosa extensión.

Para habilitar simplemente debes buscar en el apartado de extensiones "ESLint".

![img](./img/img-5.png)

resultado:

![img](./img/img-6.png)

`Auto close tag`

Aquí en React utilizaremos mucho los tags, por ende, esta extensión es súper útil. Tal y como lo menciona el propio nombre, lo que hace es cerrar de manera automática alguna etiqueta. Por ejemplo si escribimos `<div>`, a la hora de ingresar el mayor, que es el símbolo posterior a la "v", ya completa el resto `</div>`.

Para habilitar simplemente debes buscar en el apartado de extensiones "Auto close tag".

![img](./img/img-7.png)

[`subir`](#top)

---

---

<a id="item2"></a>

## `Instalación de dependencias`

Para trabajar en este proyecto vamos a tener que realizar la instalación de las dependencias, es decir, generar la carpeta "node_modules".

Para esto nos vamos a posicionar en nuestra terminal en el directorio `myapp`, ahí mismo es donde se encuentra nuestro `package.json`.
Una vez posicionados vamos a ejecutar el siguiente comando:

```
npm install
```

Al terminar la instalación ya podemos trabajar en la tarea.

---

---

<a id="item3"></a>

### `Homework`

`Ejercicio React`

- Crear un componente llamado `Equipo`

- Inyectar el componente en App.js y asegurarse que sea renderizado.

- El componente estará compuesto por un título `h1` con el nombre de una selección de básquet. También tendrá algunos datos extras que los pueden encerrar en etiquetas `<p>`. Algunos ejemplos: `"Posición, Partidos jugados, Ligas, etc".`
