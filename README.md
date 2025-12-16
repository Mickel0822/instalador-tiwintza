# 📘 Control de Activos - Tiwintza

![Version](https://img.shields.io/badge/Versi%C3%B3n-1.0.22.0-blue?style=flat-square)
![Platform](https://img.shields.io/badge/Plataforma-Windows%2010%20%2F%2011%20(64%20bits)-0078D6?style=flat-square&logo=windows)

> [!IMPORTANT]
> **Antes de empezar:**
> Este sistema es una aplicación interna exclusiva para el Batallón Tiwintza. Windows requiere un paso adicional de seguridad (instalación de certificado) que **solo debe realizarse la primera vez**.

---

## 📥 Paso 1: Descargar los archivos

1. Abra su navegador web.
2. Ingrese al sitio oficial de descarga:
   
   👉 **[https://mickel0822.github.io/instalador-tiwintza/](https://mickel0822.github.io/instalador-tiwintza/)**

3. **NO** haga clic en "Obtener la aplicación" todavía.
4. Busque la sección de archivos adicionales y descargue el **Certificado de Seguridad** (`.cer`).

---

## 🛡️ Paso 2: Instalar el Certificado de Seguridad (Solo la primera vez)

> [!WARNING]
> Este paso es crítico. Si no se realiza correctamente, la instalación fallará.

1. Haga doble clic en el archivo `.cer` descargado.
2. Haga clic en **"Instalar certificado..."**.
3. Seleccione **Equipo local** (Local Machine) y haga clic en **Siguiente**.
4. **(CRÍTICO)** En la selección de almacén:
   - Seleccione: **"Colocar todos los certificados en el siguiente almacén"**.
   - Haga clic en **Examinar...**.
   - Elija: **"Entidades de certificación raíz de confianza"**.
   - Aceptar → Siguiente.
5. Haga clic en **Finalizar**. Debe ver el mensaje: *"La importación se completó correctamente"*.

---

## 🚀 Paso 3: Instalar la Aplicación

1. Vuelva a la [página de descarga](https://mickel0822.github.io/instalador-tiwintza/).
2. Haga clic en el botón **"Obtener la aplicación"**.
3. Abra el archivo descargado.
4. Cuando Windows pregunte, verifique que **"Iniciar cuando esté listo"** esté marcado.
5. Haga clic en **Instalar**.

---

## 🔄 Actualizaciones Automáticas

¡Listo! 🎉

Cada vez que abra la aplicación, el sistema buscará automáticamente nuevas versiones y las instalará sin intervención del usuario.

---

## ❓ Solución de Problemas Frecuentes

### Pantalla azul "Windows protegió su PC"
> Esto es normal en la primera instalación.
1. Haga clic en **"Más información"**.
2. Haga clic en el botón **"Ejecutar de todas formas"**.

### Error "Instalación del paquete" o "Certificado no confiable"
> [!CAUTION]
> **Causa:** Se saltó el Paso 2.
> **Solución:** Debe instalar el certificado en la carpeta **"Entidades de certificación raíz de confianza"**. Repita el Paso 2 cuidadosamente.
