<h1 align="center">Emanuel Bertorello</h1>

<p align="center">
  Desarrollador <b>Full Stack</b> · Rosario, Argentina<br>
  <sub>Construyo productos que la gente usa todos los días para trabajar.</sub><br>
  <sub>Español nativo · Inglés avanzado</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/emanuel-bertorello-84a425219">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:emanuel.berto19@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

### Sobre mí

Hago el producto entero: la interfaz, la API, la base de datos, el deploy y
el equipo que está en la planta leyendo un indicador de peso por Modbus.

Me interesa el software que resuelve un problema concreto y medible. Escribo
código pensando en quien lo va a leer dentro de seis meses.

---

### En qué estoy

**Pesar RED** — plataforma de gestión de básculas de camiones, de punta a punta.

Un camión llega a la planta, se identifica con un QR, la balanza toma el peso
sola y el sistema hace el resto: emite el ticket, descuenta el stock y le
imputa el consumo a la cuenta corriente del cliente. Reemplaza planillas de
papel que se pierden y cierres de stock que se cruzan a mano.

Son tres piezas que tuve que resolver enteras:

| | |
|---|---|
| **Tótem** | Python + PySide6 en la balanza. Habla Modbus con el indicador de peso, dispara cámaras IP, imprime tickets y guarda todo local para que un corte de internet no frene al camión. |
| **Backend** | TypeScript sobre AWS Lambda (SAM), PostgreSQL en RDS. Emisión de QR, cierre de pesadas idempotente, stock, cuentas corrientes y facturación mensual automática. |
| **Portal** | Angular con un portal para cada uno que entra: el dueño de la balanza, la empresa cliente, el chofer y la administración. Monitoreo en vivo del peso, los semáforos y las cámaras. |

Alrededor de eso, lo que hace falta para operarlo sin viajar a cada planta:

- **Actualización remota** de los tótems, con paquetes firmados y asignación por balanza.
- **Demostraciones con balanza virtual**: un simulador que usa las mismas rutas que un tótem real, para mostrar el circuito completo sin instalar nada.
- **Funcionamiento sin internet**: el tótem valida pases y guarda las pesadas localmente, y las sincroniza cuando vuelve la conexión.

---

### Con qué trabajo

**Front** &nbsp;
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Back** &nbsp;
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Infra** &nbsp;
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---


<div align="center">
  <img height="165" src="https://streak-stats.demolab.com/?user=EmanuelBertorello&locale=es&hide_border=true&ring=003E4D&fire=E5A400&currStreakLabel=003E4D&sideLabels=003E4D&dates=6b7280" alt="Contribuciones totales y rachas">
</div>
