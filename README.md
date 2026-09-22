# ADM18 — Tarjetas de Emparejamiento: Documentos ↔ Funciones

Juego de emparejamiento para la Semana 3 de ADM18 (Procesamiento de la Información — IUB/Unibarranquilla).

Caso integrador: **LatamBox S.A.**

## Objetivo

Que el estudiante asocie cada tipo de documento con su función principal, distinguiendo entre las 4 clases documentales de la GTC 185:2009:

- **Comercial** — registra transacciones económicas
- **Administrativo** — regula comunicación interna
- **Legal** — tiene efecto jurídico
- **Técnico** — describe especificaciones operativas

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