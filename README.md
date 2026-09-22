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

**Pensada para el celular** (también funciona en computador). Abre `index.html` en el navegador.

1. **Instrucciones + 4 ejemplos guiados** al inicio: cómo se juega (4 pasos), la pregunta que clasifica y un ejemplo por clase con retroalimentación y razón. El estudiante puede empezar cuando quiera (botón «Saltar a la actividad»).
2. **Actividad**: 10 pares con documentos reales de LatamBox, barajados en cada reinicio, con contador de pares e intentos y barra de progreso.

La **clase documental** (Comercial/Administrativo/Legal/Técnico) se muestra **solo en la columna de Documentos**. En Funciones se oculta a propósito: como documento y función comparten clase, mostrarla permitiría emparejar por coincidencia de rótulo sin razonar la función.

### Interacción

| | Celular (< 860 px) | Escritorio (≥ 860 px) |
|---|---|---|
| Columnas | **Una a la vez**, con pestañas `📄 Documentos` / `🎯 Funciones` | Dos columnas lado a lado |
| Flujo | Toca un documento → **salta sola** a Funciones → toca la función | Elige libremente en ambas columnas |
| Guía | **Bandeja fija al pie**: dice qué está seleccionado y avisa del error | Bandeja bajo el tablero |

- Al tocar un documento, la app cambia de pestaña automáticamente; al acertar (o fallar) vuelve a Documentos.
- En error, la bandeja muestra **««doc» no va con «función»»** (en móvil el par comparado puede quedar fuera de pantalla) y los clics se bloquean 0,8 s para evitar intentos fantasma.
- Al emparejar, la tarjeta revela el texto de su pareja.
- Áreas táctiles ≥ 44 px, sin desplazamiento horizontal, `touch-action: manipulation` (sin retardo de doble toque).

## Recursos

| Recurso | Archivo | Descripción |
|---------|---------|-------------|
| **Tarjetas de emparejamiento** | `index.html` | Juego documento↔función (10 pares) |
| **Anatomía del documento** | `anatomia-documento.html` | Visualización interactiva de los 9 componentes con 4 tipos de documentos |

**Despliegue:** https://dfdomin.github.io/adm18-matching-cards/

---

*Material desarrollado para ADM18 — IUB/Unibarranquilla — 2026*