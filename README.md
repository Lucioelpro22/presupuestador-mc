# Presupuestador MC

Presupuestos de gas, plomería y destapaciones en pesos argentinos. Descargá y abrí `index.html` en un navegador con almacenamiento local habilitado. Funciona sin servidor ni instalación.

1. Cargá cliente, alcance, fecha, vigencia y condiciones de pago.
2. Agregá una fila por material e indicá cantidad, unidad y costo unitario. Para un trabajo de mano de obra solamente, dejá la lista vacía.
3. Sumá mano de obra, traslado y el porcentaje de recargo sobre el costo total.
4. Tocá **Guardar y ver presupuesto**. Revisá la hoja del cliente y elegí **Imprimir / Guardar PDF**. En el diálogo de impresión podés elegir A4 y desactivar los encabezados y pies que agregue el navegador.

La hoja del cliente muestra el número, el alcance, los materiales y sus cantidades, el total final y las condiciones. El detalle de costos y el porcentaje de recargo son internos. Podés cargar un logo PNG o JPG de hasta 300 KB por presupuesto. Si lo omitís en uno nuevo se imprime la marca MC.

## Cálculo

Un ejemplo con 2,5 m a $1.200,40 por metro, mano de obra de $10.000 y traslado de $1.000 da $14.001 de costo. Con un recargo del 20 %, el total es **$16.801,20**. Cada renglón de materiales se redondea a centavos antes de sumar.

## Historial

Los números son consecutivos dentro del historial de ese navegador. Editar conserva el número. Buscá por número, cliente o trabajo. Para conservar registros anteriores, actualizá el archivo en la misma ubicación y abrilo con el mismo navegador y perfil. La disponibilidad del almacenamiento para archivos locales depende del navegador. Las cotizaciones anteriores conservan su importe de materiales como un único lote. Al editarlas, completá los campos nuevos.

Los registros y logos quedan en ese dispositivo. Si borrás los datos del navegador podés perder el historial. Guardá el PDF de cada presupuesto que entregues.
