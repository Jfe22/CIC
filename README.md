# CIC
CNN Image Classifier


A CIC é um conjunto de redes neuronais convolucionais para a classificação de imagens. Contém quatro modelos: o primeiro foi criado de raiz e o segundo criado com recurso a transfer learning usando como base o modelo VGG16, ambos treinados com o mesmo conjunto de dados.
Depois de criados estes 2 modelos, o conjunto de dados foi aumentado através da criação de novas imagens a partir das originais, aplicando rotações e ampliações aleatórias. A partir deste novo dataset, foram criados mais dois modelos, um de raiz, e outro utilizando transfer learning.
