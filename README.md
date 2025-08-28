# 🌤️ Weather & Air Quality App

Aplicación web de clima y calidad del aire desarrollada en ⚛️ React que muestra información meteorológica en tiempo real basada en la 📍 geolocalización del usuario. Incluye datos de 🌡️ temperatura, 💧 humedad, 🔽 presión atmosférica, 💨 velocidad del viento y 🏭 índice de calidad del aire (AQI) utilizando la API de AirVisual.

## 🌟 Características

- **Geolocalización automática** para obtener datos precisos de tu ubicación
- **Información meteorológica completa** con temperatura, humedad y presión
- **Datos de calidad del aire** con índice AQI en tiempo real
- **Interfaz responsive** optimizada para dispositivos móviles
- **Navegación por pestañas** con secciones de Ubicación, Noticias y Recursos
- **Diseño moderno** con iconos intuitivos y animaciones suaves
- **Loader animado** durante la carga de datos
- **Datos de viento** con velocidad y dirección

## 🚀 Demo en Vivo

🔗 **[Ver Demo](https://00007-weather-air-quality.netlify.app)**

## 🛠️ Tecnologías Utilizadas

- **React 17** - Framework principal
- **Axios** - Cliente HTTP para API calls
- **AirVisual API** - Datos meteorológicos y de calidad del aire
- **CSS3** - Estilos y animaciones
- **Geolocation API** - Obtención de coordenadas del usuario
- **Firebase** - Configuración de backend

## 📁 Estructura del Proyecto

```
00007-weather-app/
├── public/
│   ├── index.html
│   ├── logo.png
│   └── robots.txt
├── src/
│   ├── App.js                 # Componente principal
│   ├── index.js              # Punto de entrada
│   ├── index.css             # Estilos globales
│   ├── img/                  # Recursos gráficos
│   │   ├── thermometer.png
│   │   ├── humidity.png
│   │   ├── gauge.png
│   │   ├── windy.png
│   │   └── ...
│   ├── loader/
│   │   ├── Loader.jsx        # Componente de carga
│   │   └── loader.css
│   ├── nearest-city/
│   │   ├── nearest-city.jsx  # Información del clima
│   │   └── nearest-city.css
│   ├── notices/
│   │   ├── notices.jsx       # Sección de noticias
│   │   └── styles.css
│   └── resources/
│       ├── resources.jsx     # Sección de recursos
│       └── styles.css
├── package.json
└── README.md
```

## 🎨 Características de Diseño

### Header
- Iconos de información, logo y notificaciones
- Diseño minimalista y funcional

### Navegación
- Pestañas deslizantes con transiciones suaves
- Indicador visual de sección activa
- Navegación táctil optimizada

### Sección Principal (Ubicación)
- **Ubicación actual** con icono de navegación
- **Índice AQI** destacado visualmente
- **Datos meteorológicos** organizados con iconos:
  - 🌡️ Temperatura en Celsius
  - 🔽 Presión atmosférica en hPa
  - 💧 Humedad relativa en porcentaje
  - 💨 Velocidad del viento en m/s
  - 🧭 Dirección del viento en grados

### Secciones Adicionales
- **Noticias** - Información relevante sobre clima
- **Recursos** - Enlaces y herramientas útiles

## 🚀 Instalación y Uso

1. **Clona el repositorio:**
   ```bash
   git clone https://github.com/FROSTYLAN/00007-weather-air-quality.git
   ```

2. **Navega al directorio:**
   ```bash
   cd 00007-weather-air-quality
   ```

3. **Instala las dependencias:**
   ```bash
   npm install
   ```

4. **Inicia el servidor de desarrollo:**
   ```bash
   npm start
   ```

5. **Abre tu navegador en:**
   ```
   http://localhost:3000
   ```

## 🔑 Configuración de API

Este proyecto utiliza la API de AirVisual. La clave API está incluida en el código para fines de demostración. Para uso en producción:

1. Regístrate en [AirVisual API](https://www.iqair.com/air-pollution-data-api)
2. Obtén tu clave API personal
3. Reemplaza la clave en `src/App.js`:
   ```javascript
   const API_KEY = "tu-clave-api-aqui";
   ```

## 📱 Responsividad

El diseño está optimizado para:
- 💻 **Desktop** - Experiencia completa con navegación fluida
- 📱 **Mobile** - Interfaz táctil optimizada
- 📟 **Tablet** - Diseño adaptativo intermedio

## 🎯 Funcionalidades Principales

- **Detección automática de ubicación** usando Geolocation API
- **Datos en tiempo real** de temperatura, humedad, presión y viento
- **Índice de calidad del aire** con valores AQI actualizados
- **Interfaz deslizante** entre diferentes secciones
- **Manejo de errores** para casos de fallo en la API o geolocalización
- **Estados de carga** con componente Loader personalizado

## 🔧 Scripts Disponibles

- `npm start` - Inicia el servidor de desarrollo
- `npm build` - Construye la aplicación para producción
- `npm test` - Ejecuta las pruebas
- `npm eject` - Expone la configuración de webpack

## 🌍 APIs Utilizadas

- **AirVisual API** - Datos meteorológicos y de calidad del aire
- **Geolocation API** - Coordenadas del usuario

## 🔧 Posibles Mejoras

- [ ] Añadir pronóstico extendido de 7 días
- [ ] Implementar modo oscuro
- [ ] Agregar gráficos de tendencias
- [ ] Incluir alertas meteorológicas
- [ ] Añadir búsqueda manual de ciudades
- [ ] Implementar notificaciones push
- [ ] Agregar mapas interactivos
- [ ] Incluir datos históricos

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Por favor:

1. Fork el proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 👨‍💻 Autor

**Charles Castillo (FROSTYLAN)**
- GitHub: [@FROSTYLAN](https://github.com/FROSTYLAN)
- LinkedIn: [Charles Castillo](https://linkedin.com/in/charles-castillo-772968234)

---

⭐ ¡No olvides dar una estrella al proyecto si te gustó!

*Desarrollado con ❤️ por el Grupo 8*