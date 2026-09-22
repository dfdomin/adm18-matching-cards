# ADM18 — Tarjetas de Emparejamiento: Documentos ↔ Funciones

Juego de emparejamiento para la Semana 3 de ADM18 (Procesamiento de la Información — IUB/Unibarranquilla).

Caso integrador: **LatamBox S.A.**

## Objetivo

Que el estudiante asocie cada tipo de documento con su función principal, distinguiendo entre las 4 clases documentales de la GTC 185:2009:

- **Comercial** — registra transacciones económicas
- **Administrativo** — regula la comunicación y la coordinación (memorandos, actas, correos)
- **Legal** — tiene efecto jurídico
- **Técnico** — describe especificaciones operativas

## Criterio de clasificación (fuente: `adm18-material/semana-03/index.html`)

| Documento | Clase | Clave |
|---|---|---|
| Factura de Amazon | Comercial | semana-03 · "la factura de Amazon" |
| Cotización de flete | Comercial | semana-03 · "la cotización de servicios" |
| Guía aérea AWB | Técnico | semana-03 · "la guía aérea es un documento técnico" |
| Manual de procedimiento | Técnico | semana-03 · "el manual de procedimiento" |
| Memorando interno | Administrativo | semana-03 · "el memorando" |
| Acta de reunión | Administrativo | semana-03 · "el acta de reunión" |
| Encuesta de satisfacción | Administrativo | semana-14 (clave) · "queja → Clase: Administrativo" |
| Correo de nacionalización | Administrativo | **corregido**: semana-05 y semana-14 (claves) clasifican los correos como "Clase: Administrativo"; un correo es una comunicación |
| Declaración de valor | Legal | semana-03 · "la declaración aduanera" |
| Comprobante de impuestos | Legal | semana-03 · "el comprobante de impuestos" |

**Distribución:** Comercial 2 · Administrativo 4 · Legal 2 · Técnico 2.

> ⚠️ La clase sigue la **naturaleza del documento**, no su tema. El *correo de nacionalización* trata de aduana (parece Legal), pero como documento es una comunicación → Administrativo. Ese es el distractor intencional de la actividad.

## Cómo usar

Abre `index.html` en un navegador. Los estudiantes hacen clic en una tarjeta de documento (columna izquierda) y luego en la función que le corresponde (columna derecha).

- **10 pares** basados en documentos reales de LatamBox
- Se shufflean en cada reinicio
- Lleva registro de intentos y pares completados
- La **clase documental** (Comercial/Administrativo/Legal/Técnico) se muestra solo en la columna de Documentos. En la columna de Funciones se oculta a propósito: como documento y función comparten clase, mostrarla permitiría emparejar por coincidencia de rótulo sin razonar la función.
- Al emparejar, la tarjeta revela el texto de su pareja. Durante la animación de error los clics se bloquean (no se registran intentos fantasma).

## Recursos

| Recurso | Archivo | Descripción |
|---------|---------|-------------|
| **Tarjetas de emparejamiento** | `index.html` | Juego documento↔función (10 pares) |
| **Anatomía del documento** | `anatomia-documento.html` | Visualización interactiva de los 9 componentes con 4 tipos de documentos |

**Despliegue:** https://dfdomin.github.io/adm18-matching-cards/

---

*Material desarrollado para ADM18 — IUB/Unibarranquilla — 2026*