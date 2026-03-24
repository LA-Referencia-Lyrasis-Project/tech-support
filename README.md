# Plataforma de Soporte Técnico para el Proyecto LAReferencia-Lyrasis

Este repositorio se utiliza como **plataforma centralizada de registro y seguimiento de incidencias**
relacionadas con los procesos de migración seguidos por repositorios **DSpace** desde versiones clásicas (5 o 6) hacia versiones
más recientes (8 y 9).

No es un repositorio de código.  
Es una **mesa de soporte técnico**.

---

## 🎯 Objetivo

- Registrar incidencias técnicas durante procesos de migración DSpace
- Estandarizar la información reportada
- Facilitar el seguimiento por parte del equipo de soporte
- Generar reportes y lecciones aprendidas a partir de los issues

---

## 📝 Cómo reportar una incidencia

1. Ir a **Issues → New issue**
2. Seleccionar el formulario correspondiente
3. Completar **todos los campos requeridos**
4. Enviar el issue

⚠️ Issues creados sin el formulario o con información incompleta podrán ser devueltos a *Triage*.

---

## 🔄 Flujo de trabajo de un issue

Todo issue sigue el siguiente flujo:

### 1️⃣ Triage
- Estado inicial de toda incidencia
- El equipo de soporte:
  - revisa la información
  - asigna etiquetas (tipo, versión, estado)
  - asigna responsable

---

### 2️⃣ En progreso
- Un soportista está trabajando activamente en la incidencia
- Puede incluir:
  - análisis
  - pruebas
  - propuestas de solución

---

### 3️⃣ Esperando respuesta
- El soporte **ya propuso una solución** o solicitó información adicional
- Se requiere acción del **gestor del repositorio / responsable técnico**
- No hay trabajo activo del soporte en este punto

Ejemplos:
- aplicar un cambio de configuración
- compartir bitácora o mensaje de error 
- confirmar si la solución funcionó

---

### 4️⃣ Resuelto
- El equipo de soporte:
  - verifica que la incidencia quedó solucionada
  - o documenta la solución aplicada
- El issue es **cerrado oficialmente**

---

## 🔐 Reglas importantes

### ✅ Quién cierra los issues
- **Solo el equipo de soporte** cierra los issues
- El gestor del repositorio puede:
  - confirmar que la solución funcionó
  - aportar información adicional
- El cierre final lo realiza el soporte

---

### ⏳ Issues sin respuesta
- Si un issue permanece en estado **Esperando respuesta** durante un periodo prolongado
  sin retroalimentación, el soporte podrá cerrarlo como resuelto.
- El issue puede reabrirse si el problema persiste.

---

## 🏷️ Uso de etiquetas (labels)

Las etiquetas se utilizan para:
- clasificar incidencias
- generar reportes
- identificar patrones recurrentes

Tipos comunes de etiquetas:
- Tipo de problema (backend, frontend, solr...)
- Versión de DSpace involucrada
- Estado del issue

---

## 📌 Buenas prácticas

- Un issue = una incidencia
- Incluir siempre logs relevantes
- No cerrar issues por cuenta propia
- Usar los comentarios para documentar soluciones

---

## 📚 Nota final

Este repositorio también funciona como **base de conocimiento**.
Las soluciones documentadas aquí ayudarán a futuros procesos de migración.

Gracias por colaborar y mantener el orden 🙌
