# Guía de Despliegue e Instalación del Sistema[cite: 1]

## 1. Requisitos Previos del Servidor[cite: 1]
Para poner en marcha la aplicación e-commerce, se requiere disponer del siguiente entorno:[cite: 1]
* **Servidor Web:** Node.js v18.x o superior.[cite: 1]
* **Base de Datos:** PostgreSQL v15.0.[cite: 1]
* **Memoria RAM Mínima:** 2 GB RAM / 2 Cores CPU.[cite: 1]
* **Sistema Operativo:** Ubuntu Server 22.04 LTS (Recomendado).[cite: 1]

## 2. Procedimiento de Instalación Técnicamente Despachado[cite: 1]

### Paso 2.1: Obtención del Código Fuente[cite: 1]
El administrador del sistema debe clonar el repositorio remoto oficial desde la plataforma GitHub hacia el servidor de destino y navegar a la carpeta raíz del proyecto.[cite: 1]

### Paso 2.2: Instalación de Dependencias del Proyecto[cite: 1]
Se deben instalar los paquetes y dependencias requeridas mediante el gestor de paquetes del entorno Node.js, ejecutando la descarga automática descrita en el archivo de configuración.[cite: 1]

### Paso 2.3: Configuración de Variables de Entorno[cite: 1]
Crea un archivo llamado `.env` en la raíz del proyecto tomando como base el archivo `.env.example`, definiendo los parámetros de conexión:[cite: 1]
* Puerto de red del servicio (`PORT`)[cite: 1]
* Dirección de host de la base de datos (`DB_HOST`)[cite: 1]
* Puerto de base de datos (`DB_PORT`)[cite: 1]
* Usuario y clave de acceso a la base de datos (`DB_USER`, `DB_PASS`)[cite: 1]

### Paso 2.4: Puesta en Marcha del Servicio[cite: 1]
Iniciar el servicio web en modo de desarrollo o producción verificando en la consola que los puertos de enlace estén abiertos y escuchando peticiones.[cite: 1]