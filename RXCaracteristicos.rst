#######################
Rayos X característicos
#######################

Los rayos X característicos son el resultado de la interacción Coulombiana entre los electrones incidentes y los electrones orbitales del material (típicamente de alto número atómico Z) que constituye el blanco (ánodo). En términos de física atómica, este proceso se considera *pérdida por colisión* (*collision loss*).

Cuando ocurre un evento de interacción Coulombiano entre un electrón incidente y un electrón orbital del material del ánodo, la energía transferida al electrón orbital resulta suficiente para eyectarlo de la capa atómica (*shell*); constituyendo lo que se conoce en física atómica como *electrón Auger*, y consecuentemente un electrón de un nivel energético superior 'cae' y ocupa la vacancia creada. La diferencia de energía entre los estados (energías de ligadura) final e inicial (diferencia de energía de los niveles involucrados) es emitida por el átomo en forma de fotón característico (rayo X característico) o bien por medio de transferencia de energía cinética al electrón orbital eyectado (electrón Auger).

La probabilidad de producción fluorescente (:math:`w`) se define como la cantidad de fotones fluorescentes (característicos) emitidos por cada vacancia generada en una capa (0 :math:`\leq w \leq` 1). El valor de :math:`w` es muy próximo a 0 para elementos de bajo número atómico Z, alrededor de 0.5 para elementos intermedios (como cobre, Z=29) y alcanza valores muy cercanos a 1 (0.96) para las capas K (*K-shell*) de los elementos pesados (alto número atómico). Por este motivo, se emplean elementos pesados para construir los ánodos.

Los fotones emitidos por transiciones electrónicas entre diferentes niveles atómicos (capas) muestran una distribución discreta de energías en correspondencia con cada material del ánodo, donde ocurren las transiciones, y de aquí el concepto de '*radiación característica*'.

La energía de los fotones emitidos como rayos X característicos puede estimarse, según los niveles atómicos involucrados, a partir de la expresión:

.. math::
	E(n, l, j) = K \, h c \: \frac{M_Z}{M_Z + m_e} \left[ \frac{(Z - \sigma_A)^2}{n^2} + \frac{\alpha^2 \, (Z - \sigma_B)^4}{n^4}\,
	\left( \frac{n}{j + \frac{1}{2}} -\frac{3}{4}  \right) \right]

donde Z es el número atómico, :math:`M_Z` y :math:`m_e` son las masas del átomo y el electrón, respectivamente. Los coeficientes :math:`\sigma_A` y :math:`\sigma_B` representan los efectos por apantallamiento, total e interno; respectivamente y K = 109737.303 :math:`cm^{-1}` es la constante de Rydberg.

Así mismo puede estimarse la intensidad de emisión de radiación característica :math:`I_{r, s}` en la transición del estado :math:`r` al :math:`s` de acuerdo con:

.. math::
		I_{r, s} = N_0 \, F_r \, F_s \, \omega_r \, P_{r, s}

donde :math:`N_0` es el flujo de radiación incidente, :math:`F_j` representa la probabilidad de ionización para el nivel j del flujo incidente en el átomo Z irradiado, :math:`\omega_j` es la probabilidad de emisión de rayos X como consecuencia del proceso de ionización. Por último, :math:`P_{j, k}` es la probabilidad de transición del estado j al k.
