<div align="center">

# 🪶 GENERADOR POÉTICO 🪶

```
     ██████╗ ███████╗███╗   ██╗███████╗██████╗  █████╗ ██████╗  ██████╗ ██████╗ 
    ██╔════╝ ██╔════╝████╗  ██║██╔════╝██╔══██╗██╔══██╗██╔══██╗██╔═══██╗██╔══██╗
    ██║  ███╗█████╗  ██╔██╗ ██║█████╗  ██████╔╝███████║██║  ██║██║   ██║██████╔╝
    ██║   ██║██╔══╝  ██║╚██╗██║██╔══╝  ██╔══██╗██╔══██║██║  ██║██║   ██║██╔══██╗
    ╚██████╔╝███████╗██║ ╚████║███████╗██║  ██║██║  ██║██████╔╝╚██████╔╝██║  ██║
     ╚═════╝ ╚══════╝╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═════╝  ╚═════╝ ╚═╝  ╚═╝
    ██████╗  ██████╗ ███████╗████████╗██╗ ██████╗ ██████╗                        
    ██╔══██╗██╔═══██╗██╔════╝╚══██╔══╝██║██╔════╝██╔═══██╗                       
    ██████╔╝██║   ██║█████╗     ██║   ██║██║     ██║   ██║                       
    ██╔═══╝ ██║   ██║██╔══╝     ██║   ██║██║     ██║   ██║                       
    ██║     ╚██████╔╝███████╗   ██║   ██║╚██████╗╚██████╔╝                       
    ╚═╝      ╚═════╝ ╚══════╝   ╚═╝   ╚═╝ ╚═════╝ ╚═════╝                        
```

### `[ poemas cuasi-ensayísticos vagamente lujuriosos ]`

[![Status](https://img.shields.io/badge/status-active-success.svg?style=for-the-badge)](https://medusahra.github.io/generador-poetico/)
[![GitHub Pages](https://img.shields.io/badge/deployed-github%20pages-blue.svg?style=for-the-badge&logo=github)](https://medusahra.github.io/generador-poetico/)
[![Algorithm](https://img.shields.io/badge/algorithm-markov%20chains-ff1493.svg?style=for-the-badge)](https://en.wikipedia.org/wiki/Markov_chain)
[![License](https://img.shields.io/badge/license-MIT-purple.svg?style=for-the-badge)](LICENSE)

**[🌐 DEMO EN VIVO](https://medusahra.github.io/generador-poetico/)** | **[📖 DOCUMENTACIÓN](#-cómo-funciona)** | **[🛠️ TECNOLOGÍA](#️-stack-tecnológico)**

---

</div>

## 🎭 ¿Qué es esto?

Un **generador algorítmico de poesía** que utiliza **cadenas de Markov** para crear poemas únicos basados en un corpus híbrido que combina:

- 📝 Textos propios originales
- 📚 Poesía de dominio público (Lorca, Vallejo, Storni, Neruda)
- 🧬 Algoritmos estocásticos de orden 2

El resultado: **constelaciones poéticas únicas** que emergen del cruce entre lo personal y lo universal, lo algorítmico y lo lírico.

---

## 🔮 Características
```ascii
┌─────────────────────────────────────────────────────────┐
│  [●] Generación algorítmica basada en Markov Chains    │
│  [●] Corpus de 2000+ palabras (propio + dominio público)│
│  [●] Interfaz cyberpunk/neón aesthetic                 │
│  [●] Sin dependencias externas (vanilla JS)            │
│  [●] Poemas de longitud variable (60-100 palabras)     │
│  [●] Formateo dinámico con saltos de línea aleatorios  │
│  [●] Función de copiado al portapapeles                │
│  [●] 100% client-side (sin backend, sin APIs)          │
└─────────────────────────────────────────────────────────┘
```

---

## 🧠 Cómo funciona

### Algoritmo de Cadenas de Markov
```javascript
// Orden 2: analiza secuencias de 2 palabras
buildMarkovChain(corpus, order = 2)

// Ejemplo:
"verde que te quiero verde" 
→ ["verde que"] → ["te"]
→ ["que te"] → ["quiero"]
→ ["te quiero"] → ["verde"]
```

**El proceso:**

1. **Análisis del corpus**: Tokeniza el texto y crea un mapa de transiciones
2. **Construcción de cadenas**: Por cada par de palabras, registra qué palabra puede seguir
3. **Generación estocástica**: Camina aleatoriamente por las cadenas para crear nuevo texto
4. **Formateo poético**: Aplica saltos de línea y espaciado según probabilidades

---

## 🛠️ Stack Tecnológico
```
┌──────────────────────────────────────┐
│  FRONTEND                             │
├──────────────────────────────────────┤
│  • HTML5 (inline)                    │
│  • CSS3 (neón/cyberpunk aesthetic)   │
│  • JavaScript ES6 (vanilla)          │
│                                      │
│  ALGORITMO                           │
├──────────────────────────────────────┤
│  • Markov Chains (orden 2)           │
│  • Generación estocástica            │
│  • Formateo dinámico de texto        │
│                                      │
│  DEPLOYMENT                          │
├──────────────────────────────────────┤
│  • GitHub Pages                      │
│  • Git version control               │
└──────────────────────────────────────┘
```

---

## 🚀 Instalación y Uso

### Opción 1: Usar la versión online
Simplemente visita: **[medusahra.github.io/generador-poetico](https://medusahra.github.io/generador-poetico/)**

### Opción 2: Clonar y ejecutar localmente
```bash
# Clonar el repositorio
git clone https://github.com/medusahra/generador-poetico.git

# Entrar al directorio
cd generador-poetico

# Abrir en el navegador
firefox index.html  # o tu navegador preferido
```

No requiere instalación de dependencias. Es 100% estático.

---

## 💀 Proceso de Creación
```ascii
[FASE 1: CORPUS] → [FASE 2: ALGORITMO] → [FASE 3: INTERFAZ] → [FASE 4: DEPLOY]
     │                    │                      │                    │
     │                    │                      │                    │
     ├─ Selección        ├─ Implementación      ├─ Diseño          ├─ GitHub Pages
     │  de textos        │  Markov Chains       │  cyberpunk        │  
     │                   │                      │                   │
     ├─ Limpieza         ├─ Tokenización        ├─ Animaciones     ├─ CI/CD
     │  y curación       │  y análisis          │  CSS              │
     │                   │                      │                   │
     └─ Corpus híbrido   └─ Generación          └─ UX/UI           └─ Live deployment
        (propio +           estocástica            minimalista
         dom. público)
```

### Timeline del desarrollo:
```
[====================] 100%

├─ [████░░░░░░░░░░░░░░] Selección y curación del corpus
├─ [████████░░░░░░░░░░] Implementación algoritmo Markov
├─ [████████████░░░░░░] Diseño de interfaz cyberpunk
├─ [████████████████░░] Testing y refinamiento
└─ [████████████████████] Deploy en GitHub Pages
```

---

## 🎨 Estética y Filosofía

El diseño visual adopta una **estética cyberpunk/neón** que dialoga con:

- 💀 La muerte del autor (Barthes)
- 🤖 La escritura posthumana
- 🌐 La poesía como código ejecutable
- ✨ Lo algorítmico como gesto creativo

**Paleta de colores:**
```css
--neon-pink: #ff1493;
--cyber-black: #000000;
--matrix-green: #00ff00;
--glow-effect: 0 0 20px rgba(255, 20, 147, 0.8);
```

---

## 📊 Corpus Stats
```
Total de palabras:     ~2000+
Poetas incluidos:      5 (Lorca, Vallejo, Storni, Neruda + propio)
Orden de Markov:       2
Longitud de poemas:    60-100 palabras
Versos por poema:      Variable (algoritmo estocástico)
```

---

## 🔧 Roadmap Futuro

- [ ] Agregar selector de corpus (romántico, existencial, surrealista)
- [ ] Implementar "semilla temática" funcional (actualmente decorativo)
- [ ] Exportar poemas como imagen (canvas + SVG)
- [ ] Añadir más poetas al corpus
- [ ] Modo "colaborativo" (combinar textos del usuario)
- [ ] API pública para integración externa

---

## 🤝 Contribuciones

¿Quieres agregar poetas al corpus o mejorar el algoritmo? 
```bash
# Fork el repo
# Crea una rama
git checkout -b feature/nuevo-corpus

# Haz tus cambios
# Commit
git commit -m "Add: Poeta X al corpus"

# Push y crea PR
git push origin feature/nuevo-corpus
```

---

## 📜 Licencia

MIT License - Siéntete libre de usar, modificar y distribuir.

---

## 👤 Autor

**medusahra**

- GitHub: [@medusahra](https://github.com/medusahra)
- Portfolio: [medusahra.github.io](https://medusahra.github.io)

---

<div align="center">

### `[ fin de transmisión ]`
```
     ╔═══════════════════════════════════════╗
     ║  Hecho con 🖤 y algoritmos en Debian  ║
     ║  Trixie + Konsole + JavaScript ES6   ║
     ╚═══════════════════════════════════════╝
```

**[⬆ volver arriba](#-generador-poético-)**

</div>
EOF

# Agrega el README al repo
git add README.md
git commit -m "Add: README épico con estética hacker"
git push origin main
