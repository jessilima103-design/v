# Simulador Web de Abastecimiento, Precios y Consumo Familiar en Contextos de Crisis

[cite_start]Este proyecto consiste en una aplicación web interactiva de carácter educativo e informático diseñada para representar, calcular y visualizar el impacto de variables socioeconómicas y logísticas críticas del contexto nacional actual mediante modelos matemáticos sencillos[cite: 5, 22]. [cite_start]La herramienta tiene la finalidad de servir como un recurso de concientización y análisis para la toma de decisiones financieras en el hogar y la comunidad, manteniendo un enfoque neutral y fundamentado en datos cuantitativos[cite: 6].

## 📁 Organización de la Estructura de Carpetas
[cite_start]El árbol de directorios ha sido estructurado respetando fielmente la distribución física de los archivos del proyecto, organizando los archivos HTML principales en la raíz y agrupando ordenadamente los recursos de estilos, scripts e imágenes[cite: 16, 162, 164]:

```text
proyecto-web-crisis/
│
├── index.html          # Portal de acceso central y enrutamiento (Dashboard general)
├── index_abas.html     # Módulo interactivo: Simulador de Precios de Alimentos (Escenario B)
├── indexfami.html      # Módulo interactivo: Simulador de Costo de Transporte (Escenario C)
├── indexsum.html       # Módulo interactivo: Simulador de Compras Familiares (Escenario D)
│
├── css/                # Directorio de Hojas de Estilo Externas
│   ├── estilos.css     # Estilos base del portal de acceso principal
│   ├── estilos1.css    # Diseño y paleta de colores para el Escenario B
│   ├── estilos2.css    # Diseño y paleta de colores para el Escenario C
│   └── estilos3.css    # Diseño y paleta de colores para el Escenario D
│
├── js/                 # Directorio de Lógica de JavaScript Externo
│   ├── script.js       # Captura de datos, validación y cálculos del Escenario B
│   ├── script2.js      # Captura de datos, validación y cálculos del Escenario C
│   └── script3.js      # Captura de datos, validación y cálculos del Escenario D
│
├── img/                # Directorio de Recursos Gráficos e Ilustraciones
│   ├── alimentos.png   # Imagen descriptiva para el simulador de precios
│   ├── transporte.png  # Imagen descriptiva para el simulador de logística
│   └── presupuesto.png # Imagen descriptiva para el simulador familiar
│
└── README.md           # Documentación técnica e institucional del proyecto