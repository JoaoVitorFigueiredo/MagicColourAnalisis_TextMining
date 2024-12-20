# Previsão das cores de cartas em Magic: The Gathering  
**Projeto Final de Text Mining**  

## Instruções para utilização do modelo de previsão  

### Organização da pasta:  
**Nome da pasta:** `MagicColourAnalisis_TextMining`  



### Subpastas:  
1. **Datasets**:  
   - Contém os arquivos CSV correspondentes:  
     - DataFrame original.  
     - TF-IDF filtrado.  

2. **Tratamento de Dados**:  
   - Limpeza e pré-processamento dos dados brutos.  


### Ficheiros na página principal:  
1. **Codigo_tfidf.ipynb**:  
   - Script para criar o modelo TF-IDF e o DataFrame filtrado.  
   - Inclui a lógica para remoção de textos vazios e exportação para CSV.  
   - Contém outras informações importantes sobre o estudo do DataFrame inicial e o TF-IDF.  

2. **Teste_para_prever_Cartas.ipynb**:  
   - Script de teste para prever as cores das cartas.  
   - Permite inserir frases manualmente e verificar a previsão de cores associadas.  

3. **Requirements.txt**:  
   - Lista de dependências necessárias para o projeto.  
   - Instalar com:  
     ```bash
     pip install -r Requirements.txt
     ```  

4. **Arquivos `.pkl`**:  
   - Modelos pré-treinados:  
     - Vetorizador (TF-IDF).  
     - Classificadores (Logistic Regression, Naive Bayes).  
     - Transformadores.  
