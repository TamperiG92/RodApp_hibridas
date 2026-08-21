# RodApp_hibridas

## Resumen 

RodApp es una aplicación hibrida diseñada para motociclistas que buscan gestionar el mantenimiento preventivo de sus vehiculos, llevar el control centralizado de documentos legales (SOAT, tecno-mecanica, licencia) y planificar rodadas mediante la navegacion y alertas contextuales. Resolviendo la desorganizacion actual devido al uso de recordatorios manuales y mensajes dispersos.

## Pregunta guia
¿Cómo se puede optimizar el seguimiento de mantenimientos preventivos, la gestion documental y la coordinacion de rutas para motociclistas en Bogotá mediante una aplicacion hibrida desarrollada en Ionic?.

## Integrantes-Rol

- Diego Alejandro Cala Espitia - Fullstack & Mobile developer
- Cristian David Collazos Bocanegra - UI/UX & Frontend Developer
- Oscar Leonardo Andrade Diaz - QA & Backend developer

  ## Herramientas tecnologicas
  -Ionic framework 7.2.1
  -Angular 18.x.x
  -Node.js 24.14.0
  -npm 11.12.0
  -TypeSCript 7.0.2
  -Capacitor 6.x.x

  ## Instalacion y ejecucion local
1. Clonar repositorio 
-git clone https://github.com/TamperiG92/RodApp_hibridas.git
cd RodApp_hibridas

2.Instalar dependencias
- npm install
- npm install -g @ionic/cli
- npm install -g @angular/cli


3. Ejecutar modo de desarrollo
- Ionic serve

4. La aplicación se abrirá automáticamente en http://localhost:8100

5. Requisitos previos
- Node.js >= 18.x.x (LTS recomendado v24.14.0)
- npm >= 9.x.x (Recomendado v11.12.0) 
- Ionic CLI (npm install -g @ionic/cli)  
- Java JDK >= 17 (Ej. Liberica JDK 21)  
- Android Studio y Android SDK configurado   

rodapp-hibridas/
├── src/
│   ├── app/
│   │   ├── components/      # Componentes reutilizables UI
│   │   ├── pages/           # Vistas (Mantenimientos, Documentos, Rutas)
│   │   ├── services/        # Servicios de datos y lógica de negocio
│   │   ├── app.component.ts # Componente raíz
│   │   └── app.routes.ts    # Configuración de rutas
│   ├── assets/              # Imágenes, íconos y recursos estáticos
│   └── theme/               # Estilos globales y variables de Ionic
├── capacitor.config.ts      # Configuración para compilación nativa
├── ionic.config.json        # Configuración del proyecto Ionic
└── package.json             # Dependencias del proyecto

## Licencia 
Este proyecto está bajo la Licencia MIT - libre para uso académico e investigativo en la Fundación Universitaria Compensar
