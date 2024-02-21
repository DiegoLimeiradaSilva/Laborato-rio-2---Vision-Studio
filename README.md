# vision-studio-microsoft-azure

- Passo a passo de experimento utilizando Vision Studio/ **Azure AI Vision** para extrair texto de imagens sem a utilização de código, com tecnologia OCR (Optical Character Recognition). Realizado como desafio de projeto no Bootcamp **Microsoft Azure AI Fundamentals** da [Dio.me](https://dio.me)

<br/>

## Passo 1

- Acessar [portal.azure.com](portal.azure.com) e clicar em "create a resource"

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/01.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/8a505e91-cc1b-446a-9e09-6fedf3b2dda)

## Passo 2

- Buscar por "Ai azure services" e clicar em "create"

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/02.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/1440bff9-db85-4e4c-add5-723ae2b1978)

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/03.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/9e018f9f-0c57-43b8-8627-d3c7b8df9c3)

## Passo 3

- Preencher as informações mostradas abaixo. O resource group pode ser novo ou existente. Escolhi um que eu já havia criado anteriormente. Depois disso, basta clicar em "review + create", e depois "create", e aguardar a finalização do deploy.

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/04.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/cc3d884b-29c9-4214-b857-a8956657335)

- Esta é a tela depois da finalização do deploy

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/05.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/df1bb43a-b25e-4b8d-8bf9-e3bb118ac11)

## Passo 4

- Conectar o resource com o Vision Studio.
- Em outro navegador, ir para [https://portal.vision.cognitive.azure.com/?azure-portal=true](https://portal.vision.cognitive.azure.com/?azure-portal=true) e clicar em "View All Resources"

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/06.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/b2f300c4-363a-4619-a9eb-39df4adfbcc)

- Clicar em "refresh" para que a lista seja carregada com o resource criado anteriormente, clicar para selecionar o mesmo, e depois clicar em "Select as default resource"

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/07.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/98557f0d-abe1-4d07-95ff-35108bd11db)

## Passo 5

- Em outro navegador, abrir novamente a landing page (<https://portal.vision.cognitive.azure.com/)[https://portal.vision.cognitive.azure.com/>], ir até a aba "Optical Character Vision" e clicar em "Extract text from images"

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/08.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/d44d01fc-6add-48a3-9a6d-336c8c704b0)

## Passo 6

- Marcar a opção conforme imagem abaixo
- Depois clicar no link fornecido pela documentação (<https://aka.ms/mslearn-ocr-images)[https://aka.ms/mslearn-ocr-images>], de onde será feito o download automaticamente do arquivo *ocr-images.zip*.

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/09.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/b9925fc8-c5b6-420a-9242-8bf68c6b189)

## Passo 7

- No portal, selecione "browse for a file" e selecione uma das imagens baixadas do arquivo anterior (lembrar de descompactar o zip primeiro).
- Selecionar uma imagem e depois abrir. Escolhi a imagem "letter.jpg"
- A coluna da esquerda mostra a imagem fornecida, e a da direita, o resultado do texto extraído.

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/10.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/cb04e08f-4bc6-45c7-bdfc-c71b29056f2)

- Teste com a imagem "note.jpg"

![image](https://github.com/DiegoLimeiradaSilva/Laborato-rio-2---Vision-Studio/blob/main/imagens/11.png?raw=truehttps://github.com/giselle-ferreira/vision-studio-microsoft-azure/assets/84051263/a8a6bf45-40d3-4169-b86c-f5a297d35c4)<div align="center">
