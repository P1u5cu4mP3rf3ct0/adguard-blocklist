# 🛡️ AdGuard Blocklist — Social Media & Streaming

Filtros para AdGuard que bloquean anuncios, rastreadores y contenido promocional en las principales plataformas sociales y de streaming.

![Version](https://img.shields.io/badge/Version-2.0-blue?style=flat-square)
![Filters](https://img.shields.io/badge/Filtros-700%2B-orange?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)
![Plataformas](https://img.shields.io/badge/Plataformas-10-purple?style=flat-square)

---

## ✨ ¿Qué bloquea?

| Plataforma | Anuncios | Rastreadores | Contenido Promocional |
|---|:---:|:---:|:---:|
| YouTube | ✅ | ✅ | ✅ |
| Spotify | ✅ | ✅ | ✅ |
| TikTok | ✅ | ✅ | ✅ |
| Instagram | ✅ | ✅ | ✅ |
| Twitter / X | ✅ | ✅ | ✅ |
| Facebook / Meta | ✅ | ✅ | ✅ |
| Twitch | ✅ | ✅ | ✅ |
| Reddit | ✅ | ✅ | ✅ |
| LinkedIn | ✅ | ✅ | ✅ |
| Pinterest | ✅ | ✅ | ✅ |
| Snapchat | ✅ | ✅ | ✅ |

Además de rastreadores cross-site generales: Google Analytics, Meta Pixel, Hotjar, Mixpanel, Amplitude, Segment, Criteo, Taboola, Outbrain y más de 50 redes publicitarias.

---

## 📥 Instalación

### Método 1 — Suscripción directa (recomendado)

Añade esta URL en **AdGuard → Filtros → Filtros personalizados → Agregar filtro personalizado**:

```
https://raw.githubusercontent.com/P1u5cu4mP3rf3ct0/adguard-blocklist/main/social-media-filters.txt
```

### Método 2 — Manual

1. Descarga el archivo `social-media-filters.txt`
2. Abre AdGuard → Filtros → Filtros personalizados
3. Haz clic en **Agregar filtro personalizado**
4. Selecciona **Importar desde archivo** y elige el archivo descargado
5. Activa el filtro

### Método 3 — Enlace de suscripción rápida

```
adguard:add?url=https://raw.githubusercontent.com/P1u5cu4mP3rf3ct0/adguard-blocklist/main/social-media-filters.txt
```

> ✅ Se recomienda activar las actualizaciones automáticas cada 24h en la configuración del filtro.

---

## 🔗 Listas externas recomendadas

Este archivo bloquea elementos específicos de cada plataforma, pero para **máxima cobertura** se recomienda combinarlo con estas listas externas.

### Nivel base — para todos los usuarios

| Lista | URL | Descripción |
|---|---|---|
| Hagezi Multi Normal | [Enlace](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/multi.txt) | ~300k dominios, sin falsos positivos |
| OISD Basic | [Enlace](https://abp.oisd.nl/basic/) | Muy estable y mantenida activamente |
| EasyList | [Enlace](https://easylist.to/easylist/easylist.txt) | Estándar de anuncios web |
| EasyPrivacy | [Enlace](https://easylist.to/easylist/easyprivacy.txt) | Estándar de rastreadores web |
| Hagezi Native TikTok Extended | [Enlace](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/native.tiktok.extended.txt) | 453 reglas específicas para rastreadores ByteDance |

### Nivel avanzado

| Lista | URL | Descripción |
|---|---|---|
| Hagezi Multi Pro | [Enlace](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.txt) | ~460k dominios, algún falso positivo ocasional |
| OISD Big | [Enlace](https://abp.oisd.nl/big/) | Versión completa de OISD |
| AdGuard Tracking Protection | [Enlace](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_3_Spyware/filter.txt) | Filtro oficial de rastreo de AdGuard |

### Malware y phishing

| Lista | URL | Descripción |
|---|---|---|
| Hagezi Threat Intelligence | [Enlace](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/tif.txt) | Dominios maliciosos activos |
| URLHaus | [Enlace](https://malware-filter.gitlab.io/malware-filter/urlhaus-filter-agh.txt) | URLs de malware activas |
| AdGuard DNS Filter | [Enlace](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt) | Filtro DNS oficial de AdGuard |

### Cookies y elementos molestos

| Lista | URL | Descripción |
|---|---|---|
| AdGuard Annoyances | [Enlace](https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_14_Annoyances/filter.txt) | Popups, banners de cookies, notificaciones |
| I Don't Care About Cookies | [Enlace](https://www.i-dont-care-about-cookies.eu/abp/) | Elimina avisos de cookies |
| Fanboy Annoyance | [Enlace](https://easylist.to/easylist/fanboy-annoyance.txt) | Elementos molestos generales |

### Para usuarios muy avanzados ⚠️ *(puede romper cosas)*

| Lista | URL | Descripción |
|---|---|---|
| Hagezi Multi Pro++ | [Enlace](https://raw.githubusercontent.com/hagezi/dns-blocklists/main/adblock/pro.plus.txt) | Muy agresivo, ~640k dominios |
| ph00lt0 Blocklist | [Enlace](https://raw.githubusercontent.com/ph00lt0/blocklist/master/blocklist.txt) | Prioriza privacidad total sobre funcionalidad |

---

## 📊 Qué se bloquea en cada plataforma

### 🎬 YouTube
Pre-roll, mid-roll y post-roll, anuncios en Shorts, overlays durante el video, botones de skip, contenido promocionado en el feed, rastreadores de analytics y métricas de reproducción, popups de Premium.

### 🎵 Spotify
Anuncios de audio entre canciones, anuncios en podcasts, banners y overlays visuales, rastreadores de comportamiento de escucha, segmentación demográfica, test A/B, botones de upsell a Premium.

### 📱 TikTok
Anuncios en el feed, anuncios en TikTok Live, publicidad en la red Pangle (ByteDance), 30+ dominios de rastreo nativos de ByteDance, dominios CDN de publicidad.

### 📸 Instagram
Contenido patrocinado en feed, ads en Stories y Reels, anuncios de Shopping, rastreadores de conversión y comportamiento, servicios de terceros de Meta.

### 🐦 Twitter / X
Tweets promocionados, trends pagados, pre-roll en vídeos, anuncios en búsqueda, rastreadores de conversión y audiencia.

### 👥 Facebook / Meta
Anuncios en el feed, Meta Pixel, seguimiento cross-site, publicidad del Audience Network.

### 🎮 Twitch
Anuncios pre-roll en streams, banners de display, rastreadores Spade y Countess.

### 💬 Reddit
Posts promocionados en el feed, rastreadores de eventos y píxeles.

### 💼 LinkedIn
Contenido patrocinado, anuncios InMail, tracking de LinkedIn Insight Tag, Bing Ads integrado.

### 📌 Pinterest
Pines promocionados, banners de publicidad, píxel de conversión de Pinterest.

### 👻 Snapchat
Snaps patrocinados, píxel de Snapchat, rastreadores de conversión.

---

## 🔧 Solución de problemas

**Los anuncios siguen apareciendo**
- Verifica que el filtro está activado y actualizado
- Limpia la caché del navegador
- Asegúrate de que las listas externas recomendadas también están activas

**Algo no funciona correctamente**
- Desactiva temporalmente el filtro para confirmar que es la causa
- [Abre un issue](https://github.com/P1u5cu4mP3rf3ct0/adguard-blocklist/issues) indicando qué plataforma falla y en qué consiste el problema

**Añadir excepciones personalizadas**
```
@@||dominio-que-quieres-permitir.com^
```

---

## 📖 Sintaxis de filtros (referencia rápida)

```
! Comentario
||dominio.com^                     Bloquea dominio completo
||dominio.com/ruta/*               Bloquea ruta específica
dominio.com##.clase-css            Oculta elemento por clase CSS
dominio.com##[data-testid="id"]    Oculta elemento por atributo
@@||dominio.com^                   Excepción — permite dominio
$xmlhttprequest                    Solo peticiones AJAX
$media                             Solo recursos de medios
$domain=sitio.com                  Solo en ese dominio
```

Documentación completa: [AdGuard Filtering Rules Syntax](https://adguard.com/kb/general/ad-filtering/create-own-filters/)

---

## 📄 Licencia

[MIT](https://github.com/P1u5cu4mP3rf3ct0/zabbix-templates/blob/main/LICENSE) — Libre para usar, modificar y distribuir. Se agradece dar crédito al autor.

---

## 👤 Autor

Creado y mantenido por [P1u5cu4mP3rf3ct0](https://github.com/P1u5cu4mP3rf3ct0).

Si te ha sido útil, considera dejar una ⭐ en el repositorio.
