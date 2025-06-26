# Proyecto---Blockydocs
Certificación y verificación de documentos con blockchain mediante una app web y móvil.

# BLOCKYDOCS – Certificación de Documentos con Blockchain

**BLOCKYDOCS** es una aplicación web y móvil para la certificación de documentos mediante tecnología blockchain. Permite a los usuarios subir archivos, generar su hash, firmarlos con MetaMask y almacenarlos en la red Ethereum como comprobante de autenticidad.

---

## Características Principales

- Certificación de documentos mediante firma digital en blockchain.
- Verificación de documentos por hash SHA-256.
- Interfaz web desarrollada en React.js.
- Aplicación móvil desarrollada en React Native.
- Backend en PHP y base de datos MySQL.
- Integración con MetaMask (web y móvil).
- Smart contracts en Solidity desplegados en red Ethereum (Ganache/Testnet).

---

## Requisitos Generales

- Node.js v16 o superior
- XAMPP (Apache + MySQL)
- Visual Studio Code
- MetaMask (navegador o móvil)
- Ganache o Remix IDE

---

## Instalación de la Aplicación Web

1. Ir al directorio `web/`:
    ```bash
    cd web
    ```

2. Instalar dependencias:
    ```bash
    npm install
    ```

3. Configurar el archivo `.env`:
    ```env
    REACT_APP_API_URL=http://localhost/blockydocs-backend/api/
    REACT_APP_CONTRACT_ADDRESS=0x123456789...
    REACT_APP_BLOCKCHAIN_NETWORK=ganache
    ```

4. Iniciar la aplicación:
    ```bash
    npm start
    ```

---

## Instalación de la Aplicación Móvil

1. Ir al directorio `mobile/`:
    ```bash
    cd mobile
    ```

2. Instalar dependencias:
    ```bash
    npm install
    ```

3. Configurar el archivo `.env`:
    ```env
    API_URL=http://localhost/blockydocs-backend/api/
    CONTRACT_ADDRESS=0x123456789...
    NETWORK=ganache
    ```

4. Ejecutar la aplicación:
    ```bash
    npx react-native run-android
    ```

---

## Instalación del Backend

1. Colocar la carpeta `backend/` en:
    ```
    C:\\xampp\\htdocs\\blockydocs-backend\\
    ```

2. Activar Apache y MySQL desde el panel de XAMPP.

3. Crear la base de datos importando el archivo SQL (`blockydocs_db.sql`) desde phpMyAdmin.

---

## Licencia

Este proyecto fue desarrollado como MVP educativo. Puedes usarlo y modificarlo libremente.

---

## Autor

Proyecto desarrollado por el equipo de BLOCKYDOCS.
"""

