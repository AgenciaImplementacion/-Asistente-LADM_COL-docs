# Captura y Estructuración de Datos

## Preprocesamiento de insumos

## Consulta de dominios

## Paquete de topografía y representación

### Puntos de lindero

### Puntos de levantamiento

### Puntos de Control

### Linderos

### Construcción De Linderos

### Relación Entre Puntos y Linderos

## Unidad Espacial

### Creación De Terrenos y Sus Relaciones

#### Creación De Relacion Entre Los Linderos y Los Terrenos

### Creación De Construcciones

### Creación De Unidades De Construcción

## Unidad Básica Administrativa

### Crear Predio

## Interesados

Un predio siempre tiene asociado a una persona, a la cual llamaremos interesado puede ser natural o jurídico, inclusive puede ser un grupo de interesados, en esta sección se describirá como se debe registrar cada uno de los interesados y agrupaciones de interesados.

### Tabla Interesados

| Descripción          | Interesado 1      | Interesado 2     | Interesado 3     |
| -------------------- | :---------------: | :--------------: | :--------------: |
| **Nombre**           | Carlos            | Camila           | Inversiones C    |
| **Apellidos**        | Casas             | Cardenas         |                  |
| **Tipo documento**   | Cédula Ciudadanía | Secuencial       | NIT              |
| **Número documento** | 1032463643        | 1042477540       | 882734323-1      |
| **Tipo**             | Natural           | Natural          | Jurídica         |

### Tabla Agrupacion de interesados

| Campo             | Valor          |
| :---------------: | :------------: |
| Interesado 1      | 50%            |
| Interesado 2      | 30%            |
| Interesado 3      | 20%            |
| Tipo              | Grupo civil    |
| Nombre Agrupación | Asociación ASI |

### Paso 1: Crear interesado

En el botón ``Crear objetos de Levantamiento`` selecciona la opción Crear Interesado.

<a class="" data-lightbox="Paso 1: Crear interesado" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados2.gif" title="Paso 1: Crear interesado" data-title="Paso 1: Crear interesado"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados2.gif" class="align-center" width="800px" alt="Paso 1: Crear interesado"/></a>

### Paso 2: Seleccion del método de creación del interesado

Se desplegará un cuadro de diálogo con dos opciones para crear interesados: *Ingresando datos manualmente en un formulario* o *desde una capa de Qgis (definiendo un mapeo de campos)*. Para este caso, selecciona la primera opción y presiona el botón `Crear`.

<a class="" data-lightbox="Paso 2: Seleccion del método de creación del interesado" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados3.gif" title="Paso 2: Seleccion del método de creación del interesado" data-title="Paso 2: Seleccion del método de creación del interesado"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados3.gif" class="align-center" width="800px" alt="Paso 2: Seleccion del método de creación del interesado"/></a>

### Paso 3: Diligenciamiento de formulario interesados

Se desplegará un formulario que debe ser diligenciado con la información correspondiente de acuerdo a los datos de referencia proporcionados en la [tabla interesados](#tabla-interesados) que se encuentra al inicio de esta sección.

<a class="" data-lightbox="Paso 3: Diligenciamiento de formulario interesados" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados4.gif" title="Paso 3: Diligenciamiento de formulario interesados" data-title="Paso 3: Diligenciamiento de formulario interesados"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados4.gif" class="align-center" width="800px" alt="Paso 3: Diligenciamiento de formulario interesados"/></a>

## Crear Agrupación De Interesados

<div class="warning">
<p class="admonition-title">ADVERTENCIA</p>
<p>Antes de iniciar con este proceso, debe haberse creado todos los interesados presentes en la <a class="reference external" href="#tabla-interesados">tabla de Interesados</a>.</p>
</div>

### Paso 1: Crear Agrupación de interesados

En el botón ``Crear objetos de Levantamiento`` selecciona la opción Crear Agrupación de Interesados.

<a class="" data-lightbox="Paso 1: Crear Agrupación de interesados" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados6.gif" title="Paso 1: Crear Agrupación de interesados" data-title="Paso 1: Crear Agrupación de interesados"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados6.gif" class="align-center" width="800px" alt="Paso 1: Crear Agrupación de interesados"/></a>

### Paso 2: Diligenciamiento de formulario Agrupación de interesados

Se desplegará un formulario que debe ser diligenciado con la información correspondiente de acuerdo a los datos de referencia proporcionados en la [tabla agrupación interesados](#tabla-agrupacion-de-interesados) que se encuentra al inicio de esta sección.Deberás añadir el nombre y el tipo de agrupación, seleccionando los 3 interesados creados y por medio del botón ![Trasladar a la derecha](../_static/tutorial/captura_y_estructura_de_datos/ICOtrasladarderecha.png). los añades como a la agrupación.

<a class="" data-lightbox="Paso 2: Diligenciamiento de formulario Agrupación de interesados" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados7.gif" title="Paso 2: Diligenciamiento de formulario Agrupación de interesados" data-title="Paso 2: Diligenciamiento de formulario Agrupación de interesados"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados7.gif" class="align-center" width="800px" alt="Paso 2: Diligenciamiento de formulario Agrupación de interesados"/></a>

### Paso 3: Asignación de porcentajes

Por ultimo, debes asignar los porcentajes de derecho sobre el predio, teniendo en cuenta la [tabla agrupación interesados](#tabla-agrupacion-de-interesados), seguido debes dar clic en el botón `Aceptar`.

<a class="" data-lightbox="Paso 3: Asignación de porcentajes" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados8.gif" title="Paso 3: Asignación de porcentajes" data-title="Paso 3: Asignación de porcentajes"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados8.gif" class="align-center" width="800px" alt="Paso 3: Asignación de porcentajes"/></a>

## Fuentes

## RRR

### Crear Derecho