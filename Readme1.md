# 🚀 Plantilla Base para Proyectos del Curso de Blockchain

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


---

## 🧩 Extensiones recomendadas para VSCode

- Solidity (Juan Blanco)
- Prettier
- GitLens
- DotENV
- Error Lens

---

## 📦 Comandos útiles

```bash
npm install             # Instalar dependencias
npx hardhat compile     # Compilar contrato
npx hardhat node        # Levantar red local
npx hardhat run scripts/deploy.js --network localhost
npx hardhat console     # Consola interactiva
npx hardhat test        # Ejecutar pruebas

node_modules/
.env
artifacts/
cache/
deployments/
