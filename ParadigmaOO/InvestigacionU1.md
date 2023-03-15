# Investigación Unidad 1: Paradigma Orientado a Objetos
---

## 1. Definición de Paradigma en el contexto de lenguajes de programación

Cuando se habla de un paradigma implementado en el mundo de la programación, habla del estilo de desarrollo del código. Se le puede considerar como una propuesta tecnológica que es adoptada como núcleo central para resolver los problemas ya delimitados con los que se trabaja.

## 2. Definición de Programación Orientada a Objetos, ¿Cuál fue el primer lenguaje orientado a objetos, quienes y en dónde lo propusieron?

- La programación orientada a objetos es un paradigma de la programación que busca obtener resultados a través de la modularidad. ésta utiliza **objetos** como elemento básico para la construcción del código y entre sus beneficios es ser:
	- reutilizable
	- organizable
	- sencillo de mantener
- Simula fue el primer lenguaje orientado a objetos a través de la creación de clases; fue creado por Ole Johan Dahl y kristen Nygaard en 1962 a través de la Conferencia de Trabajo en Lenguajes de Simulación IFIO TC 2, Lysebu, cerca de Oslo.

## 3. Define con tus palabras el concepto de abstracción, ¿Por qué se considera fundamental en programación?

Se puede pensar de la abstracción como un medio por el cual se puede extraer características genéricas, replicables y enlistables de un objeto, ser o evento por el cual se pueda prefabricar; a través de ese pensamiento se puede razonar que su importancia recae en la reutilización y optimización de los programas en los que se vaya o se pueda aplicar.

## 4. Explica el concepto de encapsulamiento, busca dos imágenes que te ayuden a describir el concepto, una que tenga algún sistema sin encapsulamiento y otra donde sí lo tenga. Menciona porque es importante y qué problemas puede evitar.

Se puede definir el encapsulamiento como la limitación y/o organización privada de una propiedad a un elemento; o sease, al momento de tener una clase, por ejemplo: sus métodos o sus variables pueden definirse como internas de la propia clase e invisibles para otras clases.

![](https://user-images.githubusercontent.com/126355162/225208657-48b596bc-fbde-42b5-b3e5-85a3ff67b164.png)
> figura 1, representación de un encapsulado
```c#
public Contacto BuscarContactoPor(
	string nombre,
	string direccion,
	int estado,
	int pais,
	string email,
	string empresa,
	string telefono)
{
    // código del método
} 
```
> figura 2, representación de una clase no encapsulada
## 5. Describe con tus palabras el concepto de herencia e ilustra el concepto con imágenes.

Cuando uno hace referencia a la herencia en la programación, uno tiene que entender que el objeto padre y el objeto hijo tienen el mismo comportamiento o las mismas propiedades. Más el hijo tiene más propiedades o menos de los que tiene el padre, pero que cumplen con contar con las similitudes para ser emparentados o que estén estrechamente relacionados bajo la necesidad de definirse entre sí.
![](https://user-images.githubusercontent.com/126355162/225209459-94a63642-1b01-4565-99a0-128e3f62c867.png)
> figura 3, diagrama de un vehículo
# UML: Diagrama de clases

## 1. Investiga la historia y haz un resumen del Lenguaje de Modelado Unificado, donde se mencione: quienes son sus principales autores (Booch, Rumbaugh, Jacobson), en que tipo de sistemas se utiliza, que tan utilizado es en años recientes, en particular el Diagrama de Clases. Menciona algunas de las herramientas para el modelado en UML. ¿Sabes de alguna empresa local que utilice este lenguaje?

- UML o Lenguaje de Modelado Unificado es un modelo utilizado para visualizar, construir y documentar el como funciona un programa a través de clases y las interacciones de las mismas entre sí.
- Fue creado por Grady Booch, James Rumbaugh y Ivar Hjalmar Jacobson
- Tiene tres principales sistemas que utiliza
	- Modelo funcional: centrado en la funcionalidad a través de la visión del usuario
	- Modelo de Objetos: representa la estructura desde la base de la programación orientada a objetos a través de atributos, objetos y asociaciones.
	- Modelo dinámico: Describen el comportamiento del sistema a través de distintos diagramas descriptivos por los cuales se subdividen las distintas partes del sistema.
- En la actualidad UML ha envejecido no precisamente bien, pero este si fue utilizado por lo menos por empresas de gran calibre relacionadas con la tecnología; véase Microsoft, Apple o IBM.
- Entre las herramientas más populares para la creación de diagramas UML, se encuentra draw.io y Microsoft Visio.

## 2. Escribe una propuesta de una máquina que venda distintos artículos y haz el diagrama de clases del sistema que propones. Recuerda que puede haber composición (un teclado se compone de botones) y generalización (tipo de productos, tipo de pago).
La máquina cuenta con los distintos métodos que hacen llamar dependiendo la cantidad de productos y la suma interna de estos al momento de elegir el precio, ya sea en dólar o en peso mexicano bajo un precio fijo base que esta en MXN, y del cual se extrae al momento de mandar operar la máquina

![image](https://user-images.githubusercontent.com/126355162/225214637-f7861bbf-ef45-479e-a305-0a8b74ea8826.png)
