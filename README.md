# 🌌 Fluxograma Interativo: Bacharelado em Física (UFABC - PP 2023)

> **Perfil:** Físico Pesquisador (Trajetória sugerida conforme Quadro 9.2 do PPC).

### 🗺️ O Mapa de Navegação
*As matérias em **Ouro** são Limitadas "Fortemente Recomendadas". As em **Cinza** são Livres sugeridas.*

```mermaid
graph TD
    %% Estilização
    classDef essencial fill:#fff5e6,stroke:#ff9900,stroke-width:2px;
    classDef livre fill:#f9f9f9,stroke:#ccc,stroke-dasharray: 5 5;

    subgraph Q7 [7º Quadrimestre]
        MC1[Mecânica Clássica I]
        CVT[Cálculo Vetorial e Tensorial]
        EM1[Eletromagnetismo I]
    end

    subgraph Q8 [8º Quadrimestre]
        MC2[Mecânica Clássica II]
        EM2[Eletromagnetismo II]
        FQM[Física Quântica]
    end

    subgraph Q9 [9º Quadrimestre]
        MQ1[Mecânica Quântica I]
        FT[Fenômenos Térmicos]
        VC[Variáveis Complexas]:::essencial
    end

    subgraph Q10 [10º Quadrimestre]
        MQ2[Mecânica Quântica II]:::essencial
        FEst[Física Estatística]
        Livre1[Disciplina Livre]:::livre
    end

    %% Conexões Críticas
    MC1 --> MC2
    CVT --> EM1
    EM1 --> EM2
    FQM --> MQ1
    MQ1 --> MQ2
    VC -.-> MQ2

    %% Links para Detalhes
    click MC1 "#mc1"
    click CVT "#cvt"
    click VC "#vc"
    click Livre1 "#livres"
