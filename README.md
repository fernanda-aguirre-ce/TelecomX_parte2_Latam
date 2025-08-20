# TelecomX_parte2_Latam
# Informe de Churn – TelecomX LATAM (versión estudiante)

---

## Resumen 

En este análisis vimos que el **churn** (clientes que cancelan) es de aproximadamente **25.7%**, lo que significa que de 7,267 clientes, **1,869 se dieron de baja**. El resto (74%) sigue activo. Esto muestra un desbalance moderado entre las clases.

### Modelos que probamos

* **Regresión Logística** (normalizada porque es sensible a la escala).
* **Random Forest** (no requiere normalización).

También trabajamos con técnicas de balanceo como **undersampling**, **oversampling** y **SMOTE**. Para modelos sensibles a escala, SMOTE funcionó mejor.

---

## Lo que encontramos

* **Clientes nuevos (tenure bajo)**: son los que más rápido se van.
* **Contrato mensual**: mucho más riesgoso que los contratos de 1 o 2 años.
* **Cargos mensuales altos**: aumentan la probabilidad de churn.
* **Gasto total bajo**: suele indicar que cancelaron temprano.
* **Sin seguridad online o sin soporte técnico**: más chances de irse.
* **Método de pago electronic check**: también se relaciona con más cancelaciones.

---

## Recomendaciones

* **Atacar los primeros meses** con bienvenida, seguimiento y ofertas iniciales.
* **Fomentar contratos largos** ofreciendo descuentos o beneficios por cambiar de mensual a anual.
* **Cuidar precios** evitando subidas bruscas y ofreciendo paquetes combinados.
* **Dar más valor** con pruebas gratis de seguridad y soporte.
* **Mejorar los pagos** migrando clientes de electronic check a débito automático o tarjeta.


