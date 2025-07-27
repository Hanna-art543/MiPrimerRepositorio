flowchart TD
    A[Iniciar Proyecto] --> B{¿Proyecto individual o grupal?}
    B -- Individual --> C[Asignar tareas]
    B -- Grupal --> D[Formar grupos]

    D --> E{¿Grupos por tema o por habilidad?}
    E -- Por tema --> F[Distribuir módulos del proyecto]
    E -- Por habilidad --> G[Asignar tareas según fortalezas]

    F --> H[Establecer cronograma]
    G --> H

    H --> I{¿Seguimiento semanal?}
    I -- Sí --> J[Revisar avances y dar feedback]
    I -- No --> K[Revisión final al terminar]

    J --> L[Entregar proyecto]
    K --> L
    C --> L

    L --> M[Fin del Proyecto]