# 🚫 Social Media AdBlock Filters

<div align="center">

![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![Platform](https://img.shields.io/badge/platform-AdGuard-green.svg)
![License](https://img.shields.io/badge/license-MIT-yellow.svg)
![Filters](https://img.shields.io/badge/filters-400+-red.svg)

**Una lista completa de filtros para AdGuard que bloquea anuncios, rastreadores y contenido promocional en las principales plataformas sociales y de streaming.**

</div>

---

## ✨ Características

- 🎯 **400+ filtros optimizados** para máxima efectividad
- 🎵 **YouTube & Spotify** - Bloquea anuncios de video, audio y rastreadores
- 🐦 **Twitter/X** - Elimina tweets promocionados y analytics
- 📸 **Instagram** - Oculta contenido patrocinado en feed, stories y reels
- 🔒 **Privacidad avanzada** - Bloquea rastreadores y analytics
- ⚡ **Rendimiento optimizado** - Filtros específicos sin falsos positivos

## 🎯 Plataformas Soportadas

| Plataforma | Anuncios | Analytics | Contenido Promocional | Estado |
|------------|----------|-----------|----------------------|---------|
| **YouTube** | ✅ | ✅ | ✅ | Completamente soportado |
| **Spotify** | ✅ | ✅ | ✅ | Completamente soportado |
| **Twitter/X** | ✅ | ✅ | ✅ | Completamente soportado |
| **Instagram** | ✅ | ✅ | ✅ | Completamente soportado |

## 📥 Instalación

### Método 1: Importación directa (Recomendado)
```
https://raw.githubusercontent.com/tu-usuario/social-media-adblock-filters/main/social-media-filters.txt
```

### Método 2: Instalación manual
1. Descarga el archivo `social-media-filters.txt`
2. Abre AdGuard → **Filtros** → **Filtros personalizados**
3. Haz clic en **Agregar filtro personalizado**
4. Selecciona **Importar desde archivo** y elige el archivo descargado
5. ✅ Activa el filtro

### Método 3: Suscripción automática
Haz clic en este enlace para añadir automáticamente los filtros:
```
adguard:add?url=https://raw.githubusercontent.com/tu-usuario/social-media-adblock-filters/main/social-media-filters.txt
```

## 🔧 Configuración

### Configuración Básica
- ✅ Asegúrate de que el filtro esté **activado**
- ✅ Configura las **actualizaciones automáticas** (24h recomendado)
- ✅ Verifica que AdGuard esté funcionando en las plataformas objetivo

### Configuración Avanzada
Para usuarios expertos que quieran personalizar los filtros:

```adblock
! Desactivar filtros específicos (añadir al inicio)
@@||youtube.com/api/stats/watchtime$xmlhttprequest

! Filtros personalizados adicionales
||tu-dominio-personalizado.com^
```

## 🛠️ Compatibilidad

| Cliente AdGuard | Compatibilidad | Notas |
|-----------------|---------------|-------|
| **AdGuard para Windows** | ✅ Completa | Funcionalidad completa |
| **AdGuard para Mac** | ✅ Completa | Funcionalidad completa |
| **AdGuard para Android** | ✅ Completa | Funcionalidad completa |
| **AdGuard para iOS** | ✅ Completa | Funcionalidad completa |
| **Extensión AdGuard** | ✅ Completa | Funcionalidad completa |
| **AdGuard Home** | ✅ Parcial | Solo filtros DNS |

## 📊 Estadísticas de Bloqueo

### YouTube
- 🎬 **Anuncios de video**: Pre-roll, mid-roll, post-roll
- 📱 **YouTube Shorts**: Anuncios en contenido vertical
- 📊 **Analytics**: Métricas de reproducción y engagement
- 🎯 **Contenido promocional**: Videos patrocinados

### Spotify
- 🎵 **Anuncios de audio**: Entre canciones y podcasts
- 🖼️ **Anuncios visuales**: Banners y overlays
- 📈 **Rastreadores**: Datos de escucha y comportamiento
- 💰 **Promociones Premium**: Botones y pop-ups

### Twitter/X
- 🐦 **Tweets promocionados**: Contenido patrocinado en timeline
- 📈 **Trends promocionados**: Hashtags pagados
- 🎥 **Anuncios de video**: Pre-roll en contenido multimedia
- 🔍 **Analytics**: Métricas de engagement y conversión

### Instagram
- 📷 **Posts patrocinados**: Contenido promocional en feed
- 📚 **Stories ads**: Anuncios entre historias
- 🎬 **Reels promocionados**: Contenido publicitario en reels
- 🛍️ **Shopping ads**: Anuncios de productos

## 🐛 Solución de Problemas

### Problemas Comunes

**❓ Los anuncios siguen apareciendo**
- Verifica que el filtro esté activado
- Fuerza la actualización del filtro
- Limpia la caché del navegador

**❓ Problemas de reproducción**
- Desactiva temporalmente el filtro
- Reporta el problema con detalles específicos
- Usa las reglas de whitelist incluidas

**❓ Contenido legítimo bloqueado**
- Revisa los logs de AdGuard
- Añade excepciones personalizadas
- Reporta falsos positivos

### Logs y Debugging
Para obtener información de debug:
1. Abre AdGuard → **Configuración** → **General**
2. Activa **Modo de debugging**
3. Reproduce el problema
4. Exporta los logs desde **Configuración** → **Soporte**

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Puedes ayudar de varias formas:

### 🐛 Reportar Bugs
- Usa el template de issues
- Incluye capturas de pantalla
- Proporciona información del sistema

### ✨ Sugerir Mejoras
- Nuevas plataformas a soportar
- Filtros adicionales
- Optimizaciones de rendimiento

### 🔧 Desarrollo
```bash
# Fork el repositorio
git clone https://github.com/tu-usuario/social-media-adblock-filters.git

# Crea una rama para tu feature
git checkout -b feature/nueva-funcionalidad

# Realiza tus cambios
# Testa los filtros

# Commit y push
git commit -m "Añadir filtros para TikTok"
git push origin feature/nueva-funcionalidad

# Crea un Pull Request
```

## 📖 Documentación

### Sintaxis de Filtros
Los filtros utilizan la sintaxis estándar de AdGuard:

```adblock
! Comentario
||dominio.com^                    # Bloquea dominio completo
||dominio.com/path/*             # Bloquea path específico
dominio.com##.clase              # Oculta elemento CSS
@@||dominio.com^                 # Excepción (whitelist)
```

### Estructura del Archivo
```
social-media-filters.txt
├── Header (información del filtro)
├── YouTube (anuncios, analytics, elementos UI)
├── Spotify (audio ads, rastreadores, promociones)
├── Twitter/X (tweets promocionados, analytics)
├── Instagram (contenido patrocinado, stories ads)
└── Dominios generales (redes publicitarias)
```

## 📝 Changelog

### v1.0 (2025-06-06)
- ✨ Lanzamiento inicial
- 🎯 400+ filtros para 4 plataformas principales
- 📱 Soporte completo para móviles y desktop
- 🔒 Filtros avanzados de privacidad

## 📄 Licencia

Este proyecto está licenciado bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

## 🙏 Agradecimientos

- [AdGuard](https://adguard.com/) por la excelente herramienta de bloqueo
- [EasyList](https://easylist.to/) por la inspiración en sintaxis de filtros
- Contribuidores de la comunidad por reportar bugs y sugerencias

---

<div align="center">

**⭐ Si te gusta este proyecto, ¡dale una estrella en GitHub! ⭐**

</div>
