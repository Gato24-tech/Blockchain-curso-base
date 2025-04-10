# 🚀 Plantilla Base para Proyectos del Curso de Blockchain
“Repositorio base con configuración lista para usar con Hardhat, Solidity y pruebas locales o en red testnet.”


Este repositorio sirve como punto de partida para cualquier proyecto del curso. Aquí se documenta la configuración estándar, herramientas y progresos.

---

## 🧪 Estado actual del curso

📍 **Módulo en curso:** Seguridad avanzada de contratos inteligentes  
🔁 **Fase actual:** Implementando URI dinámica y funciones de pausa en ERC-721  
📦 **Último contrato base trabajado:** `MyNFT.sol` (ERC-721 con mejoras de seguridad)  
🧠 **Frase clave de recuperación:** `curso blockchain`

---

## ⚙️ Configuración técnica base

| Elemento            | Valor                        |
|---------------------|------------------------------|
| **Solidity**        | `^0.8.28`                    |
| **Hardhat**         | `2.22.x`                     |
| **Node.js**         | `>=18.x`                     |
| **Librerías clave** | `OpenZeppelin 4.x`, `dotenv` |
| **Frontend**        | Vanilla HTML o React opcional|

---

## 📁 Estructura de carpetas recomendada
.
├── contracts/             # Contratos .sol
├── scripts/               # Scripts de deploy e interacción
├── test/                  # Tests con Hardhat/Chai
├── deployments/           # Dirección del contrato desplegado (JSON)
├── .env                   # Variables sensibles (IGNORADO)
├── hardhat.config.cjs     # Configuración principal
├── README.md              # Este archivo


