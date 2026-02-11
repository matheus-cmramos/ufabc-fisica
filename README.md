# 🌌 Fluxograma Interativo: Física UFABC (PP 2023)

Este guia visual organiza a trajetória completa desde o ingresso no BC&T até a conclusão do Bacharelado em Física, otimizado para as regras do catálogo de 2023.

---

## 🧭 Escolha sua Trajetória
*Clique nas abas abaixo para alternar entre as sugestões de percurso.*

<details>
<summary><b>🔬 Perfil: Físico Pesquisador (Foco Académico/Pós-Graduação)</b></summary>
<p align="center"><i>Baseado no Quadro 9.2 do PPC - Focado em rigor teórico e preparação para mestrado/doutorado.</i></p>

```mermaid
graph TD
    %% Estilos de Cores
    classDef bct fill:#f1f8e9,stroke:#558b2f,stroke-width:2px;
    classDef obrigatoria fill:#e1f5fe,stroke:#01579b,stroke-width:2px;
    classDef limitada fill:#fff3e0,stroke:#ef6c00,stroke-width:2px;
    classDef livre fill:#fafafa,stroke:#9e9e9e,stroke-dasharray: 5 5;

    subgraph "Anos 1 e 2: O Tronco BC&T"
        Q1[Q1: B.Mat, B.Comp, ECN]:::bct --> Q2[Q2: FUV, GA, B.Epist]:::bct
        Q2 --> Q3[Q3: FDV, AL, B.Exp]:::bct
        Q3 --> Q4[Q4: EDO, FM, Est.Mat]:::bct
        Q4 --> Q5[Q5: FT, EM, Trans.Cal]:::bct
        Q5 --> Q6[Q6: Q.Exp, C.Comp, Hum]:::bct
    end

    subgraph "Ano 3: Transição e Mecânica Analítica"
        Q6 --> Q7[Q7: Mec. Clássica I, EM I, C. Vetorial]:::obrigatoria
        Q7 --> Q8[Q8: Mec. Clássica II, EM II, F. Quântica]:::obrigatoria
        Q8 --> Q9[Q9: Mec. Quântica I, F. Térmicos, V. Complexas]:::obrigatoria
    end

    subgraph "Ano 4: Especialização Teórica"
        Q9 --> Q10[Q10: Mec. Quântica II, F. Estatística]:::limitada
        Q10 --> Q11[Q11: Trab. Graduação I, Física Exp. V]:::obrigatoria
        Q11 --> Q12[Q12: Trab. Graduação II, Livre]:::obrigatoria
    end

    %% Destaques do Perfil
    VC[Variáveis Complexas]:::limitada
    MQ2[Mecânica Quântica II]:::limitada
    click Q7 "#mc1"
    click Q9 "#vc"
