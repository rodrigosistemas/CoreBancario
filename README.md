# 💻 Core Bancario en Java SE 21

## Descripción
Es un sistema desarrollado en Java 21 que ejecuta un núcleo bancario básico a través de la terminal.
Este proyecto está diseñado para gestionar de manera eficiente diferentes tipos de cuentas bancarias,
realizar transacciones financieras y generar reportes detallados de las operaciones realizadas. 
Utiliza principios de Programación Orientada a Objetos (POO) para garantizar una arquitectura limpia y escalable.

---

## ✨ Características

### 🏦 Gestión de Cuentas Bancarias
- **Cuentas de Ahorro**: Tipo básico de cuenta sin generación de intereses, permite depósitos y retiros de forma sencilla.
- **Cuentas de Depósito a Plazo**: Ofrecen tasas de interés fijas durante un período específico.
- **Cuenta Sueldo**: Diseñada para recibir depósitos de nómina y gestionar gastos diarios.

### 💸 Transacciones Financieras
- **Depósitos**: Añadir fondos a cualquier tipo de cuenta.
- **Retiros**: Retirar fondos, con validación de saldo suficiente.
- **Transferencias**: Transferir fondos entre diferentes cuentas dentro del sistema.

### 📊 Generación de Reportes
- **Reportes de Transacciones**: Muestra un historial detallado de las transacciones realizadas.
- **Resumen de Cuentas**: Proporciona un resumen consolidado de cada cuenta, incluyendo saldos y movimientos recientes.

---

## 📋 Requisitos
- **Java 21**: Asegúrate de tener instalada la versión 21 de Java en tu sistema.
- **Sistema Operativo**: Compatible con Windows, macOS y Linux.
- **Terminal**: El sistema se ejecuta desde la línea de comandos.

---

## ⚙️ Instalación
1. Clonar el Repositorio:
```bash
git clone https://github.com/tu-usuario/core-bancario.git
```
2. Navegar al Directorio del Proyecto:
```bash
cd core-bancario
```
3. Compilar el Proyecto: 
```bash
javac -d bin src/**/*.java
```
4. Ejecutar la Aplicación:
```bash
java -cp bin Main
```

---

## 🚀 Utilización
Una vez ejecutada la aplicación, se presentará un menú interactivo en la terminal con las siguientes opciones:

1. Crear Cuenta: Permite crear una nueva cuenta bancaria seleccionando el tipo deseado.
2. Realizar Depósito: Añade fondos a una cuenta existente.
3. Realizar Retiro: Retira fondos de una cuenta, verificando que el saldo sea suficiente.
4. Realizar Transferencia: Transfiere fondos entre dos cuentas dentro del sistema.
5. Generar Reporte de Transacciones: Muestra un historial de todas las operaciones realizadas.
6. Salir: Cierra la aplicación.

---

## 🤝 Contribuciones
Las contribuciones son bienvenidas. Si deseas mejorar el sistema, agrega nuevas funcionalidades o corregir errores, siéntete libre de hacer un fork del repositorio y abrir un pull request.

---

## 📄 Licencia
Este proyecto está licenciado bajo la MIT License.

---

### Desarrollado con 💙 en Java 21
