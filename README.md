# Redactor de VSL — Alto Ticket

Skill de Claude Code para redactar guiones de **VSL (Video Sales Letters / videos de venta)** de alto ticket, siguiendo una estructura probada de 15 secciones, gatillos mentales, patrones hipnóticos de lenguaje, tácticas de venta y storytelling, en la voz del creador.

## Cómo funciona

1. Invoca la skill (`/redactor-vsl`) o pídele a Claude que cree un VSL.
2. Claude te devuelve una **plantilla de inputs** (oferta, precio, público, testimonios, tono, mecanismo único, garantía, urgencia…).
3. La llenas con la info de tu negocio y se la regresas.
4. Claude escribe el guión completo y lo entrega como documento **Word (.docx)**.

## Estructura

```
redactor-vsl/
├── SKILL.md                  # Orquestador del flujo y la metodología
├── assets/
│   └── plantilla-inputs.md   # Formato de inputs que llena el usuario
├── references/               # Metodología (estructura, tácticas, creencias, patrones, ejemplos)
└── scripts/
    └── build_docx.py         # Genera el .docx final (requiere python-docx)
```

## Requisitos

- Claude Code
- Python con `python-docx` (`pip install python-docx`) para la salida en .docx
