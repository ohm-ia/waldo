# Tarjeta digital de Waldo Gallardo

Esta carpeta tiene dos archivos importantes:

- **index.html**: la página que se abre al escanear el QR.
- **contacto.vcf**: el contacto que se guarda en el teléfono con el botón "Guardar contacto".

## Cómo cambiar los datos

1. En GitHub, abre `index.html` y toca el ícono del lápiz (Editar).
2. Busca la parte que dice **DATOS DE LA TARJETA** (está al principio).
3. Cambia solo lo que está entre comillas. Si dejas algo vacío (""), no aparece en la página.
4. Para mostrar los datos de transferencia, completa la sección `transferencia`. Aparece solo si `numeroCuenta` tiene algo.
5. Guarda con el botón verde **Commit changes**. En uno o dos minutos la página se actualiza.

Si cambias el teléfono o el nombre, cámbialos también en `contacto.vcf`, que es el contacto que se guarda en la agenda.

El QR no cambia nunca: siempre apunta a la misma dirección de la página.
