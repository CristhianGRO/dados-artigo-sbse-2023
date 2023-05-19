<div align="center">
    <img src=".github/Imagens/solar-energy-icon.svg" style="width: 20vw">
    
    Repositório de Dados: Uma Avaliação em Série-Temporal Quase-Estática da 
    Capacidade de Hospedagem de Geração FV em Redes de Distribuição 
</div>

Dados Referentes ao **Artigo** submetido ao **Simpósio Brasileiro de Sistemas Elétricos** (SBSE) 2023




<br><br>

# ⛅ Introdução

O presente repositório reúne os dados utilizados para o desenvolvimento das simulações, bem os resultados obtidos, expostos no artigo _"Uma Avaliação em Série-Temporal Quase-Estática da Capacidade de Hospedagem de Geração FV em Redes de Distribuição"_, submetido ao Simpósio Brasileiro de Sistemas Elétricos (SBSE) 2023.

O objetivo desse material é possibilitar que outros pesquisadores do tema utilizem o modelo adotado para comparação e validação de resultados, bem como para o desenvolvimento de novas pesquisas envolvendo o tema.

<br><br>

# 🗂️ Organização

## Pasta: _Dados do Modelo_
Esta pasta contém os dados do modelo de sistema de distribuição utilizado para as simulações.

Os arquivos, presentes nessa pasta são:

- `Dados_Ramo.csv`: dados de conexão entre os barramentos e dados de resistência e reatância das linhas; 
- `Dados_Barra.csv`: dados de tipo, carga nominal ativa e reativa e limites de tensão para cada uma das barras;  
- `Dados_Curva_de_Carga_P.csv`: perfil de carga de potência ativa normalizada para cada um dos barramentos;
- `Dados_Curva_de_Carga_Q.csv`: perfil de carga de potência reativa para cada um dos barramentos;

## Pasta: _Dados de Geração Fotovoltaica_
Esta pasta contém os dados da curva de geração fotovoltaica para cada estudo de caso, além das potências instaladas dos arranjos fotovoltaicos.

Os arquivos, presentes nessa pasta são:

- `Dados_Fotovoltaico_EC2_X_A.csv`: curvas de geração fotovoltaica e potência instalada para o Estudo de Caso com X% de hospedagem, com centro de geração fotovoltaico no agrupamento A; 
- `Dados_Fotovoltaico_EC2_X_B.csv`: curvas de geração fotovoltaica e potência instalada para o Estudo de Caso com X% de hospedagem, com centro de geração fotovoltaico no agrupamento B; 

## Pasta: _Resultados_
Esta pasta contém os arquivos .csv com os resultados de cada estudo de caso, obtidos através das simulações realizadas no desenvolvimento deste artigo.

Os arquivos disponíveis são:

- `results_EC0.csv`: Estudo de Caso 0;
- `resultsEC1.csv`: Estudo de Caso 1;
- `resultsEC2_X_A.csv`: Estudos de Caso com centro de geração no agrupamento A, para uma hospedagem de X%.
- `resultsEC2_X_B.csv`: Estudos de Caso com centro de geração no agrupamento B, para uma hospedagem de X%.



<br><br>

# 💾 Download
Baixe os dados deste repositório em formato `.zip` [através deste link](https://github.com/CristhianGRO/dados-artigo-sbse-2023/archive/refs/heads/main.zip)



<br><br>

# ✉️ Contato

Dúvidas ou sugestões? Entre em contato conosco: 

- **E-mail:** cristhiangro@gmail.com

<br><br>

# 💬 Cite este repositório

```bibtex
@article{STQE-SBSE-2023,
    title    = {Repositório de Dados: Uma Avaliação em Série-Temporal Quase-Estática da Capacidade de Hospedagem de Geração FV em Redes de Distribuição},
    year     = {2023},
    url      = {https://github.com/CristhianGRO/dados-artigo-sbse-2023},
    author   = {Cristhian Gabriel da Rosa de Oliveira; Gabriel Rodrigues Tremeschin},
    keywords = {Capacidade de Hospedagem; Recursos Energéticos Distribuídos; Redes de Distribuição; Sistemas Fotovoltaicos.},
}
```
