# Documentación jurídica y licitaciones · Skills para empleados IA de IAbot.io

Organización de contratos, fuentes, plazos y expedientes con trazabilidad y revisión profesional.

Procedimientos abiertos y concretos para agentes IA, con entradas, criterios de revisión y entregables. Publicados por [IAbot.io](https://iabot.io), plataforma de empleados IA con memoria, aplicaciones y ordenador virtual Linux.

## Habilidades y uso

| Skill | Empleado en IAbot.io | Entrega que revisar |
| --- | --- | --- |
| [Matriz de obligaciones contractuales](skills/contract-obligation-matrix/SKILL.md) | un empleado de operaciones jurídicas | Matriz contractual de obligaciones, hitos y asuntos ambiguos. |
| [Dossier de investigación normativa](skills/legal-source-research-dossier/SKILL.md) | un empleado de documentación jurídica | Dossier de fuentes con alcance, citas, fechas y cuestiones abiertas. |
| [Lista administrativa de licitación](skills/tender-administrative-checklist/SKILL.md) | un empleado de preparación de licitaciones | Checklist por requisito con documento, vigencia y responsable. |
| [Registro revisable de plazos](skills/legal-deadline-register/SKILL.md) | un empleado de control de expedientes | Registro de plazos y cálculos con evidencia y estado de validación. |
| [Inventario de tratamientos de datos](skills/privacy-processing-inventory/SKILL.md) | un empleado de apoyo a privacidad | Inventario de tratamientos y mapa de información pendiente. |
| [Comparar versiones de contratos](skills/contract-version-comparison/SKILL.md) | un empleado de revisión documental jurídica | Cuadro de cambios con texto anterior, nuevo e impacto por revisar. |

## Instalación y uso en IAbot.io

```sh
npx skills add Iabot-io/legal-tender-skills --list
npx skills add Iabot-io/legal-tender-skills
```

En la plataforma, abre **Skills**, revisa la habilidad e impórtala con el ámbito adecuado. Adjunta sus entradas y da el encargo al empleado. Consulta [la guía de uso en IAbot.io](USO-EN-IABOT.md) para el recorrido completo.

## Ejemplos

- **Matriz de obligaciones contractuales:** «Prepara una matriz de obligaciones de este contrato con la cláusula exacta de cada una.»
- **Dossier de investigación normativa:** «Localiza fuentes oficiales sobre esta cuestión y entrega citas comprobables, sin inventar jurisprudencia.»
- **Lista administrativa de licitación:** «Prepara la lista administrativa de esta licitación y distingue documentos exigidos de recomendaciones.»

## Herramientas y límites

Necesita documentos autorizados y acceso a fuentes oficiales. La habilidad prepara información y borradores; las interpretaciones y actuaciones jurídicas requieren la revisión correspondiente.

La colección no instala aplicaciones ni concede accesos. Las referencias se comprueban según la fecha, jurisdicción y alcance del encargo. Los resultados profesionales o administrativos conservan sus responsables y revisiones.

## Fuentes de referencia

- [Boletín Oficial del Estado](https://www.boe.es/)
- [Plataforma de Contratación del Sector Público](https://contrataciondelestado.es/)

Las fuentes orientan el método; su enlace no significa que una institución certifique o avale estas skills.

## Comprobación y licencia

```sh
python3 -m pip install -r scripts/requirements-validation.txt
python3 scripts/validate_skills.py
```

Se comprueban formato, recursos y referencias locales. Esa validación no acredita por sí sola un recorrido con un empleado real ni resultados en datos de producción. [Licencia MIT](LICENSE).

Agent Skills for AI employees and agents. Each skill includes an IAbot.io usage example and remains usable in compatible agents outside the platform.
