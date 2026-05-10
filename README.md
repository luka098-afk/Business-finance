# 📈 Business Finance

> Controlá tus compras, ventas y ganancias desde el celular — sin registro, sin internet, sin límites.



![Version](https://img.shields.io/badge/version-1.0.0-00d68f?style=flat-square)




![PWA](https://img.shields.io/badge/PWA-instalable-4d9eff?style=flat-square)




![Android](https://img.shields.io/badge/Android-APK%20disponible-a78bfa?style=flat-square)




![License](https://img.shields.io/badge/license-MIT-f5b731?style=flat-square)




![Offline](https://img.shields.io/badge/offline-100%25-00d68f?style=flat-square)




![IA](https://img.shields.io/badge/hecho%20con-IA-ff4d6d?style=flat-square)



---

## ¿Qué es?

**Business Finance** es una app diseñada para cualquier persona que revende productos y necesita llevar el control de su negocio de forma simple y rápida. Funciona para ropa, tecnología, alimentos, accesorios — cualquier rubro.

Sin registro. Sin servidor. Sin suscripción. Todo se guarda localmente en tu dispositivo.

---

## ✨ Funciones

### 💼 Finanzas
- Registrá artículos con costo de compra, arreglos, gastos extra y precio de venta
- Calculá ganancia y margen (%) en tiempo real antes de agregar
- 4 estados por artículo: Pendiente / Vendido / Trueque / Reparación
- Filtrá por estado y buscá por nombre o notas
- Exportá todo a **CSV** para abrir en Excel

### 📅 Por mes
- Historial separado mes a mes con navegación hacia atrás
- Estadísticas mensuales: invertido, ganancia, vendidos, pendientes
- **Gráfico de barras** de ganancias de los últimos 6 meses
- Filtrá por estado dentro de cada mes

### 💵 Dólares
- Registrá tus ahorros en dólares con historial de ingresos y egresos
- Establecé una **meta de ahorro** con barra de progreso
- Cotización del dólar configurable — convierte a pesos automáticamente en toda la app

### 🔐 Backup
- Exportá todos tus datos en un archivo **JSON** (registros + dólares + cotización)
- Restaurá el backup cuando quieras sin perder nada
- Ideal antes de formatear o cambiar de dispositivo

---

## 📥 Descarga

### Android — APK directa
> Instalación sin Play Store. Activá "Fuentes desconocidas" en Ajustes → Seguridad antes de instalar.

➡️ **[Descargar APK v1.0.0](../../releases/latest)**

### Versión web — PWA instalable
Abrí la app en Chrome y tocá **"Agregar a pantalla de inicio"** para instalarla sin Play Store.

➡️ **[Abrir app web](https://luka098-afk.github.io/Business-finance)**

---

## 📱 Cómo instalar la APK

1. Descargá el archivo `.apk` desde la sección **Releases**
2. En tu Android abrí **Ajustes → Seguridad → Fuentes desconocidas** y activalo
3. Abrí el archivo `.apk` descargado
4. Tocá **Instalar**
5. Listo — la app aparece en tu cajón como cualquier app normal

---

## 🚀 Uso rápido

```
1. Abrí la app
2. Configurá la cotización del dólar (banner superior)
3. Tab "Finanzas" → agregá tu primer registro
4. Cambiá el estado a Vendido cuando lo vendas
5. Revisá tus ganancias del mes en tab "Mes"
6. Guardá tus ahorros en dólares en tab "Dólares"
7. Exportá backup regularmente para no perder datos
```

---

## 🗂 Estructura del proyecto

```
business-finance/
├── index.html          # App completa (HTML + CSS + JS)
├── manifest.json       # Configuración PWA
├── service-worker.js   # Cache offline
├── icon.png            # Ícono de la app
├── icon.svg            # Ícono vectorial
└── README.md
```

---

## 🛠 Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 / CSS3 / JS vanilla | App completa sin frameworks |
| localStorage | Persistencia local de datos |
| Service Worker | Funcionamiento offline |
| Web App Manifest | Instalación como PWA |
| Capacitor | Empaquetado como APK nativa |
| Google Fonts | Space Mono + DM Sans |

Sin dependencias externas. Sin backend. Sin base de datos en la nube.

---

## 🤖 Hecho con IA

Este proyecto fue desarrollado con la asistencia de inteligencia artificial. Desde el diseño visual hasta la lógica de negocio, el CSS, las animaciones y la arquitectura general — todo fue construido en colaboración con IA.

> Una demostración de lo que se puede lograr combinando una idea clara con las herramientas correctas.

---

## 📄 Licencia

MIT © 2026 — libre para usar, modificar y distribuir.
Ver archivo [LICENSE](LICENSE) para más detalles.

---

## 🤝 Contribuciones

¿Encontraste un bug o tenés una idea? Abrí un [Issue](../../issues) o mandá un Pull Request. Toda ayuda es bienvenida.

---

<div align="center">
  Hecho con 💚 y con la ayuda de IA
</div>
