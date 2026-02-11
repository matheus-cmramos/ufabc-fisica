graph TB
  classDef bct fill:#e1f5fe,stroke:#01579b;
  classDef fis fill:#fff9c4,stroke:#f57f17;
  classDef exp fill:#ffe0b2,stroke:#e65100;
  classDef math fill:#e8f5e9,stroke:#1b5e20;
  classDef hum fill:#f3e5f5,stroke:#4a148c;

  subgraph "1º Quadrimestre"
    BCS0001[BCS0001-15<br>Base Exp. Ciências]:::exp
    BIK0102[BIK0102-15<br>Estrutura da Matéria]:::bct
    BIS0003[BIS0003-15<br>Bases Matemáticas]:::math
    BIL0304[BIL0304-15<br>Evolução/Vida]:::bct
    BIS0005[BIS0005-15<br>Bases Computacionais]:::bct
    HUM1[Humanidade 1]:::hum
  end

  subgraph "2º Quadrimestre"
    BCM0504[BCM0504-15<br>Natureza da Informação]:::bct
    BCJ0204[BCJ0204-15<br>Fen. Mecânicos]:::bct
    BCN0402[BCN0402-15<br>Funções 1 Var]:::math
    BCN0404[BCN0404-15<br>Geom. Analítica]:::math
    BCL0306[BCL0306-15<br>Biodiversidade]:::bct
  end

  subgraph "3º Quadrimestre"
    BCM0505[BCM0505-22<br>Process. Informação]:::bct
    BCJ0205[BCJ0205-15<br>Fen. Térmicos]:::bct
    BCN0407[BCN0407-15<br>Funções Várias Var]:::math
    BCL0307[BCL0307-15<br>Transf. Químicas]:::bct
  end

  subgraph "4º Quadrimestre"
    BCM0506[BCM0506-15<br>Comunicação/Redes]:::bct
    BCJ0203[BCJ0203-15<br>Fen. Eletromag]:::bct
    BCN0405[BCN0405-15<br>Introd. EDO]:::math
    BIN0406[BIN0406-15<br>Prob/Estat]:::math
    NHBP010[NHBP010-23<br>Óptica e Relatividade]:::fis
  end

  subgraph "5º Quadrimestre"
    BCK0103[BCK0103-15<br>Física Quântica]:::bct
    MCTB001[MCTB001-17<br>Álgebra Linear]:::math
    NHT3049[NHT3049-15<br>Princ. Termodinâmica]:::fis
    NHBP001[NHBP001-23<br>Física Exp I]:::exp
  end

  subgraph "6º Quadrimestre"
    HUM2[Humanidade 2]:::hum
    MCTB010[MCTB010-13<br>Cálc. Vet/Tensor]:::math
    NHT3068[NHT3068-15<br>Mec. Clássica I]:::fis
    NHBP002[NHBP002-23<br>Física Exp II]:::exp
  end

  subgraph "7º Quadrimestre"
    HUM3[Humanidade 3]:::hum
    NHT3066[NHT3066-15<br>Var. Complexas]:::math
    NHT3070[NHT3070-15<br>Eletromagnetismo I]:::fis
    NHP003[NHP003-23<br>Física Exp III]:::exp
    OL1[Opção Limitada]:::fis
  end

  subgraph "8º Quadrimestre"
    BCL0308[BCL0308-15<br>Bioquímica]:::bct
    NHT3067[NHT3067-15<br>Análise Fourier]:::math
    NHBP007[NHBP007-23<br>Mec. Quântica I]:::fis
    OL2[Opção Limitada]:::fis
  end

  subgraph "9º Quadrimestre"
    BCS0002[BCS0002-15<br>Projeto Dirigido]:::bct
    NHBP008[NHBP008-23<br>Mec. Quântica II]:::fis
    NHBP004[NHBP004-23<br>Física Exp IV]:::exp
    OL3[Opção Limitada]:::fis
  end

  subgraph "10º-12º Quadrimestres"
    OL4[Opção Limitada]:::fis
    OL5[Opção Limitada]:::fis
    LIVRE[Disciplinas Livres]:::fis
    TCC[TCC - 10h]:::fis
    EXT[Atividades Extensionistas]:::fis
  end

  %% Ligações de recomendação (apenas principais)
  BCN0402 --> BCN0407
  BCN0404 --> MCTB001
  BCN0402 --> BCN0405
  BCN0407 --> MCTB010
  BCN0407 --> NHT3066
  MCTB001 --> MCTB010
  MCTB010 --> NHT3066
  MCTB010 --> NHT3067
  BCN0405 --> NHT3067

  BCJ0204 --> NHT3068
  BCJ0205 --> NHT3049
  BCJ0203 --> NHT3070
  BCK0103 --> NHBP007
  NHBP007 --> NHBP008
  NHT3068 --> NHBP007
  NHT3070 --> NHBP007
  NHT3049 --> NHBP007

  NHBP001 --> NHBP002 --> NHP003 --> NHBP004
