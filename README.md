# 🦕 ARK Mobile Enhancement Toolkit

> **Herramientas, parches y guías para mejorar ARK: Survival Evolved Mobile**

---

## 📋 Sobre este proyecto

Este proyecto nació de una comunidad que se niega a dejar morir su juego favorito. ARK: Survival Evolved Mobile fue abandonado oficialmente por Studio Wildcard, pero eso no significa que tenga que desaparecer.

Aquí encontrarás herramientas para:

- 🔧 **Fixear problemas de rendimiento** causados por servicios de Google obsoletos
- 🎨 **Mejorar los gráficos** con texturas, materiales y shaders optimizados
- 🎯 **Ajustar el aim assist** y otros parámetros de gameplay
- 📚 **Documentación completa** para que cualquiera pueda modificar su juego
- 🛡️ **Eliminar dependencias innecesarias** que causan crashes

## ⚠️ Aviso Legal

Este proyecto es **solo con fines educativos y de modding personal**. Todos los archivos del juego pertenecen a Studio Wildcard / Snail Games / Warner Bros. Este repositorio NO contiene ningún archivo del juego original.

**No distribuyas archivos modificados del juego.** Úsalos solo en tu dispositivo personal.

## 🛠️ Herramientas Necesarias

| Herramienta | Versión | Para qué | Descarga |
|-------------|---------|----------|----------|
| Java JDK | 17+ | Requerido por Apktool | [Adoptium](https://adoptium.net/) |
| Apktool | 2.9+ | Decompilar/recompilar APK | [apktool.org](https://apktool.org/) |
| UModel | 1.5+ | Extraer assets de UE4 | [gildor.org](https://www.gildor.org/projects/umodel) |
| Unreal Engine 4 | 4.27 | Modificar assets | [Epic Games](https://www.unrealengine.com/download) |
| Notepad++ | Latest | Editar código y configs | [notepad-plus-plus.org](https://notepad-plus-plus.org/) |

## 📁 Estructura del Proyecto

```
ark-mobile-enhancement/
├── docs/                   # Guías y documentación
│   ├── como-empezar.md     # Guía para principiantes
│   ├── herramientas.md     # Setup de herramientas
│   └── fix-google-services.md  # Fix de Google Play Services
├── tools/                  # Scripts y herramientas
│   ├── setup-tools.bat     # Instalar todo automáticamente
│   ├── decompile-apk.bat   # Decompilar el APK
│   ├── extract-assets.bat  # Extraer assets del OBB
│   └── rebuild-apk.bat     # Recompilar APK modificado
├── patches/                # Parches y configuraciones
│   ├── config/             # Archivos de configuración
│   └── README.md           # Explicación de parches
└── .gitignore              # Protección de archivos
```

## 🚀 Cómo Empezar

### 1. Clona este repositorio
```bash
git clone https://github.com/TU-USUARIO/ark-mobile-enhancement.git
cd ark-mobile-enhancement
```

### 2. Organiza tu PC
```
ArkMobile/
├── 1-original/       # APK y OBB sin modificar (respaldo)
├── 2-workspace/      # Aquí trabajamos
└── 3-build/          # Resultado final
```

### 3. Instala las herramientas
```bash
# Ejecuta el script de instalación (requiere CMD como Administrador)
tools\setup-tools.bat
```

### 4. Decompila el APK
```bash
tools\decompile-apk.bat
```

### 5. Extrae los assets
```bash
tools\extract-assets.bat
```

## 📊 Estado del Proyecto

| Tarea | Estado | Progreso |
|-------|--------|----------|
| Fix Google Play Services | 🔴 En progreso | 0% |
| Mejora de texturas | 🔴 Pendiente | 0% |
| Mejora de materiales/shaders | 🔴 Pendiente | 0% |
| Parche de aim assist | 🔴 Pendiente | 0% |
| Parche de rendimiento | 🔴 Pendiente | 0% |
| Herramienta de UI personalizada | 🔴 Pendiente | 0% |
| Servidor alternativo (largo plazo) | 🔴 Pendiente | 0% |

## 👥 Cómo Contribuir

1. **Haz un Fork** de este repositorio
2. Crea una **rama** para tu cambio (`git checkout -b mi-mejora`)
3. Haz tus cambios y **comitea** (`git commit -m 'Mi mejora'`)
4. **Push** a tu fork (`git push origin mi-mejora`)
5. Abre un **Pull Request**

## 📄 Licencia

Este proyecto está licenciado bajo **MIT License** - Puedes usar, modificar y distribuir estas herramientas libremente.

Los archivos del juego ARK: Survival Evolved Mobile pertenecen a sus respectivos propietarios y NO están incluidos en este repositorio.
