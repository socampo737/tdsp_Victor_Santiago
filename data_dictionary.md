NOMBRE CAMPOS;DESCRIPCIÓN
CICLO;Ciclo de facturación al que pertenece el cliente.
VPT;Toma los valores 0 y 1.
;Toma el valor 1 en caso de que una factura tenga alguno concepto vpt, 0 en caso contrario.
NUMERO_FACTURA_CLIENTE;Indica cuantas facturas lleva emitidas el cliente
BIRTHDAY_DAY_KEY;Fecha de nacimiento del cliente.
NUM_FACTURAS_DEV;Número de facturas devueltas por el cliente.
NACIONALIDAD;Nacionalidad del cliente
PORTABILIDAD;Tipo de portabilidad
TIPOCLIOPERDONANTE;Tipo de cliente en operador donante.
OPERADORDONANTE;Operador Donante
NUMLINACTIVAS;Número de líneas activas
NUMLINSOLICITADAS;Número de líneas solicitadas
GRUPORIESGO;Grupo de Riesgo
POSTAL_CODE_ID;Código postal
AMBITO;Descripción del segmento del cliente
CUST_CODE;Identificador único para cada cliente
IMPORTE_FACTURA_ORIGINAL;Importe total de la factura original con impuestos incluidos.
IMPORTE_PAGO_ANTICIPADO;Importe correspondientes a pagos anticipados, previos a la facturación 
METODO_PAGO;Método de pago del cliente.
FU;Indica si al clientes se le está facturando con Factura Única.
;Toma los valores 0, 1 y 2.
; - 0: Facturas que NO están catalogadas como Factura Única.
; - 1: Facturas catalogadas como Factura Única.
; - 2: Casuísticas especiales en las que la factura está catalogada por ejemplo  como Factura única y además  OCC.
FECHA_SALIDA_DEUDA;Fecha de salida de la factura del pari.
;En el caso de que haya facturas rectificadas será la última fecha de salida de deuda de las fechas de salida de la original y sus rectificadas.
;En caso de estar actualmente en deuda toma el valor 99990101.
;Si el cliente paga el mismo día que nos llega la devolución, el campo tomará como valor 0. Por lo que si este campo toma el valor 0 y la fecha de devolución no es del último día hábil, la factura estará al corriente.
DIAS_ESTADO_IMPAGO;Días que ha permanecido en deuda la factura.
;Depende de la fecha de ejecución del informe en los casos en los que la factura no haya salido de deuda.
;Si no tiene entrada en PARI, se asumen 2 días en estado DEVOLUCIÓN.
SW_HA_SIDO_DEV;Toma los valores 0 y 1.
;Toma el valor 1 en caso de que una factura haya pasado por la tabla de devoluciones, 0 en caso contrario.
SW_RECOBRO_TOTAL;Toma los valores 0 y 1.
;Toma el valor 1 en caso de que la factura se haya recobrado el total de la factura, 0 en caso contrario.
CUSTOMER_END_DAY_KEY;Fecha de baja del cliente. Si toma el valor 99991231, el cliente está activo todavía.
GENDER_DES;Genero de cliente
TIPO DE ALTA;Clasificacion de el tipo de alta, si pertenece a alta de migracion o alta de scoring
SCORING O PUNTUACION;Calificacion de cliente de acuerdo al comportamiento de pago
MAX DIAS IMPAGO;Maximo de dias que el cliente no ha pagado
FINANCIACION;Financiacion de la deuda cliente
ESTADO_CLIENTE;Indica si el cluente esta activo o inactivo
DOLPHIN;Identifica si el cliente posee terminal con la compañía
TIPO_FASE;Fase de acuerdo a los dias de mora en las que se encuentra la deuda
PORTADO;Indica si el cliente se ha portado o no
ESCENARIO_RECOBRO;Indica el segmento en el que se encuentra el cliente ya sea PER, FU, EMP
DEUDA_TOTAL;Deuda todal del cliente
;
;
;
;
;
;
;
;
;
;
