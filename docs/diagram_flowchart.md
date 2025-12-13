flowchart TD
    START([START]) --> A[1. Analiza wymagań]
    A --> B[2. Projekt design]
    B --> C[3. Implementacja]
    C --> D[4. Testy]
    D --> E{Testy ok?}
    
    E -- tak --> F[5. Wdrożenie]
    E -- nie --> G[Poprawki]
    
    G --> C
    F --> END([KONIEC])
