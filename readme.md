# 🌿 AUDITORÍA TÉCNICA Y AMBIENTAL PRO – PAGA

### Acta Digital de Evaluación Ambiental – Vía Granada – Guatapé

![Image](https://imagenes2.eltiempo.com/files/image_1200_535/uploads/2025/07/16/6877fcc5aa08d.jpeg)

![Image](https://www.huila.gov.co/info/huila_bco/media/pubInt/thumbs/thpubInt_700X400_14189.webp)

![Image](https://storage.googleapis.com/download/storage/v1/b/tecplast-241907-gke/o/baches-direct%2Fmedia%2Fcache%2F385x241%2F6d%2F19%2Fae713c84b67ca10f04ae34dd31d4.jpg?alt=media\&generation=1741079537021593)

![Image](https://img.waimaoniu.net/2407/2407-202106011736222022.jpg)

Aplicación web desarrollada en **HTML, CSS y JavaScript puro** para la generación digital de:

> **Actas de Auditoría Técnica y Control Ambiental**
> Evaluación del **Plan de Adaptación a la Guía Ambiental (PAGA)**

Diseñada para el proyecto:

**Vía Rural Granada – Guatapé (Sector La Sonadora y La Peña)**

Optimizada para uso en **campo (celular/tablet)** y generación inmediata de **PDF imprimible institucional**.

---

# 🚀 Características Principales

* 🌿 Evaluación ambiental estructurada por fichas PAGA
* 🚦 Sistema semáforo (Cumple / No cumple / N/A)
* 📸 Evidencia fotográfica múltiple por ítem con compresión y galería
* ✍️ **Novedad:** Motor Digital de Firmas en Lienzo (Canvas) para pantalla táctil o mouse
* 💾 **Novedad:** Guardado y Carga de Reportes Locales en formato `.json`
* 🔔 **Novedad:** Sistema de Notificaciones Toast integradas (UI limpia, sin alertas nativas)
* 📲 **Novedad:** PWA Completa (Service Worker y Manifest para instalación nativa y Offline real)
* 📝 Observaciones técnicas detalladas
* 🏷 Carga dinámica de logos institucionales
* 🖨 Generación de PDF lista para radicación
* 📱 Diseño 100% responsive optimizado para móvil y escritorio
* 🔒 100% Local: Sin base de datos ni backend

---

# 📂 Estructura del Proyecto

```
📁 auditoria-ambiental-pro/
 ├── 📄 index.html      (Aplicación principal, estilos y lógica JS integrados)
 ├── 📄 manifest.json   (Declaración de variables PWA p/ Instalación)
 └── 📄 sw.js           (Service Worker para caché y soporte Offline)
```

El archivo incluye:

* Maquetación HTML completa
* Estilos CSS (pantalla + impresión)
* Lógica JavaScript integrada
* Optimización para dispositivos móviles
* Configuración avanzada de impresión

No requiere:

* Frameworks
* Librerías externas
* Backend
* Base de datos

---

# 📋 Módulos de Auditoría Ambiental Incluidos

## 1️⃣ Gestión Social y Documental (DAGA / PGS)

* Actas de Vecindad
* Atención Comunitaria (PQRS)
* Cumplimiento de tiempos legales
* Registro fotográfico obligatorio

---

## 2️⃣ Manejo de Materiales y Escombros (PAC)

* Acopios temporales
* Confinamiento y cobertura
* Preparación de concretos
* Prohibición de mezcla sobre suelo natural
* Transporte y disposición de RCD
* Certificación ZODME

---

## 3️⃣ Protección Hídrica y Residuos (PGH)

* Manejo de aguas residuales
* Unidades sanitarias portátiles
* Manejo de residuos peligrosos (RESPEL)
* Condiciones de almacenamiento
* Frecuencia de retiro

---

## 4️⃣ Señalización y Contingencias (PMIT / PSST)

* Cerramientos y manejo de tránsito
* Señalización preventiva
* Mantenimiento de maquinaria
* Plan de contingencia
* Kit de derrames
* Protección de flora

---

# ⚙️ Funcionalidades Técnicas

## 📅 Fecha automática

Se carga automáticamente al abrir el documento.

## 🖼 Carga dinámica de logos

Permite adjuntar:

* Logo Alcaldía
* Logo Interventoría

Se almacenan en memoria durante la sesión.

## 📸 Galería por ítem

Cada requerimiento incluye:

* Subida múltiple de imágenes
* Eliminación individual con clic
* Visualización tipo galería adaptable
* Optimización para impresión

## 🚦 Sistema semáforo inteligente

Estados disponibles:

* 🟢 CUMPLE
* 🔴 NO CUMPLE
* ⚪ N/A

Cambio automático de color visual.

## 🧹 Botón de limpieza total

Incluye función:

```
🗑 Limpiar
```

* Borra campos
* Elimina imágenes
* Restablece estados
* Limpia firmas
* Restaura logos

Optimizado para iOS (sin bloqueo del navegador).

## 🖨 Modo impresión profesional

Incluye:

* Ajuste automático de tipografía
* Conservación de colores
* Control de saltos de página
* Eliminación de botones en PDF
* Tablas optimizadas para impresión formal

---

# 📱 Diseño Responsive

En dispositivos móviles:

* Tablas convertidas en formato tarjeta
* Etiquetas automáticas con `data-label`
* Galería en 2 columnas
* Firmas apiladas verticalmente
* Botones flotantes de acción rápida (FAB)

---

# 🖥️ Uso

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/tuusuario/auditoria-ambiental-pro.git
```

## 2️⃣ Abrir archivo

Abrir directamente:

```
index.html
```

Navegador recomendado: **Google Chrome**

---

## 3️⃣ Diligenciar

* Contratista
* Fecha
* Tramo
* Auditor
* Evaluación por ficha
* Adjuntar evidencias

---

## 4️⃣ Generar PDF

Presionar:

```
🖨 Generar PDF
```

O:

```
Imprimir → Guardar como PDF
```

---

# 🔒 Consideraciones Importantes

* No guarda información al cerrar el navegador.
* Las imágenes se mantienen solo en memoria.
* Se recomienda generar el PDF inmediatamente después de diligenciar.
* No reemplaza sistema oficial de gestión documental.

---

# 🛠 Posibles Mejoras Futuras

* Guardado automático en `localStorage`
* Generación de consecutivo automático
* Firma digital táctil
* Exportación automática directa a PDF
* Versión con backend y almacenamiento en nube
* Dashboard de seguimiento ambiental
* Reporte consolidado de hallazgos

---

# 👷 Perfil de Usuario

* Ingeniero Ambiental
* Interventor
* Supervisor Municipal
* Residente Ambiental
* Entidades Públicas
* Consultores PAGA

---

# 📌 Estado del Proyecto

🟢 Versión estable
🌿 Especializada en auditoría ambiental PAGA
📱 Optimizada para campo
🖨 Lista para radicación en PDF

---

# 📄 Licencia

Uso técnico e institucional.
Libre para modificación según requerimientos contractuales y normativos.

---

Si deseas, puedo prepararte también:

* 📘 Manual de Usuario Ambiental (PDF formal)
* ☁ Versión con almacenamiento en la nube
* 🧾 Versión con consecutivo automático
* 🖊 Versión con firma digital avanzada
* 🏛 Versión institucional con identidad gráfica oficial

Solo dime cuál quieres desarrollar.
