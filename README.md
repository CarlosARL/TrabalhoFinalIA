## NeSy Learner - Michalsky (Colab 1, 2 e 3c)

Este repositório contém um modelo NeSy Learner e questões relacionadas, desenvolvido para os exercícios 1, 2 e 3c do Colab sobre Michalsky.

### Visão Geral dos Arquivos

- **`NeSy_Learner_Michalsky_Colab_1_e_2_e_3c.ipynb`**: Este é o notebook principal contendo o modelo NeSy Learner e as questões a serem respondidas. Este é o notebook que deve ser executado para explorar o projeto.
- **`data.ipynb`**: Este notebook foi usado para pré-processar os dados brutos do arquivo `trains-100.csv`, gerando o arquivo  `trains-100-mod.csv` utilizado pelo notebook principal.
- **`trains-100.csv`**: O dataset original utilizado para o pré-processamento.
- **`trains-100-mod.csv`**: Os dados pré-processados, utilizados pelo notebook principal.

### Passos para Executar o Notebook Principal

1. **Configurar o Ambiente:**
   - Certifique-se de ter o Python instalado em seu sistema.
   - Instale os pacotes necessários:
     ```bash
     pip install notebook pandas numpy scikit-learn
     ```

2. **Preparar os Dados:**
   - Certifique-se de que o arquivo `trains-100-mod.csv` esteja presente no mesmo diretório que o notebook principal (`NeSy_Learner_Michalsky_Colab_1_e_2_e_3c.ipynb`). 
   - Caso contrário, execute o notebook `data.ipynb` para gerar o arquivo `trains-100-mod.csv` a partir do arquivo `trains-100.csv`.

3. **Executar o Notebook Principal:**
   - Abra um terminal e navegue até o diretório onde o arquivo `NeSy_Learner_Michalsky_Colab_1_e_2_e_3c.ipynb` está localizado.
   - Inicie o Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Na interface do Jupyter Notebook, clique no arquivo `NeSy_Learner_Michalsky_Colab_1_e_2_e_3c.ipynb` para abri-lo.
   - Execute todas as células do notebook selecionando *Cell > Run All* no menu ou pressionando `Shift + Enter` em cada célula.

### Notas

- Certifique-se de que todos os arquivos necessários (`NeSy_Learner_Michalsky_Colab_1_e_2_e_3c.ipynb`, `trains-100-mod.csv`) estejam no mesmo diretório.
- Se houver dependências faltando, instale-as usando `pip`.
- Este README.md foi escrito de acordo com as informações fornecidas. Adapte-o conforme necessário para refletir qualquer informação adicional ou específica do seu projeto. 
