# Contratos

Los contratos son acuerdos formales registrados en el sistema que vinculan a la empresa con clientes o agentes de aduanas para la gestión de importaciones, exportaciones y logística.

Cada contrato permite documentar:

- Condiciones comerciales
- Tarifas aplicadas
- Términos de pago
- Servicios incluidos

Todo cumpliendo con la normativa local y los procedimientos aduaneros.

---

## Crear un Nuevo Contrato

Para crear un nuevo contrato:

1. Haga clic en **Nuevo**.
2. El sistema solicitará ingresar:
   - **Importadora**
   - **Almacén**
   - **Fecha del Contrato**

> 📷 Captura de pantalla: Ventana de creación de nuevo contrato con los campos de importadora, almacén y fecha.

Al crear un nuevo contrato, este queda inicialmente en estado **"Borrador"** y el sistema despliega automáticamente la vista de detalles para completar su información.

---

## Vista de Detalle del Contrato

La vista de detalle permite ingresar, revisar y actualizar todos los datos necesarios para que el contrato quede correctamente registrado y vinculado.

Los campos principales son:

| Campo | Descripción |
|---|---|
| **Número de Contrato** | Generado automáticamente por la secuencia del sistema |
| **Fecha del Contrato** | Fecha de creación del contrato |
| **Fecha Autorizada** | Fecha en que el contrato fue formalmente autorizado |
| **Número de Autorización** | Referencia oficial de autorización |
| **Referencia** | Número de referencia interno o externo |
| **Método de Transporte** | Marítimo o aéreo |
| **Costos Asociados** | Costos de transporte y manejo |
| **Líneas del Contrato** | Productos incluidos en el contrato (pueden importarse y exportarse en bloque) |

> 📷 Captura de pantalla: Vista de detalle del contrato mostrando todos los campos y la tabla de líneas con los productos incluidos.

---

## Liberación y Vista Previa del Contrato

Una vez que la información del contrato esté completa, este puede ser **liberado**.

Tras la liberación, es posible obtener una vista previa a través del **Informe de Contrato**, el cual muestra:

- Productos
- Fechas
- Autorizaciones
- Referencias
- Método de transporte
- Costos

> 📷 Captura de pantalla: Vista previa del Informe de Contrato con el documento formateado y todos sus detalles.

---

## Aprobación del Contrato

{% hint style="danger" %}
**Esta operación es irrevocable.** Una vez que el contrato ha sido aprobado, no puede revertirse al estado Borrador.
{% endhint %}

Para aprobar el contrato, haga clic en el botón **Aprobar**.

El estado del contrato cambiará de **"Borrador"** a **"Aprobado"**.

Tras la aprobación:

- El contrato queda visible en **P4 Warehouse** con el **número de orden de compra** asociado.
- Se mantiene trazabilidad y control completo del contrato en ambos sistemas.

> 📷 Captura de pantalla: Contrato aprobado mostrando el cambio de estado y el número de orden de compra en P4 Warehouse.

---

## Iniciar el Proceso de Recepción en P4 Warehouse

Una vez aprobado el contrato, diríjase a **P4 Warehouse** para iniciar la recepción de la mercancía:

1. Ingrese al módulo **Entrada**.
2. Abra la sección **Órdenes de Compra**.
3. Localice la orden de compra asociada al contrato aprobado.
4. Inicie el proceso de recepción.

> 📷 Captura de pantalla: Módulo Entrada de P4 Warehouse mostrando la lista de Órdenes de Compra con la orden vinculada.

---

**Siguiente:** [Historia – Órdenes de Compra Recibidas](historia.md) · **Luego:** [Facturas](../egreso/facturas.md)
