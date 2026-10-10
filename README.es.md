# 🏆 Pitch-Win (Español)

> **Skill de Código Abierto para Agentes de IA: Diseña Pitches Ganadores de 3 Minutos para Hackatones**  
> *Compatible con Antigravity, Claude Code, Cursor, OpenCode, Codex y Windsurf.*

[![Licencia: MIT](https://img.shields.io/badge/Licencia-MIT-emerald.svg)](https://opensource.org/licenses/MIT)
[![Tiempo Calibrado](https://img.shields.io/badge/Duraci%C3%B3n-3:00_Min_(~400_palabras)-blue.svg)]()

---

## 🎯 ¿Qué es Pitch-Win?

**Pitch-Win** es una skill especializada para agentes de inteligencia artificial que convierte cualquier prototipo, desarrollo de software o proyecto de innovación en un **pitch de 3 minutos diseñado específicamente para convencer al jurado y ganar hackatones**.

### Pilares Fundamentales:
- ⏱️ **Matemática Estricta de 3 Minutos**: Presupuesto cerrado de **390 a 420 palabras** (~130–140 palabras por minuto) para memorizar con calma y no ser cortado por el cronómetro.
- 🎭 **Indicaciones Escénicas Línea por Línea**: Debajo de cada frase se detallan indicaciones de `[Tono & Intención]`, `[Mirada]`, `[Manos & Gestos]`, `[Movimiento]` y `[Pausa]`.
- 🫁 **Protocolo Pre-Pitch (Respiración 4-6-8)**: Ejercicios de respiración diafragmática para anular el temblor de voz por adrenalina, postura de resonancia en pecho y reglas acústicas para el uso del micrófono.
- 📊 **Anclaje Territorial y Datos**: Integra prioridades de planes de innovación (como el PDE Piura Innovadora / AEIs) y validación empírica.
- 🖥️ **Entregable HTML Minimalista**: Genera un archivo `.html` limpio con fondo blanco, letras oscuras, cronómetro interactivo de ensayo y un slide canvas de 5 láminas.

---

## ⚡ Instalación Rápida (1 Solo Comando)

### En Windows (PowerShell)
```powershell
irm https://raw.githubusercontent.com/luisfelix122/pitch-win/main/install.ps1 | iex
```

### En Linux / macOS / WSL (Bash)
```bash
curl -fsSL https://raw.githubusercontent.com/luisfelix122/pitch-win/main/install.sh | bash
```

### Universal con NPX (Cualquier Sistema Operativo)
```bash
npx degit luisfelix122/pitch-win .agents/skills/pitch-win
```

*Nota: Si lo ejecutas dentro de la carpeta de un proyecto, se instala localmente en `.agents/skills/pitch-win`. Si lo ejecutas en tu carpeta de usuario, queda disponible de forma global en `~/.agents/skills/pitch-win`.*

---

## 🤖 ¿Cómo se usa con tu Agente de IA?

No necesitas configurar nada a mano. Una vez instalada la skill:

1. **Pídeselo directamente en el chat a tu IA**:
   > *"Usa la skill pitch-win para armar el pitch de mi proyecto [Nombre]. El problema es [X] y la solución es [Y]."*

2. **O pídele a la IA que se la instale sola**:
   > *"Descarga e instala la skill pitch-win desde https://github.com/luisfelix122/pitch-win en mi carpeta `.agents/skills/pitch-win`."*

Gracias al principio de **Progressive Disclosure**, la IA solo cargará los archivos que necesite (por ejemplo, las técnicas vocales o las pautas de diseño) sin saturar la ventana de contexto.

---

## 📄 Licencia
MIT © 2026 [Luis Félix](https://github.com/luisfelix122). Código abierto y libre para la comunidad de desarrolladores y emprendedores.
