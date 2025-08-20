# TelecomX_parte2_Latam
# Informe de Churn – TelecomX LATAM

---

## 1) Resumen rápido

* **Churn:** \~25.7% (1,869 de 7,267 clientes). Desbalance moderado (74% siguen, 26% cancelan).
* **Modelos probados:**

  * **Regresión Logística** (con normalización).
  * **Random Forest** (sin normalización).
* **Balanceo:** probamos undersampling, oversampling y SMOTE. Para modelos sensibles a escala, lo mejor es SMOTE.

---

## 2) Qué encontramos

1. **Clientes nuevos (tenure bajo)** se van más rápido.
2. **Contrato mensual** → mucho más riesgo que 1–2 años.
3. **Cargos mensuales altos** aumentan churn.
4. **Gasto total bajo** suele indicar cancelación temprana.
5. **Sin seguridad online o soporte técnico** → más probabilidad de irse.
6. **Pago con electronic check** también aparece asociado a más cancelaciones.

---

##  Recomendaciones simples

* **Atacar los primeros meses:** bienvenida, seguimiento, ofertas iniciales.
* **Incentivar contratos largos:** descuentos o beneficios por pasar de mensual a anual.
* **Manejar precios:** evitar aumentos bruscos, ofrecer bundles.
* **Aumentar valor percibido:** dar pruebas de seguridad/soporte gratis al inicio.
* **Reducir fricción en pagos:** migrar clientes de electronic check a débito/tarjeta.

---
## 6) Próximos pasos

* Medir AUC/ROC y calibrar probabilidades.
* Ajustar hiperparámetros (C en LR, profundidad y estimadores en RF).
* Usar SHAP o permutaciones para explicar drivers con más claridad.
* Integrar el score de churn en CRM para activar alertas de retención.
