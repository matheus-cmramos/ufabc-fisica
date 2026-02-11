<details open>
<summary><b>🔬 Perfil: Físico Pesquisador (Foco Acadêmico)</b></summary>
<p align="center"><i>Baseado no Quadro 9.2 do PPC - Focado em rigor teórico para pós-graduação.</i></p>

```mermaid
graph TD
    %% Estilos de Cores
    classDef bct fill:#f1f8e9,stroke:#558b2f,stroke-width:2px;
    classDef obrigatoria fill:#e1f5fe,stroke:#01579b,stroke-width:2px;
    classDef limitada fill:#fff3e0,stroke:#ef6c00,stroke-width:2px;
    classDef livre fill:#fafafa,stroke:#9e9e9e,stroke-dasharray: 5 5;

    subgraph BCT [Ciclo Inicial: Bacharelado em Ciência e Tecnologia]
        Q1[Q1: B.Mat, B.Comp, B.Exp, Est. Mat]:::bct --> Q2[Q2: FUV, GA, B.Epist, Evol. Vida]:::bct
        Q2 --> Q3[Q3: FDV, AL, Proc. Info, Transf. Quím]:::bct
        Q3 --> Q4[Q4: EDO, Fen. Mecânicos, Prob. Est, Ópt. Relat]:::bct
        Q4 --> Q5[Q5: Fen. Térmicos, Fen. Eletromag, Fís. Quântica, Fís. Exp I]:::bct
        Q5 --> Q6[Q6: Mec. Clássica I, C. Vetorial, Fís. Exp II, Hum II]:::bct
    end

    subgraph FISICA [Ciclo Específico: Bacharelado em Física]
        Q6 --> Q7[Q7: Eletromag I, Var. Complexas, Mec. Clássica II, Fís. Exp III]:::obrigatoria
        Q7 --> Q8[Q8: Mec. Quântica I, Eletromag II, Análise Fourier]:::obrigatoria
        Q8 --> Q9[Q9: Mec. Quântica II, Fís. Exp IV, Mec. Clássica III, Eletromag III]:::obrigatoria
        Q9 --> Q10[Q10: Mec. Estatística I, Mec. Quântica III, Limitada]:::limitada
        Q10 --> Q11[Q11: Mec. Estatística II, Mec. Quântica IV, Limitada]:::limitada
        Q11 --> Q12[Q12: Opção Limitada ou Livre]:::livre
    end

    %% Cliques para detalhes
    click Q4 "#fen-mec" "Detalhes de Fen. Mecânicos"
    click Q6 "#mc1" "Detalhes de Mec. Clássica I"
    click Q7 "#vc" "Detalhes de Var. Complexas"

</details><details> <summary><b>💼 Perfil: Físico Interdisciplinar (Foco Mercado/Aplicada)</b></summary> <p align="center"><i>Baseado no Quadro 9.1 do PPC - Conexões com Economia, Finanças e Tecnologia.</i></p>

</details> ```
