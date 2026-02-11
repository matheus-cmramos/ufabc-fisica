graph TD
    %% Estilização
    classDef bct fill:#f1f8e9,stroke:#558b2f,stroke-width:2px;
    classDef fisica fill:#e1f5fe,stroke:#01579b,stroke-width:2px;
    classDef limitada fill:#fff3e0,stroke:#ef6c00,stroke-width:2px;
    classDef livre fill:#f5f5f5,stroke:#9e9e9e,stroke-dasharray: 5 5;

    subgraph BCT [Bloco 1: Bacharelado em Ciência e Tecnologia - Início]
        Q1[Q1: B.Mat / B.Comp / ECN]:::bct --> Q2[Q2: FUV / GA / B.Epist]:::bct
        Q2 --> Q3[Q3: FDV / AL / B.Exp]:::bct
        Q3 --> Q4[Q4: EDO / Fen. Mecânicos]:::bct
        Q4 --> Q5[Q5: Fen. Térmicos / Fen. Eletromag]:::bct
        Q5 --> Q6[Q6: Física Quântica / Mec. Clássica I]:::bct
    end

    subgraph FIS [Bloco 2: Bacharelado em Física - Específica]
        Q6 --> Q7[Q7: CVT / Eletromag I / V. Complexas]:::fisica
        Q7 --> Q8[Q8: Mec. Quântica I / A. Fourier]:::fisica
        Q8 --> Q9[Q9: Mec. Quântica II / F. Exp IV]:::fisica
        Q9 --> Q10[Q10: Mec. Estatística I / Limitada]:::limitada
        Q10 --> Q11[Q11: Mec. Estatística II / TCC I]:::fisica
        Q11 --> Q12[Q12: TCC II / Livre / Formatura]:::fisica
    end

    %% Cliques para detalhes
    click Q4 "#fen-mec"
    click Q6 "#mec-1"
    click Q7 "#cvt"
    click Q9 "#mq2"
