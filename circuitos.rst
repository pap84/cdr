#################################
Circuitos para equipos de rayos X
#################################

Circuito con rectificación de onda media
========================================

Para lograr la diferencia de potencial deseada entre el ánodo y el cátodo se utiliza un transformador (ver **Figura 5**), que permite regular la tensión entre éstos. En la práctica, también, se suele agregar al circuito un autotransformador y un reóstato que permiten regular la tensión hasta el valor requerido.

.. figure:: img/circuitos_1.png
    :align: center

    **Figura 5:** Tubo con transformador.

Al tratarse de tensión alterna, las polaridades del ánodo y el cátodo cambian cíclicamente. Así, solo cuando el ánodo es positivo existe corriente entre ánodo y cátodo y se generan rayos X, ya que cuando el ánodo es negativo éste no atraerá electrones y éstos no impactarán sobre él. Esto generará un haz de rayos X solo durante los intervalos de tiempo en los que exista corriente entre las partes, o más bien en los momentos en los que el ánodo se encuentre con polaridad positiva.

En la **Figura 6** se puede observar cualitativamente lo indicado. Primero (arriba) el comportamiento de la tensión en el ánodo; segundo (medio) la corriente generada por este comportamiento en el tubo; y, finalmente, la itensidad del haz de rayos X generado (abajo). Esta última dependerá de la corriente pero también será moderada por la tensión, provocando un pico más pronunciado que el de la corriente.

.. figure:: img/media_onda.png
    :align: center

    **Figura 6:** Intensidad debida a circuito de media onda (normalizada al máximo).

Los *circuitos de rectificación de onda media* incorporan una válvula rectificadora intercalada en serie con el tubo de rayos X. Esto impide la emisión de electrones del ánodo al cátodo, en caso de que la temperatura del ánodo alcance valores suficientes para generación de electrones libres.

Circuito con rectificación de onda completa
===========================================

Al variar la corriente, como se vio en el caso anterior, disminuye la producción de rayos X en el tiempo y la eficiencia del equipo. Por esto, es deseable configurar un sistema tal que permita obtener polarización positiva del ánodo para todo tiempo. De esta forma se obtendría una corriente contínua y, como consecuencia, se obtendría un haz de rayos X contínuo.

Para solucionar este problema, se utilizan circuitos como el de Graetz (ver **Figura 7**), donde:

* cuando A es negativo: los electrones recorren el camino ACDEB, y
* cuando A es positivo: los electrones recorren el camino BCDEA.

.. figure:: img/circuito_2.png
    :align: center

    **Figure 7:** Circuito de rectificación de onda completa.

De esta forma se obtiene una corriente contínua y, por consiguiente una intensidad continua del haz de rayos X, como se muestra en la **Figura 8**.

.. figure:: img/onda_completa.png
    :align: center

    **Figura 8:** Intensidad debida a circuito de onda completa (normalizada al máximo).
