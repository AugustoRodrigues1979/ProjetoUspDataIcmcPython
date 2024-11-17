# ProjetoUspDataIcmcPython
Projeto da USP - Curso Machine Learning USP com Python
Responsável: Augusto de Miranda Rodrigues
e-mail: guto.rodrigues1979@gmail.com

Projeto de Machine Learning através do uso da linguagem Python solicitado pelos professores(as) responsáveis pelo curso de Python para Ciência de Dados

Tem duas pastas:
- Pasta Objetivo  : Contem o material base para a realização do projeto solicitado pelos professores(as)
- Pasta Programa  : Contem os arquivos do colab que contem o projeto solicitado pelos pelos professores(as)

Na pasta Programa esta presente o arquivo colab que instancia e treina o aprendizado de duas machine learning disponiveis pelo módulo SVM (Support Vector 
Machine (Máquina de Vetores de Suporte, em português) da biblioteca Sklearn a saber:
- SVC  :  Sigifiica Support Vector Classification (Classificação por Vetores de Suporte)
- SVR  :  Significa Support Vector Regression (Regressão por Vetores de Suporte)

Ambas machine learning foram treinadas a partir da massa de dados de testes providenciada pela função train_test_split da biblioteca sklearn.model_selection

Depois de treinadas, aplica-se o método Validação Cruzada K-Fold para para melhorar a acurácia final dessas machine learning e após isso verifica-se o score
de ambas machine learning para verificar a eficacia de ambas quando aplicada as massas de testes junto com a chamada do método score dessas machines learning.

Os resultados obtidos são impressos via comando print do python e mostram que para as massas de dados fornecidas o score de ambas machines learning são 
quase idênticas.


  
