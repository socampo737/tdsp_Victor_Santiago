NOMBRE�CAMPOS;DESCRIPCI�N
CICLO;Ciclo de facturaci�n al que pertenece el cliente.
VPT;Toma los valores 0 y 1.
;Toma el valor 1 en caso de que una factura tenga alguno concepto vpt, 0 en caso contrario.
NUMERO_FACTURA_CLIENTE;Indica cuantas facturas lleva emitidas el cliente
BIRTHDAY_DAY_KEY;Fecha de nacimiento del cliente.
NUM_FACTURAS_DEV;N�mero de facturas devueltas por el cliente.
NACIONALIDAD;Nacionalidad del cliente
PORTABILIDAD;Tipo de portabilidad
TIPOCLIOPERDONANTE;Tipo de cliente en operador donante.
OPERADORDONANTE;Operador Donante
NUMLINACTIVAS;N�mero de l�neas activas
NUMLINSOLICITADAS;N�mero de l�neas solicitadas
GRUPORIESGO;Grupo de Riesgo
POSTAL_CODE_ID;C�digo postal
AMBITO;Descripci�n del segmento del cliente
CUST_CODE;Identificador �nico para cada cliente
IMPORTE_FACTURA_ORIGINAL;Importe total de la factura original con impuestos incluidos.
IMPORTE_PAGO_ANTICIPADO;Importe correspondientes a pagos anticipados, previos a la facturaci�n 
METODO_PAGO;M�todo de pago del cliente.
FU;Indica si al clientes se le est� facturando con Factura �nica.
;Toma los valores 0, 1 y 2.
; - 0: Facturas que NO est�n catalogadas como Factura �nica.
; - 1: Facturas catalogadas como Factura �nica.
; - 2: Casu�sticas especiales en las que la factura est� catalogada por ejemplo  como Factura �nica y adem�s  OCC.
FECHA_SALIDA_DEUDA;Fecha de salida de la factura del pari.
;En el caso de que haya facturas rectificadas ser� la �ltima fecha de salida de deuda de las fechas de salida de la original y sus rectificadas.
;En caso de estar actualmente en deuda toma el valor 99990101.
;Si el cliente paga el mismo d�a que nos llega la devoluci�n, el campo tomar� como valor 0. Por lo que si este campo toma el valor 0 y la fecha de devoluci�n no es del �ltimo d�a h�bil, la factura estar� al corriente.
DIAS_ESTADO_IMPAGO;D�as que ha permanecido en deuda la factura.
;Depende de la fecha de ejecuci�n del informe en los casos en los que la factura no haya salido de deuda.
;Si no tiene entrada en PARI, se asumen 2 d�as en estado DEVOLUCI�N.
SW_HA_SIDO_DEV;Toma los valores 0 y 1.
;Toma el valor 1 en caso de que una factura haya pasado por la tabla de devoluciones, 0 en caso contrario.
SW_RECOBRO_TOTAL;Toma los valores 0 y 1.
;Toma el valor 1 en caso de que la factura se haya recobrado el total de la factura, 0 en caso contrario.
CUSTOMER_END_DAY_KEY;Fecha de baja del cliente. Si toma el valor 99991231, el cliente est� activo todav�a.
GENDER_DES;Genero de cliente
TIPO DE ALTA;Clasificacion de el tipo de alta, si pertenece a alta de migracion o alta de scoring
SCORING O PUNTUACION;Calificacion de cliente de acuerdo al comportamiento de pago
MAX DIAS IMPAGO;Maximo de dias que el cliente no ha pagado
FINANCIACION;Financiacion de la deuda cliente
ESTADO_CLIENTE;Indica si el cluente esta activo o inactivo
DOLPHIN;Identifica si el cliente posee terminal con la compa��a
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
