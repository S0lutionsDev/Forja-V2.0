# 🔨 Forja

**Gestión de Proyectos Personales — Local, Sin Internet, 100% Privado**

*Desarrollado por **SolutionsDev** | Buenos Aires, Argentina*

---

## ¿Qué es Forja?

Forja es una solución integral de gestión de proyectos personales diseñada para ser completamente **local-first**, **privado** y **sin dependencia de internet**. Todos tus datos residen exclusivamente en tu computadora, garantizando máxima seguridad y control total.

### Principios Core
- 🔐 **100% Local**: Sin sincronización a la nube
- 🔒 **Completamente Privado**: Solo tú accedes a tus datos
- ⚡ **Sin Conexión a Internet**: Funciona totalmente offline
- 🚫 **Sin Suscripciones**: Compra una licencia y úsala de por vida
- 💾 **Respaldos Fáciles**: Exporta e importa tu base de datos en segundos

---

## 🚀 Características Principales

### 🔨 Gestión de Proyectos
Organiza todos tus proyectos en un único lugar con estructura clara y fácil de navegar. Asigna colores, descripciones y vincula repositorios o archivos locales.

### 📋 Seguimiento de Tareas
Administra tareas con:
- **Prioridades**: Baja, Media, Alta, Crítica
- **Estados**: Pendiente, En Progreso, Completada, Bloqueada
- **Horas**: Estimadas vs Reales para detectar desvíos
- **Fechas**: Vencimiento y seguimiento de deadlines

### ✅ To-Do Lists
Listas de tareas rápidas y simples para anotaciones diarias. Marca elementos con checkbox cuando logres avances.

### 📂 Gestión de Archivos
Almacena y organiza archivos (imágenes, PDFs, hojas de cálculo) directamente vinculados a tus proyectos. Todo almacenado localmente.

### 📝 Documentación Enriquecida
Editor completo con soporte para:
- Textos formateados (negrita, cursiva, enlaces)
- Listas y viñetas
- Bloques de código
- Imágenes incrustadas
- Estructuras jerárquicas

### 👥 Múltiples Perfiles
Separa tus proyectos por contextos:
- **Trabajo**: Proyectos profesionales
- **Personal**: Metas y hobbies
- **Hogar**: Tareas domésticas
- **Programación**: Desarrollo y learning
- **Estudios**: Investigación académica

Cada perfil es completamente independiente con sus propios datos, iconos y colores.

### 🎨 Personalización Completa
- **Temas**: Oscuro y Claro
- **Colores de Acento**: 6 opciones modernas
- **Tamaño de Fuente**: 12px a 20px ajustable
- **Preferencias Persistentes**: Se guardan automáticamente

### 🛡️ Sistema de Licencias Offline
- **DEMO FULL**: 3 meses gratuitos (90 días)
- **PRO Anual**: 12 meses de acceso completo
- **PRO Perpetua**: Licencia de por vida
- Sin conexión a internet requerida

### 💾 Backup & Restore
Exporta toda tu base de datos a un archivo `.db` y restauralo en cualquier momento o máquina. Máxima seguridad de datos.

### 🎯 Kanban Visual
Arrastra y suelta tareas entre estados (Pendiente → En Progreso → Completada) para organización visual intuitiva.

---

## 👥 Sistema de Múltiples Perfiles (V2.0)

### Características
- **Aislamiento Total**: Cada perfil tiene sus proyectos, tareas, archivos y documentación
- **Cambio Instantáneo**: Salta entre perfiles sin perder ningún dato
- **Personalización Visual**: Elige icono y color único para cada perfil
- **Perfil Favorito**: Se carga automáticamente al abrir Forja
- **Gestión Completa**: Crear, editar, eliminar perfiles según necesites

### Iconos Disponibles
Maletín 💼 | Casa 🏠 | Código 💻 | Juego 🎮 | Corazón ❤️ | Música 🎵 | Cámara 📷 | Rayo ⚡

### Colores Disponibles
Azul | Verde | Púrpura | Rosa | Naranja | Turquesa + 4 más

---

## 🎨 Personalización

### Acceso a Ajustes
Haz clic en el **ícono de engranaje** en la barra lateral izquierda para acceder a todas las opciones de personalización.

### Opciones
| Opción | Valores |
|--------|---------|
| **Tema** | Oscuro, Claro |
| **Color de Acento** | 6 colores modernos |
| **Tamaño de Fuente** | 12px - 20px |
| **Guardado** | Automático |

---

## 🛡️ Sistema de Licencias

### Tipos de Licencia

| Tipo | Duración | Costo | Características |
|------|----------|-------|-----------------|
| **DEMO FULL** | 3 meses (90 días) | Gratuito | Acceso completo durante prueba |
| **PRO Anual** | 12 meses | Contactar | Acceso ilimitado + soporte |
| **PRO Perpetua** | Permanente | Contactar | Licencia de por vida |

### Activar Licencia
1. Ve a **Configuración** → **Licencia**
2. Presiona **"Subir Archivo de Licencia"**
3. Selecciona tu archivo `.lic`
4. Los beneficios se activan inmediatamente

### Código UID
Si soporte lo requiere, encontrarás tu identificación de máquina (UID) en la sección de Licencia.

---

## 🛠️ Stack Tecnológico

**Frontend & Desktop:**
- **Electron** 29 - Aplicación de escritorio multiplataforma
- **React** 18 - Interfaz de usuario moderna
- **Tailwind CSS** 3 - Estilos y diseño responsivo
- **Vite** 5 - Build tool ultrarrápido

**Backend & Datos:**
- **SQLite** (better-sqlite3) - Base de datos local embebida
- **Python** - Sistema de licencias y lógica backend

### Arquitectura
```
┌─────────────────────────────────────┐
│   Electron (Desktop Wrapper)        │
│  React UI + Tailwind CSS            │
│  ┌─────────────────────────────┐   │
│  │  SQLite Local Database      │   │
│  │  (Proyectos, Tareas, etc)   │   │
│  └─────────────────────────────┘   │
│  ┌─────────────────────────────┐   │
│  │  Python License System      │   │
│  │  (Offline Validation)       │   │
│  └─────────────────────────────┘   │
└─────────────────────────────────────┘
```

---

## 📊 Casos de Uso

### Para Desarrolladores
- Gestiona múltiples proyectos de código
- Seguimiento de bugs y features
- Documentación técnica
- Histórico de cambios y notas

### Para Profesionales
- Gestión de proyectos laborales
- Seguimiento de deadlines
- Documentación profesional
- Separación trabajo/personal

### Para Estudiantes
- Organización académica
- Proyectos de investigación
- Notas y apuntes
- Seguimiento de tareas

### Para Propietarios
- Gestión de tareas del hogar
- Presupuestos y finanzas
- Proyectos personales
- Planes y metas

---

## 🔐 Seguridad y Privacidad

### Principios de Diseño
- ✅ **Cero Rastreo**: No recolectamos datos
- ✅ **Cero Sincronización**: Nada sale de tu computadora
- ✅ **Cero Conexión**: Funciona completamente offline
- ✅ **Máxima Privacidad**: Solo tú tienes acceso

### Respaldo de Datos
Realiza backups regulares exportando tu base de datos. Guarda el archivo `.db` en:
- Memoria USB
- Disco duro externo
- Almacenamiento personal en la nube (si lo deseas)

---

## 🚀 Comenzar

### Requisitos Mínimos
- **SO**: Windows 10+, macOS 10.14+, Linux (Ubuntu 18.04+)
- **RAM**: 512 MB mínimo (recomendado 2GB)
- **Espacio**: 200 MB para instalación

### Primera Vez
1. Instala Forja desde [www.solutionsdev.com.ar](https://www.solutionsdev.com.ar)
2. Inicia la aplicación
3. Comienza con licencia DEMO FULL (3 meses gratis)
4. ¡Crea tu primer perfil y proyecto!

### Migración desde Otra Herramienta
1. Exporta tus datos desde la herramienta anterior (si es posible)
2. En Forja, importa tus proyectos manualmente o por archivos
3. Reorganiza según los perfiles que necesites
4. ¡Listo para comenzar!

---

## 📞 Soporte

### Canales de Contacto

| Canal | Información |
|-------|-------------|
| 📧 **Email** | soporte@solutionsdev.com.ar |
| 🌐 **Web** | www.solutionsdev.com.ar |
| 📍 **Ubicación** | Buenos Aires, Argentina |

### Tiempo de Respuesta
- **Critical**: < 2 horas
- **Normal**: < 24 horas
- **General**: < 48 horas

### Base de Conocimiento
Consulta la documentación completa y FAQ en [www.solutionsdev.com.ar/docs](https://www.solutionsdev.com.ar/docs)

---

## 💡 Tips y Mejores Prácticas

### Organización
- Usa perfiles para separar clara y completamente tus áreas
- Asigna colores consistentes a tipos similares de proyectos
- Mantén nombres descriptivos pero concisos

### Productividad
- Revisa tu dashboard cada mañana
- Actualiza horas reales para mejorar estimaciones
- Usa to-do lists para tareas < 30 minutos

### Seguridad
- Realiza backup semanal mínimo
- Guarda backups en ubicaciones diferentes
- Prueba restaurar ocasionalmente para verificar integridad

### Performance
- Archiva proyectos completados
- Limpia tareas antiguas regularmente
- Optimiza base de datos si se vuelve lenta

---

## 📈 Roadmap Futuro

Planeamos agregar en futuras versiones:
- 📱 Aplicación móvil (companion)
- 🤖 Asistente AI para sugerencias
- 📊 Reportes y análisis avanzados
- 🔄 Sincronización opcional (manteniendo privacidad)
- ⏱️ Time tracking automático
- 🎯 Integración de calendarios
- 📤 Exportación a múltiples formatos

---

## ⚖️ Licencia

Forja es software propietario desarrollado por SolutionsDev. 

Consulta la licencia completa incluida con la aplicación.

---

## 🙏 Agradecimientos

Forja fue construido pensando en usuarios como vos, que valoran privacidad, simplicidad y productividad.

Gracias por elegir Forja.

---

## 📖 Documentación Completa

Para más información, consulta el **Manual de Usuario** (`MANUAL_USUARIO.pdf`) incluido con la aplicación.

---

<div align="center">

**Forja — Forge Your Projects.**

*© 2026 SolutionsDev. Todos los derechos reservados.*

[🌐 www.solutionsdev.com.ar](https://www.solutionsdev.com.ar) | [📧 soporte@solutionsdev.com.ar](mailto:soporte@solutionsdev.com.ar)

</div>
