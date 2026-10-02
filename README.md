# 🎓 CampusMarket Website

Sitio web oficial de CampusMarket con Política de Privacidad y Términos de Servicio.

## 📁 Estructura

```
/
├── index.html              # Página principal
├── privacidad/index.html   # Política de Privacidad
└── terminos/index.html     # Términos de Servicio
```

## 🚀 Despliegue en Cloudflare Pages

### Opción 1: Desplegar desde GitHub (Recomendado)

1. **Sube este repositorio a GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: CampusMarket website"
   git branch -M main
   git remote add origin https://github.com/TuUsuario/campusmarket-website.git
   git push -u origin main
   ```

2. **Conecta en Cloudflare Pages:**
   - Ve a https://dash.cloudflare.com
   - Cloudflare Pages → Crear proyecto
   - Conecta tu cuenta de GitHub
   - Selecciona repo: `campusmarket-website`
   - Framework: Ninguno
   - Build command: (dejar vacío)
   - Build output directory: `.` (punto)
   - Deploy

3. **Configura el dominio personalizado:**
   - En Cloudflare Pages → Configuración
   - Custom domain: `campusmarket.asyncz.tech`
   - Sigue las instrucciones para DNS

### Opción 2: Desplegar manualmente

```bash
# Instalar Wrangler (CLI de Cloudflare)
npm install -g @cloudflare/wrangler

# Autenticarse
wrangler login

# Desplegar
wrangler pages deploy .
```

## 🌍 URLs Finales

- **Inicio:** https://campusmarket.asyncz.tech
- **Privacidad:** https://campusmarket.asyncz.tech/privacidad
- **Términos:** https://campusmarket.asyncz.tech/terminos

## 📝 Notas

- La Política de Privacidad incluye:
  - Tipos de datos recopilados (ubicación, fotos, pagos, perfil)
  - Cómo se usan
  - Derechos del usuario (LFPDPPP)
  - Cumplimiento con leyes mexicanas

- Los Términos de Servicio incluyen:
  - Condiciones de uso
  - Productos prohibidos
  - Protección de comprador/vendedor
  - Resolución de disputas

## ✏️ Editar

Para actualizar contenido, edita los archivos HTML localmente y vuelve a desplegar.

---

**Contacto:** brandonrbarrera@gmail.com
