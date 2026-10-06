# Tarea: Flujo de Colaboración en GitHub

Este repositorio contiene la entrega de la tarea práctica sobre la aplicación de un flujo simple de colaboración en GitHub (Gestión de Issues, Trabajo en Ramas, Pull Requests, Revisión y Merge).

---

## 👤 Información del Estudiante

- **Autor:** Claudio Ramirez
- **Código de Estudiante:** 202110020069
- **Asignatura:** Implementación y Validación de Software
- **Institución:** Universidad Central de Nicaragua (UCN)

---

## 🚀 Guía Rápida de Uso

Esta guía describe el flujo de trabajo estándar utilizado en este repositorio para la colaboración en equipo:

### 1. Clonar el repositorio
```bash
git clone https://github.com/Clos1604/tarea-procedimiento-github-claudio-ramirez.git
cd tarea-procedimiento-github-claudio-ramirez
```

### 2. Crear una rama de característica (Feature Branch)
Para cada mejora o corrección reportada en un Issue, se debe crear una rama dedicada con un nombre descriptivo:
```bash
git checkout -b feature/nombre-de-la-mejora
```

### 3. Registrar los cambios (Commits)
Realiza cambios en el código/documentación y registra los avances con mensajes claros y concisos:
```bash
git add .
git commit -m "docs: agregar guia rapida al README"
```

### 4. Publicar la rama y abrir un Pull Request (PR)
Subir la rama al repositorio remoto y solicitar la revisión correspondiente mediante un PR:
```bash
git push -u origin feature/nombre-de-la-mejora
```

### 5. Revisión y Merge
- Verificar la checklist del PR.
- Auto-revisar o solicitar revisión a un compañero.
- Realizar el **Merge** a la rama principal (`main`) una vez aprobado.
- Cerrar el Issue correspondiente.

---

## 📋 Estructura del Trabajo
1. **Issue:** `#1` - *Agregar guía rápida al README*
2. **Branch:** `feature/guia-readme`
3. **Pull Request:** Integración y checklist de verificación.
