# Calculadora de Palés — Streamlit v6

Corrección del contraste de los botones en modo claro.

- «ATRÁS»: fondo blanco, borde oscuro y texto negro.
- «CONTINUAR / CALCULAR PESO NETO»: fondo azul, texto blanco.
- Se utilizan los tipos nativos `primary` y `secondary` de Streamlit y selectores sobre el botón real, evitando el problema de estilos que no se aplicaban al HTML generado.
- El modo oscuro mantiene el diseño anterior.
