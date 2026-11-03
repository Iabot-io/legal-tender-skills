---
name: contract-obligation-matrix
description: Extraer obligaciones contractuales con responsables, condiciones y evidencia de cumplimiento. En IAbot.io, asígnala a un empleado de operaciones jurídicas y aporta contrato, anexos, modificaciones y contexto de seguimiento.
license: MIT
metadata:
  author: IAbot.io
  version: 0.1.0
  sector: Documentación jurídica y licitaciones
---

# Matriz de obligaciones contractuales

## Uso en IAbot.io

Asigna esta skill a **un empleado de operaciones jurídicas** desde la biblioteca Skills de [IAbot.io](https://iabot.io). Aporta contrato, anexos, modificaciones y contexto de seguimiento.

**Ejemplo de encargo:** «Prepara una matriz de obligaciones de este contrato con la cláusula exacta de cada una.»

**Resultado a revisar:** Matriz contractual de obligaciones, hitos y asuntos ambiguos.

## Cuándo usarla y qué necesita

Extraer obligaciones contractuales con responsables, condiciones y evidencia de cumplimiento

Trabaja con contrato, anexos, modificaciones y contexto de seguimiento. Necesita documentos autorizados y acceso a fuentes oficiales. La habilidad prepara información y borradores; las interpretaciones y actuaciones jurídicas requieren la revisión correspondiente.

## Procedimiento

1. Fija partes, versión y orden de documentos contractuales y sus modificaciones.
2. Extrae obligaciones, facultades y condiciones distinguiendo quién debe hacer qué y cuándo.
3. Relaciona cada obligación con cláusula y anexo; conserva ambigüedades y contradicciones.
4. Propón responsables operativos y evidencias de seguimiento sin decidir la interpretación jurídica.
5. Entrega una matriz revisable y separa tareas de seguimiento de notificaciones formales.

## Comprobación del resultado

- No se transforma una facultad en obligación.
- Las fechas condicionadas conservan el hecho desencadenante.
- La versión y cláusula se pueden localizar en el original.

## Entrega

Matriz contractual de obligaciones, hitos y asuntos ambiguos.

Conserva la identidad y revisión de las fuentes utilizadas. Señala los datos pendientes que afecten al resultado; no los sustituyas por valores inventados.

Usa [el registro de trabajo](assets/registro.csv) cuando no exista una plantilla del usuario; adapta sus filas sin perder las referencias.

## Referencias

- [Boletín Oficial del Estado](https://www.boe.es/)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)
