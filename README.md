# 🛠️ Basic MCP Demo - Weather Tool

Este proyecto es un ejemplo básico de un servidor **MCP (Model Context Protocol)** implementado en Node.js. Define una herramienta simple para consultar información del clima de una ciudad utilizando la API pública de [Open-Meteo](https://open-meteo.com/).

## 📦 Características

- Servidor MCP compatible utilizando `@modelcontextprotocol/sdk`.
- Herramienta `fetch-weather` que permite consultar el clima de una ciudad.
- Ejemplo educativo, ideal para entender el flujo básico de MCP.
- Sin claves API privadas, solo usa servicios públicos gratuitos.

## 🚀 Requisitos

- [Node.js](https://nodejs.org/) (v18 o superior recomendado)
- Acceso a Internet para consultar las APIs públicas

## ⚙️ Instalación

1. Clona el repositorio:

   ```
   git clone https://github.com/itsPatH/basicMCP.git
   cd basicMCP
   ```

2. Instala las dependencias:
```
npm install
```
3. Ejecuta el servidor MCP:
```
npx ts-node main.ts   
```
Nota: Este servidor espera ser utilizado por un cliente MCP compatible (como Claude con soporte MCP habilitado). Si no tienes un cliente MCP, el servidor quedará esperando conexión.
## 🌐 Alternativa para Pruebas Locales (Opcional)
Puedes extender este proyecto para agregar un servidor HTTP local y probar la herramienta sin un cliente MCP. Ejemplo de esto disponible en la rama local-test.
## ⚠️ Advertencias
⚡ Este proyecto es solo para fines educativos.
⚡ No está pensado para entornos de producción.
⚡ Si amplías el proyecto, no subas archivos con claves privadas o información sensible.
## 📄 Licencia
Este proyecto está bajo la licencia MIT. Eres libre de usarlo, modificarlo o distribuirlo para aprendizaje.

## ✨ Créditos
- Documentación oficial de Model Context Protocol: https://github.com/modelcontextprotocol .
- Uso de APIs públicas de Open-Meteo.
