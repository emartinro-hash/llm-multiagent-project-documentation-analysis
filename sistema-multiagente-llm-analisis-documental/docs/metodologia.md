# Metodología de la prueba de concepto

La prueba de concepto se ha diseñado para validar una arquitectura multiagente aplicada al análisis documental de proyectos.

El sistema utiliza un corpus documental simulado formado por actas, registros de riesgos, incidencias, presupuestos, facturas y comunicaciones de proveedor. Sobre este corpus se aplica un enfoque RAG para recuperar evidencia relevante y alimentar posteriormente a los agentes de análisis y síntesis.

El flujo general es:

1. El usuario formula una consulta en lenguaje natural.
2. El supervisor activa el agente recuperador documental.
3. El recuperador localiza evidencia relevante en los documentos.
4. El analizador interpreta la evidencia recuperada.
5. El sintetizador redacta una respuesta ejecutiva orientada a PMO.

La implementación se ha realizado en Flowise para facilitar el prototipado visual y la documentación del flujo multiagente.
