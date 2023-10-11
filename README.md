# Cálculo de Índice de Densidad del Estado (IDE)

Esta es una primera versión del cálculo de indicador Densidad del Estado (IDE), cuyas operaciones realizadas se encuentran en el notebook "Cálculo del IDE" de la carpeta "indicador_ide". Se realizó el cálculo del IDE por departamento para los años 2017, 2020 y 2022.

Se usó la metodología planteada por el PENUD recuperado en el siguiente enlace: https://www.undp.org/es/peru/publications/el-reto-de-la-igualdad#

El IDE se calcula promediando 5 indicadores:

- Índice de salud (i_salud): Tasa de médicos por habitante. El cual se calcula como la cantidad de médicos por departamento multiplicado por 10000. Este indicador se calcula tomando la población proyectada por el INEI y la información publicada por el INEI de médicos colegiados por departamento (tiene como fuente el Colegio Médico del Perú). Cabe precisar que solo se cueta con información hasta el 2020, por lo cual en el cálculo del IDE para el 2022 se tomó el valor del 2020.
/
- Índice de educación (i_educacion): Porcentaje de población de 12 a 16 años matriculado en educación secundaria. Se toma como fuente al MINEDU, la información es extraída desde su portal estadístico ESCALE.
/
- Índice de saneamiento(i_saneamiento): Porcentaje de viviendas con acceso a agua e instalaciones sanitarias. Se calcula usando la base de datos de la Encuesta Nacional de Programas Presupuestales (ENAPRES), considerando que el INEI presenta la información de acceso a estos servicios desde esta encuenta en lugar de la Encuesta Nacional de Hogares (ENAHO)
/
- Índice de electrificación(i_electricidad): Porcentaje de viviendas que cuentan con alumbrado eléctrico. Se calcula usando la base de datos de la Encuesta Nacional de Hogares (ENAHO), considerando que el INEI presenta la información de acceso a este servicio desde esta encuenta.
/
- Índice de indentidad (i_dni): Porcentaje de población con DNI. Se calcula usando la base de datos de la Encuesta Nacional de Programas Presupuestales (ENAPRES) 

