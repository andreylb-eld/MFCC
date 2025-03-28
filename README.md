## Coeficientes Cepstrais de Frequências Mel (MFCC)
Este repositório explora os conceitos e a implementação dos **Coeficientes Cepstrais de Frequências Mel (MFCC)**, uma técnica importante de processamento de sinais amplamente utilizada na extração de características de áudio e fala. Embora o uso do MFCC tenha diminuído devido ao crescimento do Deep Learning, ele ainda é altamente relevante quando utilizado em conjunto com algoritmos clássicos de Machine Learning. As aplicações incluem **reconhecimento de fala**, **análise de música**, **análise/detecção de sentimentos** e muito mais.
### Visão Geral do Notebook
O repositório contém um Jupyter Notebook que cobre os seguintes tópicos:
1. **Introdução ao MFCC**:
    - Explica a importância e as aplicações do MFCC.
    - Mostra seu papel na transformação de sinais de áudio em características analisáveis.

2. **Etapas da Implementação**:
    - **Transformada de Fourier Discreta (DFT)**:
        - Converte sinais no domínio do tempo para seus componentes no domínio da frequência.
        - Visualiza o espectro de um sinal de áudio.

    - **Transformada de Fourier de Tempo Curto (STFT)**:
        - Divide o sinal em janelas sobrepostas para gerar representações tempo-frequência.
        - Calcula um espectrograma e aplica escala logarítmica para melhor visualização.

    - **Filtros Mel**:
        - Aplica escalas Mel para destacar bandas de frequência perceptíveis.
        - Cria espectrogramas na escala Mel baseados na percepção humana de frequências.

    - **Extração de MFCC**:
        - Mostra como extrair os coeficientes MFCC a partir dos espectrogramas em escala Mel.

3. **Visualização de Dados**:
    - Visualização da forma de onda e do espectro de arquivos de áudio.
    - Gráficos detalhados e bem estruturados, apresentados passo a passo para facilitar o entendimento.

4. **Processamento de Áudio**:
    - Utiliza bibliotecas como `librosa` para carregar e processar arquivos de áudio.
    - Demonstra os fluxos de trabalho para extração de características utilizando Python.

5. **Demonstração de uma tarefa de Classificação**:
   - Extrai os MFFCs de um conjunto de áudio com sons de gatos e cachorros.
   - Treina um classificador de Regressão Logística para a tarefa.

**Créditos**: 
A parte 5. do projeto, incluindo os dados utilizados, foi totalmente retirada do seguinte repositório: https://github.com/FilipTirnanic96/mfcc_extraction <br>
Todos os créditos são devidos ao seu autor.
        

