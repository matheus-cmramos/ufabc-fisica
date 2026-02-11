# 🌌 Fluxograma Interativo: BC&T -> Física

Este guia visual ajuda estudantes a navegarem pelas disciplinas obrigatórias e recomendações para o Bacharelado em Física (PPC 2023)

### 🗺️ O Fluxo
*Clique em uma disciplina para ver os detalhes abaixo.*

```mermaid
graph TD
    %% Trilhas
    subgraph "Base Comum (BC&T)"
        FE[Base Experimental] --> FM[Fenômenos Mecânicos]
        FUV[Funções de Uma Variável] --> FDV[Funções de Diversas Variáveis]
        FUV --> FM
        GA[Geometria Analítica] --> AL[Álgebra Linear]
    end

    subgraph "Caminho da Física"
        FM --> MC1[Mecânica Clássica I]
        FDV --> EDO[EDOs]
        EDO --> MC1
        CVT[Cálculo Vetorial e Tensorial] --> MC1
    end

    %% Links de Âncora
    click FUV "#fuv" "Ver detalhes de FUV"
    click FM "#fm" "Ver detalhes de Fenômenos Mecânicos"
    click MC1 "#mc1" "Ver detalhes de Mecânica Clássica I"
    click CVT "#cvt" "Ver detalhes de Vetorial e Tensorial"
