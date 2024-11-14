# 1 a 1 - Aplicación para Fortalecer Vínculos Personales

¡Bienvenido al proyecto **1 a 1**! Esta es una aplicación móvil multiplataforma diseñada para ayudar a las personas a fortalecer sus relaciones uno a uno con familiares y seres queridos. Utiliza tecnología de Inteligencia Artificial para ofrecer sugerencias y planes personalizados para mantener relaciones saludables y constructivas.

## Índice

- [Características](#características)
- [Requisitos Previos](#requisitos-previos)
- [Instalación](#instalación)
- [Ejecución de la Aplicación](#ejecución-de-la-aplicación)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Dependencias Principales](#dependencias-principales)
- [Próximos Pasos](#próximos-pasos)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

---

## Características

- **Gestión de Vínculos:** Agrega, edita y elimina relaciones personales.
- **Integración con IA:** Simulación de sugerencias personalizadas mediante un servicio de modelo de lenguaje.
- **Navegación Intuitiva:** Fácil acceso a diferentes secciones de la aplicación.
- **Interfaz de Usuario Simple:** Diseño sencillo para una experiencia de usuario amigable.

---

## Requisitos Previos

- **Node.js** y **npm** instalados en tu sistema.
- **Expo CLI** instalado globalmente.
  
  ```bash
  npm install -g expo-cli
  ```
  
- Un emulador de Android/iOS o un dispositivo físico conectado.

---

## Instalación

Sigue estos pasos para configurar el proyecto en tu máquina local:

1. **Clona este repositorio:**

   ```bash
   git clone https://github.com/tu-usuario/1a1-app.git
   ```

2. **Navega al directorio del proyecto:**

   ```bash
   cd 1a1-app
   ```

3. **Instala las dependencias:**

   ```bash
   npm install
   ```

---

## Ejecución de la Aplicación

Para iniciar la aplicación en modo de desarrollo:

```bash
expo start
```

Esto abrirá la interfaz de Expo en tu navegador, desde donde puedes:

- Escanear el código QR con la aplicación Expo Go en tu dispositivo móvil.
- Ejecutar la aplicación en un emulador de Android o iOS.

---

## Estructura del Proyecto

```
1a1-app/
├── App.js
├── package.json
├── /components
│   ├── LoginScreen.js
│   ├── HomeScreen.js
│   ├── AddLinkScreen.js
│   └── LinkDetailScreen.js
├── /services
│   └── LanguageModelService.js
└── /assets
    └── (imágenes y otros recursos estáticos)
```

- **App.js:** Punto de entrada principal de la aplicación.
- **/components:** Componentes de React Native que representan las pantallas de la aplicación.
- **/services:** Servicios para la lógica de negocios y comunicación con APIs (actualmente simulado).
- **/assets:** Recursos estáticos como imágenes, fuentes, etc.

---

## Dependencias Principales

- **React Native:** Framework para construir aplicaciones móviles nativas.
- **Expo:** Plataforma para facilitar el desarrollo y la ejecución de aplicaciones React Native.
- **React Navigation:** Manejo de la navegación entre pantallas.

Instaladas a través de npm y Expo:

```bash
npm install @react-navigation/native @react-navigation/stack
expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
```

---

## Próximos Pasos

Este es un prototipo básico y puede expandirse con las siguientes mejoras:

- **Integración Real con un LLM:**
  - Implementar la integración con una API de modelo de lenguaje como OpenAI GPT-4 para obtener sugerencias personalizadas reales.
  
- **Persistencia de Datos:**
  - Añadir almacenamiento local o en la nube para guardar vínculos y sugerencias.
  - Opciones como AsyncStorage o servicios en la nube como Firebase.

- **Autenticación de Usuarios:**
  - Implementar un sistema de autenticación para manejar cuentas de usuario.
  - Proveedores como Firebase Auth o Auth0.

- **Notificaciones Push:**
  - Agregar notificaciones para recordar al usuario sobre planes y sugerencias.
  - Utilizar Expo Notifications o librerías nativas.

- **Mejoras en la Interfaz de Usuario:**
  - Aplicar estilos más avanzados y componentes personalizados.
  - Utilizar librerías como React Native Paper o NativeBase.

---

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas contribuir al proyecto:

1. Haz un fork del repositorio.
2. Crea una nueva rama para tu función o corrección de errores.
3. Realiza tus cambios y haz commits descriptivos.
4. Envía un pull request detallando tus cambios.

---

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

---

## Contacto

Si tienes preguntas o necesitas más información, puedes contactarme a través de:


- **GitHub:** [galenzo17](https://github.com/galenzo17)

---

¡Gracias por interesarte en el proyecto **1 a 1**! Esperamos que esta aplicación ayude a fortalecer tus relaciones personales y a mantener conexiones significativas con tus seres queridos.

# Nota

