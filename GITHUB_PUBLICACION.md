# 🚀 CÓMO PUBLICAR EN GITHUB - GUÍA RÁPIDA

## Paso 1: Crear Cuenta en GitHub (Si no la tienes)

1. Ve a **https://github.com**
2. Clic en **"Sign up"**
3. Completa:
   - Username: Tu nombre de usuario (ej: `tu-nombre`)
   - Email: `manuelchanourdiellevilao@gmail.com`
   - Password: Tu contraseña segura
4. Verifica tu email
5. ✅ Cuenta creada

---

## Paso 2: Crear Repositorio en GitHub

1. Inicia sesión en GitHub (https://github.com)
2. En la esquina superior derecha, haz clic en **➕ (Plus)**
3. Selecciona **"New repository"**
4. Completa:
   - **Repository name:** `presentacion-anillo-digital`
   - **Description:** `Presentación División Anillo Digital 2026 - Informe Operativo`
   - **Public:** ✅ (Selecciona esta opción para compartir)
   - **Add a README file:** Opcional (ya tenemos el nuestro)
5. Clic en **"Create repository"**

---

## Paso 3: Configurar Git Localmente (YA HECHO ✅)

El repositorio local ya está configurado en:
```
C:\Users\chanu\
```

Archivos agregados:
- ✅ `presentacion_anillo_digital.html`
- ✅ `README.md`
- ✅ `INSTRUCCIONES.md`

---

## Paso 4: Conectar Repositorio Local con GitHub

### Opción A: HTTPS (Más Fácil) ⭐

En PowerShell, ejecuta estos comandos en `C:\Users\chanu`:

```powershell
git remote add origin https://github.com/TU_USUARIO/presentacion-anillo-digital.git
git branch -M main
git push -u origin main
```

**Reemplaza `TU_USUARIO` con tu nombre de usuario de GitHub**

Ejemplo:
```powershell
git remote add origin https://github.com/manuelchanourdiele/presentacion-anillo-digital.git
git branch -M main
git push -u origin main
```

### Opción B: SSH (Más Seguro)

Si tienes SSH configurado en GitHub:

```powershell
git remote add origin git@github.com:TU_USUARIO/presentacion-anillo-digital.git
git branch -M main
git push -u origin main
```

---

## Paso 5: Subir los Archivos a GitHub

En PowerShell, ejecuta:

```powershell
cd C:\Users\chanu
git push -u origin main
```

**Primera vez:** Te pedirá autenticación
- **HTTPS:** Ingresa tu username y contraseña (o token personal)
- **SSH:** Debería funcionar automáticamente

---

## Paso 6: Verificar que Subió Correctamente

1. Ve a **https://github.com/TU_USUARIO/presentacion-anillo-digital**
2. Deberías ver:
   - ✅ `presentacion_anillo_digital.html`
   - ✅ `README.md`
   - ✅ `INSTRUCCIONES.md`

---

## Paso 7: Activar GitHub Pages (Para Publicar Online)

1. En tu repositorio de GitHub, ve a **Settings** (⚙️)
2. En el menú izquierdo, busca **"Pages"**
3. En la sección **"Build and deployment"**:
   - Source: Selecciona **"Deploy from a branch"**
   - Branch: Selecciona **"main"** 
   - Folder: Selecciona **"/ (root)"**
4. Clic en **"Save"**
5. Espera 1-2 minutos
6. Verás un mensaje: **"Your site is live at: https://tu-usuario.github.io/presentacion-anillo-digital/"**

---

## Paso 8: Acceder a la Presentación Online

Una vez activado GitHub Pages, puedes acceder en:

```
https://TU_USUARIO.github.io/presentacion-anillo-digital/presentacion_anillo_digital.html
```

Ejemplo:
```
https://manuelchanourdiele.github.io/presentacion-anillo-digital/presentacion_anillo_digital.html
```

---

## ⚙️ CONFIGURAR TOKEN PERSONAL EN GITHUB (Alternativa Segura)

Si Git pide contraseña pero tienes 2FA habilitado:

1. Ve a **https://github.com/settings/tokens**
2. Clic en **"Generate new token"**
3. Dale un nombre: "Presentación Anillo Digital"
4. Selecciona scopes: `repo`, `workflow`
5. Clic en **"Generate token"**
6. **Copia el token** (no lo compartas)
7. En PowerShell, cuando pida contraseña, pega el token

---

## 📋 CHECKLIST DE PUBLICACIÓN

- [ ] Creé cuenta en GitHub
- [ ] Creé el repositorio `presentacion-anillo-digital`
- [ ] Ejecuté `git remote add origin...`
- [ ] Ejecuté `git push -u origin main`
- [ ] Verifiqué que los archivos están en GitHub
- [ ] Activé GitHub Pages
- [ ] Accedí a la presentación online
- [ ] Compartí el link con el equipo

---

## 🔗 LINKS RÁPIDOS

| Acción | Link |
|--------|------|
| Tu Repositorio | https://github.com/TU_USUARIO/presentacion-anillo-digital |
| Presentación Online | https://TU_USUARIO.github.io/presentacion-anillo-digital/presentacion_anillo_digital.html |
| Configurar GitHub Pages | https://github.com/TU_USUARIO/presentacion-anillo-digital/settings/pages |
| Mi Perfil de GitHub | https://github.com/TU_USUARIO |

---

## 🆘 PROBLEMAS COMUNES

### Error: "fatal: not a git repository"
**Solución:** Asegúrate de estar en `C:\Users\chanu`
```powershell
cd C:\Users\chanu
```

### Error: "could not read Username"
**Solución:** Usa un token personal en lugar de contraseña
- Crea uno en: https://github.com/settings/tokens
- Usa el token cuando pida contraseña

### Los archivos subieron pero la presentación no aparece
**Solución:** Espera 2-3 minutos y recarga la página

### No me aparece el botón de Settings
**Solución:** Asegúrate de que el repositorio sea **PUBLIC**

---

## ✅ ¡LISTO!

Tu presentación está publicada en GitHub y accesible online. 

Puedes:
- 📤 Compartir el link con tu equipo
- 📝 Hacer cambios y actualizar automáticamente
- 🔗 Incrustar la presentación en un sitio web
- 📊 Ver estadísticas de visitas

---

**Versión:** 1.0
**Fecha:** Septiembre 2026
**Autor:** División Anillo Digital

