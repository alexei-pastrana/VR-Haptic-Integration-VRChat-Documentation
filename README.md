# VR-Haptic-Integration-VRChat-Documentation
Documentación técnica completa del proyecto de integración háptica con VRChat. Cubre desde los fundamentos de la plataforma hasta la programación con UdonSharp, creación de mundos interactivos y conexión con dispositivos hápticos físicos (chalecos y guantes).

## Productos finales del proyecto
| Producto | Descripción | Link |
|----------------------------------|-------------|------|
| Manual Operativo | Guía interactiva paso a paso para replicar el sistema desde cero | [Abrir manual](https://vrchat-guide.netlify.app) |
| Documentación completa | Base de conocimiento, bitácora de investigación y roadmap del proyecto | [Notion — HOME VRChat](https://prairie-guan-bf4.notion.site/HOME-VRCHAT-30f1faedee6e8033baa0fb578c024d0f) |

## ¿De qué trata este proyecto?
El objetivo es desarrollar dominio completo del ecosistema VRChat e integrar dispositivos hápticos reales (chaleco bHaptics, guantes LucidGloves) para que el usuario pueda **sentir físicamente** las interacciones dentro de un entorno de realidad virtual social.

El proyecto tiene dos productos finales:

| Producto | Descripción |
|----------|-------------|
| **Documentación de aprendizaje** | Bitácora técnica del proceso real: lo que funcionó, lo que no, y por qué |
| **Manual operativo replicable** | Guía paso a paso para que cualquier persona pueda replicar el sistema desde cero |

## Tecnologías utilizadas

| Tecnología | Uso en el proyecto |
|------------|-------------------|
| **VRChat** | Plataforma de realidad virtual social donde se ejecuta el proyecto |
| **Unity 2022.3.22f1** | Motor de juego usado para crear mundos y avatares |
| **UdonSharp (C#)** | Lenguaje de programación para lógica dentro de VRChat |
| **VRChat SDK 3.x** | Kit de desarrollo oficial para subir contenido a VRChat |
| **OSC (Open Sound Control)** | Protocolo de comunicación entre VRChat y los dispositivos hápticos |
| **bHaptics TactSuit** | Chaleco háptico con 40 motores ERM integrado vía OSC |
| **LucidGloves (DIY)** | Guantes hápticos open source con force feedback y finger tracking |
| **SteamVR** | Plataforma VR para conectar guantes y trackers en modo PCVR |
| **Meta Quest Link** | Software para conectar Meta Quest al PC en modo PCVR |

## Estado del proyecto

| Elemento | Estado |
|----------|--------|
| Cuenta VRChat | Creada |
| Nivel de usuario | Visitor → trabajando hacia User |
| Entorno de desarrollo (Unity + SDK) | Configurado |
| Primer script UdonSharp | Funcional |
| Primer mundo en VRChat | En construcción |
| Integración háptica (OSC + bHaptics) | En progreso |
| Chaleco háptico | En gestión |
| Guantes hápticos (LucidGloves) | Pendiente |
| Manual replicable completo | En construcción |

## Requisitos para replicar el proyecto
- PC con Windows 10/11 (64-bit), mínimo 8GB RAM
- Unity 2022.3.22f1 (instalado vía VRChat Creator Companion)
- Cuenta nativa de VRChat (creada en vrchat.com, no Steam)
- Chaleco háptico bHaptics (cualquier modelo) o LucidGloves DIY
- Visual Studio 2022 Community

## Referencias principales
| Recurso | URL |
|---------|-----|
| VRChat Creator Documentation | https://creators.vrchat.com |
| UdonSharp Documentation | https://udonsharp.docs.vrchat.com |
| bHaptics VRChatOSC (oficial) | https://github.com/bhaptics/VRChatOSC |
| LucidGloves (open source) | https://github.com/LucidVR/lucidgloves |
| OpenGloves Driver | https://store.steampowered.com/app/1574050/OpenGloves/ |
| SenseShift (DIY haptics) | https://github.com/senseshift/senseshift-firmware |
| Unity 2022.3.22f1 | https://creators.vrchat.com/sdk/upgrade/current-unity-version/ |
| Random Nerd Tutorials — ESP32 | https://randomnerdtutorials.com |
