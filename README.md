<div align="center">

# 🎨 VisorX
! [Image Alt](https://github.com/ByRafaelSystem/magisk-visorx-fixed/blob/main/IMG_20260316_093832.jpg)
### By_Rafael System

**Color & Graphics Engine — Motor de color y gráficos para Android**

[![Version](https://img.shields.io/badge/Version-v9.0-purple?style=flat-square)]()
[![Android](https://img.shields.io/badge/Android-8%2B-green?style=flat-square)]()
[![Root](https://img.shields.io/badge/Root-Magisk%20%7C%20KSU%20%7C%20APatch-blue?style=flat-square)]()
[![License](https://img.shields.io/badge/License-Apache%202.0-orange?style=flat-square)]()
[![Author](https://img.shields.io/badge/Author-By__Rafael_System-red?style=flat-square)]()

</div>

---

## 🌍 Idiomas / Languages
- 🇪🇸 [Español](#español)
- 🇺🇸 [English](#english)
- 🇧🇷 [Português](#português)
- 🇮🇩 [Indonesia](#indonesia)
- 🇷🇺 [Русский](#русский)

---

## 🇪🇸 Español

### ¿Qué es VisorX?

VisorX es un módulo Magisk/KSU/APatch que mejora los colores de tu pantalla en tiempo real usando SurfaceFlinger. Trae 6 perfiles listos para usar y un modo completamente personalizable. El perfil se aplica automáticamente en cada reinicio.

### 🎨 Perfiles disponibles

| Perfil | Saturación | Contraste | Brillo | Ideal para |
|---|---|---|---|---|
| 🟣 Ultra Suave | 1.05 | 1.02 | 0.98 | Uso diario suave |
| 🔵 Suave | 1.15 | 1.05 | 0.95 | Colores ligeramente mejorados |
| 🟡 Medio | 1.45 | 1.12 | 1.0 | Balance visual óptimo |
| 🔴 Fuerte | 1.8 | 1.2 | 1.0 | Colores vívidos e intensos |
| ⚙️ Custom | Libre | Libre | Libre | Control total desde WebUI |
| ⚪ Sistema | 1.0 | 1.0 | 1.0 | Restaura valores de fábrica |

### ✨ Características técnicas

- Aplica via `SurfaceFlinger` nativo — sin apps extra
- Props `persist.sys.sf` + `persist.vendor.display.miui` para máxima compatibilidad con HyperOS/MIUI
- Sharpness engine: ajuste de nitidez via `fb0/sharpness` y `persist.sys.sf.sharpness`
- HDR mode activado en pantallas compatibles
- Renderer backend `skiaglthreaded` para mayor fluidez visual
- Log automático en `Descargas/visual_rafael.log` con valores exactos aplicados
- Escucha cambios en tiempo real: al cambiar perfil en WebUI se aplica sin reiniciar

### 📱 Compatibilidad

| Dispositivo | Compatibilidad | Notas |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Máxima | Props MIUI/HyperOS completos activos |
| Samsung | ✅ Buena | SurfaceFlinger universal |
| OnePlus / OPPO | ✅ Buena | SurfaceFlinger universal |
| Motorola / Nokia | ✅ Buena | SurfaceFlinger universal |
| Cualquier Android 8+ | ✅ Base | Funciona en cualquier ROM |

### ⚙️ Gestores de root compatibles

| Gestor | Versión mínima | Estado |
|---|---|---|
| Magisk | v20.4+ | ✅ Soportado |
| KernelSU | Cualquiera | ✅ Soportado |
| APatch | Cualquiera | ✅ Soportado |

### 📲 Instalación

1. Descargá el ZIP desde la página oficial
2. Abrí Magisk / KSU / APatch
3. Instalá desde ZIP
4. Reiniciá el dispositivo
5. Abrí **KSU WebUI** → elegí tu perfil

> El panel de control se administra desde **KSU WebUI**. Desde ahí podés cambiar perfiles, ajustar valores custom y ver el estado del módulo en tiempo real.

### ❓ Preguntas frecuentes

**¿Necesito reiniciar para cambiar de perfil?**
No. Al cambiar el perfil desde la WebUI se aplica en segundos sin reiniciar.

**¿Afecta la batería?**
Mínimamente. Los cambios son a nivel de propiedades del sistema, no corren procesos pesados.

**¿Cómo vuelvo a los colores de fábrica?**
Desde la WebUI elegí el perfil **Sistema** o simplemente desinstalá el módulo.

**¿Funciona con otros módulos de rendimiento?**
Sí, es compatible con Project Diablo y ARG X9 del mismo autor.

**¿Dónde veo los valores aplicados?**
Se guarda un log en `Descargas/visual_rafael.log` con saturación, contraste y brillo exactos.

---

## 🇺🇸 English

### What is VisorX?

VisorX is a Magisk/KSU/APatch module that enhances your screen colors in real time using SurfaceFlinger. It comes with 6 ready-to-use profiles and a fully customizable mode. The profile is automatically applied on every reboot.

### 🎨 Available profiles

| Profile | Saturation | Contrast | Brightness | Best for |
|---|---|---|---|---|
| 🟣 Ultra Soft | 1.05 | 1.02 | 0.98 | Gentle daily use |
| 🔵 Soft | 1.15 | 1.05 | 0.95 | Slightly enhanced colors |
| 🟡 Medium | 1.45 | 1.12 | 1.0 | Optimal visual balance |
| 🔴 Strong | 1.8 | 1.2 | 1.0 | Vivid and intense colors |
| ⚙️ Custom | Free | Free | Free | Full control from WebUI |
| ⚪ System | 1.0 | 1.0 | 1.0 | Restores factory values |

### ✨ Technical features

- Applied via native `SurfaceFlinger` — no extra apps needed
- `persist.sys.sf` + `persist.vendor.display.miui` props for maximum HyperOS/MIUI compatibility
- Sharpness engine via `fb0/sharpness` and `persist.sys.sf.sharpness`
- HDR mode enabled on compatible displays
- `skiaglthreaded` render backend for smoother visuals
- Auto log at `Downloads/visual_rafael.log` with exact applied values
- Real-time profile switching — no reboot needed when changing profiles from WebUI

### 📱 Compatibility

| Device | Compatibility | Notes |
|---|---|---|
| Xiaomi / Redmi / POCO | ✅ Maximum | Full MIUI/HyperOS props |
| Samsung | ✅ Good | Universal SurfaceFlinger |
| OnePlus / OPPO | ✅ Good | Universal SurfaceFlinger |
| Any Android 8+ | ✅ Base | Works on any ROM |

### ⚙️ Supported root managers

| Manager | Min version | Status |
|---|---|---|
| Magisk | v20.4+ | ✅ Supported |
| KernelSU | Any | ✅ Supported |
| APatch | Any | ✅ Supported |

### 📲 Installation

1. Download the ZIP from the official page
2. Open Magisk / KSU / APatch
3. Install from ZIP
4. Reboot your device
5. Open **KSU WebUI** → choose your profile

> The control panel is managed from **KSU WebUI**. From there you can switch profiles, adjust custom values and see the module status in real time.

### ❓ FAQ

**Do I need to reboot to change profiles?**
No. Changing the profile from WebUI applies in seconds without rebooting.

**Does it affect battery life?**
Minimally. Changes are at system property level, no heavy processes running.

**How do I go back to factory colors?**
From WebUI choose the **System** profile, or simply uninstall the module.

**Is it compatible with other modules?**
Yes, compatible with Project Diablo and ARG X9 from the same author.

**Where can I see the applied values?**
A log is saved at `Downloads/visual_rafael.log` with exact saturation, contrast and brightness values.

---

## 🇧🇷 Português

### O que é VisorX?

VisorX é um módulo Magisk/KSU/APatch que melhora as cores da sua tela em tempo real usando SurfaceFlinger. Traz 6 perfis prontos e um modo totalmente personalizável. O perfil é aplicado automaticamente a cada reinicialização.

### 🎨 Perfis disponíveis

| Perfil | Saturação | Contraste | Brilho |
|---|---|---|---|
| 🟣 Ultra Suave | 1.05 | 1.02 | 0.98 |
| 🔵 Suave | 1.15 | 1.05 | 0.95 |
| 🟡 Médio | 1.45 | 1.12 | 1.0 |
| 🔴 Forte | 1.8 | 1.2 | 1.0 |
| ⚙️ Custom | Livre | Livre | Livre |
| ⚪ Sistema | 1.0 | 1.0 | 1.0 |

### 📱 Compatibilidade

| Dispositivo | Compatibilidade |
|---|---|
| Xiaomi / Redmi / POCO | ✅ Máxima |
| Samsung / OnePlus | ✅ Boa |
| Qualquer Android 8+ | ✅ Base |

### 📲 Instalação

1. Baixe o ZIP na página oficial
2. Abra o Magisk / KSU / APatch
3. Instale pelo ZIP
4. Reinicie
5. Abra o **KSU WebUI** → escolha o perfil

---

## 🇮🇩 Indonesia

### Apa itu VisorX?

VisorX adalah modul Magisk/KSU/APatch yang meningkatkan warna layar secara real time menggunakan SurfaceFlinger. Dilengkapi 6 profil siap pakai dan mode yang dapat dikustomisasi sepenuhnya.

### 🎨 Profil tersedia

| Profil | Saturasi | Kontras | Kecerahan |
|---|---|---|---|
| 🟣 Ultra Lembut | 1.05 | 1.02 | 0.98 |
| 🔵 Lembut | 1.15 | 1.05 | 0.95 |
| 🟡 Sedang | 1.45 | 1.12 | 1.0 |
| 🔴 Kuat | 1.8 | 1.2 | 1.0 |
| ⚙️ Custom | Bebas | Bebas | Bebas |
| ⚪ Sistem | 1.0 | 1.0 | 1.0 |

### 📱 Kompatibilitas

| Perangkat | Kompatibilitas |
|---|---|
| Xiaomi / Redmi / POCO | ✅ Maksimal |
| Samsung / OnePlus | ✅ Baik |
| Android 8+ manapun | ✅ Dasar |

### 📲 Instalasi

1. Unduh ZIP dari halaman resmi
2. Buka Magisk / KSU / APatch
3. Pasang dari ZIP
4. Reboot
5. Buka **KSU WebUI** → pilih profil

---

## 🇷🇺 Русский

### Что такое VisorX?

VisorX — модуль Magisk/KSU/APatch, улучшающий цвета экрана в реальном времени через SurfaceFlinger. Включает 6 готовых профилей и полностью настраиваемый режим.

### 🎨 Доступные профили

| Профиль | Насыщенность | Контраст | Яркость |
|---|---|---|---|
| 🟣 Ультра мягкий | 1.05 | 1.02 | 0.98 |
| 🔵 Мягкий | 1.15 | 1.05 | 0.95 |
| 🟡 Средний | 1.45 | 1.12 | 1.0 |
| 🔴 Сильный | 1.8 | 1.2 | 1.0 |
| ⚙️ Custom | Свободно | Свободно | Свободно |
| ⚪ Система | 1.0 | 1.0 | 1.0 |

### 📱 Совместимость

| Устройство | Совместимость |
|---|---|
| Xiaomi / Redmi / POCO | ✅ Максимальная |
| Samsung / OnePlus | ✅ Хорошая |
| Android 8+ любой | ✅ Базовая |

### 📲 Установка

1. Скачайте ZIP с официальной страницы
2. Откройте Magisk / KSU / APatch
3. Установите из ZIP
4. Перезагрузите устройство
5. Откройте **KSU WebUI** → выберите профиль

---

## 📄 Licencia / License

Apache License 2.0 — By_Rafael System © 2026
