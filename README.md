# LenPT Core Patch

Repositorio base para pruebas, simulación y reutilización de fragmentos simbólicos en **LenPT** — un lenguaje experimental para IA distribuida y estructuras automatizadas.

Este repositorio define una colección inicial de parches (`.lenpt`) que contienen:

- ✅ Fragmentos con **tokens codificados**  
- 🚩 **Banderas de comportamiento** activables/desactivables  
- 🧬 **Identificadores únicos** para cada módulo  

---

## 🌐 Estructura del Proyecto

/lenpt
└── base.lenpt         
lenpt-parser/
├── parser/
│   ├── __init__.py
│   └── lenpt_parser.py      
├── tests/
│   └── test_parser.py      
├── LICENSE                 
├── pyproject.toml          
└── README.md               

---

## MIT License 

Copyright (c) 2025 Cristhiam Quiñonez

---

```Bash
python lenpt-parser/parser/lenpt_parser.py lenpt/base.lenpt
```
