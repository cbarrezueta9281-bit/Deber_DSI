# README-PROYECTO

## Datos
- Nombre: sistema-gestion-rescate-adopcion
- URL: https://github.com/cbarrezueta9281-bit/sistema-gestion-rescate-adopcion
- Usuario: cbarrezueta9281-bit

## Estructura
/sistema-gestion-rescate-adopcion
├── README.md
├── readme-proyecto.md
├── analisis-requerimiento.md
├── docs/
│   ├── Figura1.png (Casos de Uso)
│   ├── Figura2.png (Clases)
│   └── Figura3.png (Secuencia)
└── src/
    ├── dominio/ (ExpedienteAnimal, Usuario, FabricaExpediente - Factory)
    ├── aplicacion/ (ServicioAvisos - Observer, EstrategiaPriorizacion - Strategy)
    ├── infraestructura/
    └── presentacion/ (MVC)

## Patrones
- Factory Method: crear expediente por especie (Perro, Gato, Fauna Silvestre)
- Observer: notificar cambios de estado
- Strategy: priorización por riesgo, especie, ubicación
- MVC: separación Modelo-Vista-Controlador
