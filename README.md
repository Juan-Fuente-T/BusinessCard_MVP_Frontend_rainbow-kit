# SNC: Identidad Profesional Soberana (ERC-721)

**Smart Network Card (SNC)** es una DApp de identidad descentralizada. Permite compartir datos sensibles (email, teléfono) **exclusivamente** con wallets autorizadas on-chain, garantizando privacidad criptográfica. Funciona como una red profesional en la que el usuario mantiene el control total de sus datos.

## 📸 Interfaz de Usuario
![Card_dashboard](/public/SNC_Dashboard.webp)

<div align="center">
  <img src="/public/SNC_Card2.webp" width="40%" alt="Dashboard de Usuario" />
  &nbsp;
  <img src="/public/SNC_Visor2.webp" width="50%" alt="Visor de Perfil" />
</div>

---

## 💡 Características Clave
NFT Interactivo: Un token no fungible que sirve como identidad del perfil, permitiendo a los usuarios compartir datos de forma selectiva y segura.

Gestión Segura de Contactos: La información privada solo es accesible a través de transacciones en la red, garantizando un alto nivel de privacidad y privacidad.

Front-end intuitivo: Una interfaz de usuario limpia y funcional que permite la interacción con la blockchain sin fricciones.

---

## ⚡ Ingeniería de Contratos & Seguridad

La prioridad en este proyecto fue la seguridad del Smart Contract y la inmutabilidad de los datos.

### 🔒 Privacidad Condicional (Token Gating)
El contrato implementa lógica de control de acceso on-chain. Solo las direcciones que poseen el NFT "Llave" o han sido whitelisteadas pueden desencriptar/acceder a los metadatos de contacto alojados en IPFS.

### 🧪 Testing Avanzado con Foundry
A diferencia de entornos JS (Hardhat), se utilizó **Foundry** para realizar tests unitarios y fuzzing directamente en Solidity, asegurando que no existan vulnerabilidades críticas antes del despliegue.

---

## ⚙️ Tecnologías y Stack
#### Frontend:

* **React**: Biblioteca para el desarrollo de la interfaz de usuario.

* **TypeScript**: Garantiza la solidez del código y la detección de errores en tiempo de desarrollo.

* **Tailwind CSS**: Framework de CSS para un diseño ágil y escalable.

* **RainbowKit**: Para la integración y gestión de multiples billeteras de criptomonedas.

* **Ethers.js**: Biblioteca para interactuar con los smart contracts en la red Ethereum.

* **Wagmi**: Colección de hooks y herramientas para trabajar con wallets y contratos en aplicaciones React.
  
* **Viem**: Librería que proporciona una API simple y robusta para interactuar con la blockchain.

#### Blockchain:

* **Solidity**: Lenguaje de programación para los smart contracts.

* **Foundry**: Herramienta para el desarrollo, prueba y despliegue de los contratos inteligentes.

#### Almacenamiento Descentralizado:

* **IPFS**: Para el almacenamiento de metadatos de los NFTs, garantizando la persistencia y descentralización

---
  
### 🎥 Demo del Funcionamiento
> ⚠️ Al requerir Wallet (Metamask) y red de pruebas de Arbitrum, se recomienda ver el flujo aquí:

[![Ver Video Demo](https://img.youtube.com/vi/dCy7JaMCcXg/0.jpg)](https://youtu.be/dCy7JaMCcXg)

## 🤝 Contribuciones y Contacto
Este proyecto es una prueba de concepto personal para demostrar mis habilidades en el desarrollo de aplicaciones blockchain. Si tienes interés en mi perfil o en este tipo de soluciones, no dudes en contactarme.

---

<p align="center">
  <a href="https://juanfuente.ovh">🌐 Portfolio: juanfuente.ovh</a> | <a href="https://www.linkedin.com/in/juan-fuente-dev/">👔 LinkedIn</a> 
</p>

