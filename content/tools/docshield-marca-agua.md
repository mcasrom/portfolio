---
title: "DocShield — Marca de agua para documentos de identidad"
date: 2025-03-08
description: "Herramienta gratuita y local para añadir marca de agua a DNI, pasaporte y carnet de conducir. Protege tus documentos sensibles frente al fraude de identidad. Sin subir datos a ningún servidor."
tags: ["seguridad", "privacidad", "identidad", "documentos", "rgpd", "herramientas", "javascript"]
categories: ["tools"]
cover:
  alt: "DocShield — Protección de documentos de identidad con marca de agua"
showToc: true
---

## El problema real

Cada año miles de personas son víctimas de **fraude de identidad** en España y Europa. El vector más común es sorprendentemente simple: una fotocopia o imagen de un DNI, pasaporte o carnet de conducir enviada por email, WhatsApp o formulario web — muchas veces de forma completamente legítima — acaba siendo reutilizada para fines fraudulentos.

Alquileres de pisos, contratos de telefonía, préstamos rápidos, suplantación en plataformas digitales. El documento original no cambia de manos, pero su imagen sí.

---

## La solución: marca de agua contextual

Una **marca de agua visible** con el propósito específico de la cesión hace que la copia sea inútil para cualquier otro uso. Si el documento dice claramente `SOLO PARA ALQUILER PISO CALLE MAYOR 12 · MARZO 2025`, no sirve para abrir una línea de móvil ni para nada más.

**[→ Abrir DocShield](/portfolio/tools/docshield/)** — funciona 100% en tu navegador, sin subir nada a ningún servidor.

---

## Cómo funciona

1. **Sube la imagen** de tu documento (DNI, pasaporte, licencia)
2. **Escribe el texto** de la marca de agua — destinatario, fecha, propósito
3. **Ajusta** opacidad, tamaño, ángulo y posición
4. **Descarga** la imagen protegida directamente desde el navegador

Todo el procesamiento ocurre en tu dispositivo mediante JavaScript puro. La imagen **nunca sale de tu ordenador**.

---

## Aviso legal — RGPD y protección de datos

> ⚠️ **Nota importante sobre el Reglamento General de Protección de Datos (RGPD / GDPR)**

El DNI, pasaporte y carnet de conducir son **documentos de identidad oficial** que contienen **datos personales especialmente sensibles** según el RGPD (Reglamento UE 2016/679) y la LOPDGDD española (Ley Orgánica 3/2018).

Antes de facilitar una copia de cualquier documento de identidad, ten en cuenta:

- **Principio de minimización** (Art. 5 RGPD): solo debes proporcionar los datos estrictamente necesarios para el fin solicitado. Valora si realmente es necesario ceder el documento completo.
- **Finalidad específica** (Art. 5 RGPD): la copia solo puede usarse para el propósito declarado. La marca de agua ayuda a hacer esto explícito y verificable.
- **Derecho de información** (Art. 13 RGPD): quien recibe tu documento debe informarte de cómo lo tratará, cuánto tiempo lo conservará y con quién lo compartirá.
- **Conservación limitada** (Art. 5 RGPD): el receptor debe destruir la copia una vez cumplida la finalidad.

**DocShield no elimina el riesgo, lo mitiga.** La herramienta es una capa adicional de protección, no un sustituto de una cesión responsable. En caso de duda sobre la legitimidad de una solicitud de documento, contacta con la **Agencia Española de Protección de Datos (AEPD)**: [aepd.es](https://www.aepd.es).

---

## Casos de uso habituales

| Situación | Marca de agua recomendada |
|---|---|
| Alquiler de vivienda | `SOLO PARA CONTRATO ALQUILER · [dirección] · [fecha]` |
| Apertura cuenta bancaria | `SOLO PARA [nombre banco] · [fecha]` |
| Contrato de trabajo | `SOLO PARA [empresa] · CONTRATO LABORAL · [fecha]` |
| Plataforma online | `SOLO PARA VERIFICACIÓN [plataforma] · [fecha]` |
| Compraventa vehículo | `SOLO PARA COMPRAVENTA [matrícula] · [fecha]` |

---

## Tecnología

- **HTML5 Canvas API** — procesamiento de imagen en cliente
- **JavaScript puro** — sin frameworks, sin dependencias externas
- **Zero backend** — ningún dato sale del navegador
- Parte del ecosistema **Con el Odroid en la Mochila** — herramientas abiertas, auditables

**[→ Abrir DocShield ahora](/portfolio/tools/docshield/)**

---

*© 2025 Miguel Castillo · [mybloggingnotes@gmail.com](mailto:mybloggingnotes@gmail.com) · Esta herramienta se ofrece tal cual, sin garantías. El autor no se responsabiliza del uso que se haga de las imágenes generadas.*
