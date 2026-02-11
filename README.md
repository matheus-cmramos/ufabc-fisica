<details> <summary><b>🔬 Perfil: Físico Pesquisador (Foco Acadêmico)</b></summary> <p align="center"><i>Baseado no Quadro 9.2 do PPC - Focado em rigor teórico para quem almeja pós-graduação.</i></p>
graph TD
    %% Estilos
    classDef bct fill:#f1f8e9,stroke:#558b2f,stroke-width:2px;
    classDef obrigatoria fill:#e1f5fe,stroke:#01579b,stroke-width:2px;
    classDef inter fill:#f3e5f5,stroke:#7b1fa2,stroke-width:2px;
    classDef livre fill:#fafafa,stroke:#9e9e9e,stroke-dasharray: 5 5;

    subgraph BCT_INT [Tronco Inicial BC&T]
        I1[Q1-Q3: Base Científica e Humanidades]:::bct --> I2[Q4-Q6: Transição para Física e Matemática]:::bct
    end

    subgraph FIS_INT [Bacharelado em Física Interdisciplinar]
        I2 --> Q7_I[Q7: Var. Complexas / Eletromag I / Fís. Exp III / Hum III]:::obrigatoria
        Q7_I --> Q8_I[Q8: Mec. Quântica I / Análise Fourier / Bioquímica]:::obrigatoria
        Q8_I --> Q9_I[Q9: Mec. Quântica II / Fís. Exp IV / Projeto Dirigido]:::obrigatoria
        Q9_I --> Q10_I[Q10: Opção Limitada ou Livre - Foco Interdisciplinar]:::inter
        Q10_I --> Q11_I[Q11: Opção Limitada ou Livre - Foco Interdisciplinar]:::inter
        Q11_I --> Q12_I[Q12: Opção Limitada ou Livre - Formatura]:::livre
    end
</details>
