# Microsoft Azure AI Fundamentals

Bootcamp da DIO em parceria com a Microsoft, visando a preparação de profissionais para a certificação AI-900. 

## Projeto 2: Visão Computacional

Neste segundo desafio de projeto, o objetivo é utilizar a ferramenta do Azure AI Vision para reconhecimento facial, análise descritiva de imagem e reconhecimento de texto. As imagens utilizadas neste projeto estão contidas na pasta **inputs** e os arquivos JSON correspondentes estão na pasta **outputs**.

## Etapas do Projeto

### 1. Criando o Workspace

Acesse o portal do Azure, utilizando uma conta Microsoft. Selecione a opção "Create a Resource", selecione a categoria "AI + Machine Learning" e acesse "Azure AI Services", clicando em "Create". 
![readme1](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/b6605e33-6bcc-4320-8fc9-f0a666b18dfd)

Após criar o "Resource Group", acesse o portal do Azure AI Vision Studio (https://portal.vision.cognitive.azure.com/). Nele, clique em "View all resources".
![readme2](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/b642b2b9-0852-4cd3-a3c8-e62d264e3dfa)

Selecione o 'resource' criado e clique em "Select as default resource".
![readme3](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/9573811b-332b-40da-a883-6d1c3f9c36d3)

### 2. Reconhecimento Facial

Para realizar o reconhecimento facial em imagens, selecione a ferramenta "Detect faces in an image" na aba "Face". Faça o upload da imagem a ser analisada.
![readme4](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/6f3c6569-a23d-424a-8ec8-5272a77bc058)

Após o upload da imagem, é possível ver os resultados em "Detected attributes" e o arquivo JSON correspondente.
![readme5](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/64fce0ac-dad6-407f-956e-382d998eb965)

### 3. Reconhecimento de Imagem

Para realizar a análise descritiva de uma imagem, selecione a ferramenta "Add caption to images" na aba "Image analysis". Faça o upload da imagem a ser analisada.
![readme6](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/aa5b2fe4-3030-41d8-b6d7-3574ea7144bf)

Após o upload da imagem, é possível ver os resultados em "Detected attributes" e o arquivo JSON correspondente.
![readme7](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/0dca427a-e63a-48d5-b2d8-a668bdbce657)

### 4. Reconhecimento de Texto

Para realizar o reconhecimento de texto em imagens, selecione a ferramenta "Extract text from images" na aba "Optical character recognition". Faça o upload da imagem a ser analisada.
![readme8](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/67e4c5da-b30b-479b-a2ad-35f8cd0eaab0)

A primeira análise foi realizada em uma foto. Após o upload da imagem, é possível ver os resultados em "Detected attributes" e o arquivo JSON correspondente.
![readme9](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/ec67cea2-ca4d-47ca-8f1c-e9be94b24f40)

A segunda análise foi realizada em um print. Após o upload da imagem, é possível ver os resultados em "Detected attributes" e o arquivo JSON correspondente.
![readme10](https://github.com/mkatzor36/dioBootcampAI900_projeto2-Azure-AI-vision/assets/54877987/702adc21-a608-447a-a9fc-817fed254b59)

## Referências
 
1. https://aka.ms/ai900-image-analysis;
2. https://aka.ms/ai900-face; 
3. https://aka.ms/ai900-ocr;
