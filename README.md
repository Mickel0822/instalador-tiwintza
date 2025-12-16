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
<img width="886" height="660" alt="image" src="https://github.com/user-attachments/assets/c272206c-0a19-47d7-981e-a8050b958e52" />
<img width="619" height="225" alt="image" src="https://github.com/user-attachments/assets/ca860693-6df1-4df9-9f65-c241303e2e06" />

---

## 🛡️ Paso 2: Instalar el Certificado de Seguridad (Solo la primera vez)

> [!WARNING]
> Este paso es crítico. Si no se realiza correctamente, la instalación fallará.

1. Haga doble clic en el archivo `.cer` descargado.
<img width="514" height="233" alt="image" src="https://github.com/user-attachments/assets/44e3f25c-ea1f-4b18-a55f-627f89b3acad" />
2. Haga clic en **"Instalar certificado..."**.
<img width="659" height="554" alt="image" src="https://github.com/user-attachments/assets/6d981da4-0815-4139-8295-2f53d8d76d58" />
<img width="614" height="785" alt="image" src="https://github.com/user-attachments/assets/44a5dafc-08f2-4f64-9cf1-6594b53a7022" />
3. Seleccione **Equipo local** (Local Machine) y haga clic en **Siguiente**.
<img width="821" height="810" alt="image" src="https://github.com/user-attachments/assets/f9792f2b-9e6e-4825-ac5a-3394d89904cc" />
<img width="821" height="810" alt="image" src="https://github.com/user-attachments/assets/0d6c3503-aeae-472a-a291-510064472a72" />
4. **(CRÍTICO)** En la selección de almacén:
   - Seleccione: **"Colocar todos los certificados en el siguiente almacén"**.
   <img width="819" height="801" alt="image" src="https://github.com/user-attachments/assets/d8ecaebb-b50a-44b6-ad56-4bcbc038b777" />
   - Haga clic en **Examinar...**.
   - Elija: **"Entidades de certificación raíz de confianza"**.
   <img width="438" height="415" alt="image" src="https://github.com/user-attachments/assets/f815f72f-c0ae-41c7-bd9b-bb1102e705a5" />
   - Aceptar → Siguiente.
   <img width="833" height="803" alt="image" src="https://github.com/user-attachments/assets/47808178-3c94-4223-a87b-f53180693758" />
5. Haga clic en **Finalizar**. Debe ver el mensaje: *"La importación se completó correctamente"*.
<img width="823" height="813" alt="image" src="https://github.com/user-attachments/assets/c6299bd5-82be-4cad-8722-7adcfcbead4e" />

---

## 🚀 Paso 3: Instalar la Aplicación

1. Vuelva a la [página de descarga](https://mickel0822.github.io/instalador-tiwintza/).
2. Haga clic en el botón **"Obtener la aplicación"**.
<img width="886" height="645" alt="image" src="https://github.com/user-attachments/assets/60afa7d8-48b6-4b6c-b19d-6801d455f177" />

3. Abra el archivo descargado.
<img width="590" height="254" alt="image" src="https://github.com/user-attachments/assets/794e92cf-e893-4e8d-ab29-6fb201ca7579" />

4. Cuando Windows pregunte, verifique que **"Iniciar cuando esté listo"** esté marcado.
5. Haga clic en **Instalar**.
<img width="886" height="628" alt="image" src="https://github.com/user-attachments/assets/f2a7c5b5-5193-4807-840c-0a166365efe7" />

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
