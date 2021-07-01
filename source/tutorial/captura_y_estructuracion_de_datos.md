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

Un predio siempre está asociado al menos a una persona (natural o jurídica), la cual es denominada como **Interesado** o **Agrupación de interesados** a lo largo de este tutorial. En esta sección se describe el procedimiento para registrar cada uno de los interesados y agrupaciones de interesados asociados a uno o más predios, de manera que se sugiere tener en cuenta los siguientes datos de referencia:

### Tabla Interesados

| Descripción          |   Interesado 1    | Interesado 2 | Interesado 3  |
| -------------------- | :---------------: | :----------: | :-----------: |
| **Nombre**           |      Carlos       |    Camila    | Inversiones C |
| **Apellidos**        |       Casas       |   Cárdenas   |               |
| **Tipo documento**   | Cédula Ciudadanía |  Secuencial  |      NIT      |
| **Número documento** |    1032463643     |  1042477540  |  882734323-1  |
| **Tipo**             |      Natural      |   Natural    |   Jurídica    |

### Tabla Agrupación de interesados

| Campo             | Valor          |
| :---------------: | :------------: |
| Interesado 1      | 50%            |
| Interesado 2      | 30%            |
| Interesado 3      | 20%            |
| Tipo              | Grupo civil    |
| Nombre Agrupación | Asociación ASI |

### Paso 1: Crear interesado

En el botón ``Crear objetos de Levantamiento`` selecciona la opción **Crear Interesado**.

<a class="" data-lightbox="Paso 1: Crear interesado" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados2.gif" title="Paso 1: Crear interesado" data-title="Paso 1: Crear interesado"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados2.gif" class="align-center" width="800px" alt="Paso 1: Crear interesado"/></a>

### Paso 2: Selección del método de creación del interesado

Se desplegará un cuadro de diálogo con dos opciones para crear interesados: *Ingresando datos manualmente en un formulario* o *Desde una capa de QGIS (definiendo un mapeo de campos)*. Para este caso, selecciona la primera opción y presiona el botón `Crear`.

<a class="" data-lightbox="Paso 2: Seleccion del método de creación del interesado" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados3.gif" title="Paso 2: Seleccion del método de creación del interesado" data-title="Paso 2: Seleccion del método de creación del interesado"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados3.gif" class="align-center" width="800px" alt="Paso 2: Seleccion del método de creación del interesado"/></a>

### Paso 3: Diligenciamiento de formulario interesados

Se desplegará un formulario que debe ser diligenciado con la información correspondiente de acuerdo a los datos de referencia proporcionados en la [tabla de interesados](#tabla-interesados) que se encuentra al inicio de esta sección.

<a class="" data-lightbox="Paso 3: Diligenciamiento de formulario interesados" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados4.gif" title="Paso 3: Diligenciamiento de formulario interesados" data-title="Paso 3: Diligenciamiento de formulario interesados"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados4.gif" class="align-center" width="800px" alt="Paso 3: Diligenciamiento de formulario interesados"/></a>

## Crear Agrupación De Interesados

<div class="warning">
<p class="admonition-title">ADVERTENCIA</p>
<p>Antes de iniciar con este proceso, deben haberse creado todos los interesados presentes en la <a class="reference external" href="#tabla-interesados">tabla de interesados</a>.</p>
</div>


### Paso 1: Crear Agrupación de Interesados

En el botón ``Crear objetos de Levantamiento`` selecciona la opción **Crear Agrupación de Interesados**.

<a class="" data-lightbox="Paso 1: Crear Agrupación de interesados" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados6.gif" title="Paso 1: Crear Agrupación de interesados" data-title="Paso 1: Crear Agrupación de interesados"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados6.gif" class="align-center" width="800px" alt="Paso 1: Crear Agrupación de interesados"/></a>

### Paso 2: Diligenciamiento de formulario Agrupación de interesados

Se desplegará un formulario que debe ser diligenciado con la información correspondiente de acuerdo a los datos de referencia proporcionados en la [tabla agrupación de interesados](#tabla-agrupacion-de-interesados) que se encuentra al inicio de esta sección. Debes especificar el nombre y el tipo de agrupación, seleccionando los tres (3) interesados creados y por medio del botón ![Trasladar a la derecha](../_static/tutorial/captura_y_estructura_de_datos/ICOtrasladarderecha.png) para que sean registrados en la agrupación.

<a class="" data-lightbox="Paso 2: Diligenciamiento de formulario Agrupación de interesados" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados7.gif" title="Paso 2: Diligenciamiento de formulario Agrupación de interesados" data-title="Paso 2: Diligenciamiento de formulario Agrupación de interesados"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados7.gif" class="align-center" width="800px" alt="Paso 2: Diligenciamiento de formulario Agrupación de interesados"/></a>

### Paso 3: Asignación de porcentajes

Por último, debes asignar los porcentajes de derecho sobre el predio, teniendo en cuenta la [tabla agrupación de interesados](#tabla-agrupacion-de-interesados), seguido debes dar clic en el botón `Aceptar`.

<a class="" data-lightbox="Paso 3: Asignación de porcentajes" href="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados8.gif" title="Paso 3: Asignación de porcentajes" data-title="Paso 3: Asignación de porcentajes"><img src="../_static/tutorial/captura_y_estructura_de_datos/cap7interesados8.gif" class="align-center" width="800px" alt="Paso 3: Asignación de porcentajes"/></a>

## Fuentes

## RRR

### Crear Derecho