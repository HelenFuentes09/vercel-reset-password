# Renta Premium - Password Reset Page

Esta es la página web para restablecer contraseñas de la aplicación Renta Premium.

## 🚀 Despliegue en Vercel

### Pasos para desplegar:

1. **Instalar Vercel CLI:**
   ```bash
   npm install -g vercel
   ```

2. **Iniciar sesión en Vercel:**
   ```bash
   vercel login
   ```

3. **Desplegar:**
   ```bash
   cd vercel-reset-password
   vercel --prod
   ```

### 🔧 Configuración

Las credenciales de Supabase ya están configuradas en `index.html`:
- **SUPABASE_URL:** `https://ezhdbozdcxavmwjwjwrx.supabase.co`
- **SUPABASE_ANON_KEY:** Configurada correctamente

### 📱 Uso

1. El usuario solicita reset de contraseña desde la app
2. Recibe un email con enlace a esta página
3. Ingresa nueva contraseña
4. Regresa a la app para iniciar sesión

### 🔒 Seguridad

- Headers de seguridad configurados en `vercel.json`
- Validación de tokens de Supabase
- Logs detallados para debugging