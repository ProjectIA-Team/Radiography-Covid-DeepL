# Radiography-Covid-DeepL

# Deep Learning em Raios-X de Tórax

<p>
  <a href="https://github.com/ProjectIA-Team/CampogramFIFA/blob/main/imagem_summit.png">
    <img src="imagem_summit.png" alt="umc_summit">
  </a>
</p>

## Descrição do Projeto

Este projeto tem como objetivo demonstrar o uso de técnicas de **Deep Learning** na análise de imagens médicas, utilizando um banco de dados de raios-X de tórax. Através deste trabalho, aplicamos modelos de redes neurais convolucionais (CNNs) para classificar imagens de raios-X em diferentes categorias relacionadas a condições pulmonares, ilustrando o potencial da inteligência artificial na área da saúde.

## Estrutura do Banco de Dados

O banco de dados contém imagens de raios-X de tórax, cada uma com resolução de **299x299 pixels**, divididas nas seguintes categorias:

- **COVID-19**: 3.616 casos positivos.
- **Opacidade Pulmonar**: 6.012 casos (infecções pulmonares não relacionadas à COVID-19).
- **Pneumonia Viral**: 1.345 casos.
- **Normais**: 10.192 imagens de indivíduos saudáveis.

## Objetivo

O foco principal do projeto é classificar automaticamente as imagens de raios-X nas categorias acima, demonstrando como modelos de **Deep Learning** podem ser aplicados na prática para auxiliar diagnósticos médicos. Esse trabalho busca:

- Explorar a viabilidade do uso de redes neurais convolucionais em análise médica.
- Identificar padrões visuais específicos associados a diferentes condições pulmonares.
- Avaliar a precisão e eficácia do modelo em distinguir entre condições normais e anormais.

## Ferramentas Utilizadas

O projeto utiliza um conjunto robusto de ferramentas e bibliotecas de Python para o desenvolvimento e treinamento do modelo:

- **Google Colab**: Ambiente principal para implementação e execução do projeto.
- **Python**: Linguagem base.
- **Bibliotecas**:
  - `TensorFlow` e `Keras`: Para construção e treinamento do modelo de Deep Learning.
  - `NumPy` e `Pandas`: Para manipulação de dados.
  - `Matplotlib` e `Seaborn`: Para visualização dos dados e resultados.
  - `Scikit-learn`: Para validação do modelo e métricas de desempenho.

## Como Executar o Projeto

1. Clone este repositório:
    ```bash
    git clone https://github.com/ProjectIA_Team/Radiography-Covid-DeepL.git
    ```

2. Instale as dependências necessárias:
    ```bash
    pip install -r requirements.txt
    ```

3. Faça o download do banco de dados e salve-o na pasta `data/` (mais informações no arquivo README específico para o banco de dados).

4. Execute o notebook principal no Google Colab ou em seu ambiente Python preferido:
    - `DeepLearning_RaiosX.ipynb`

## Estrutura do Repositório

- `data/`: Contém o banco de dados de imagens (não incluído no repositório por limitações de espaço e direitos).
- `notebooks/`: Contém o notebook principal com o modelo e análises.
- `README.md`: Este arquivo.

## Resultados Esperados

O modelo será avaliado com base em métricas como:

- **Acurácia**: Medida da proporção de classificações corretas.
- **Precisão, Recall e F1-Score**: Para cada classe, fornecendo uma visão detalhada da performance.
- **Matriz de Confusão**: Para entender melhor os erros de classificação.

## Considerações Éticas

Este projeto é exclusivamente para fins educacionais e experimentais. O modelo desenvolvido **não deve ser utilizado para diagnósticos médicos reais** sem validação rigorosa e supervisão de profissionais qualificados.

## Contribuições

Contribuições são bem-vindas! Se desejar colaborar, abra um issue ou envie um pull request.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
