#================================================================================================
|                              PROCESSAMENTO DIGITAL DE IMAGEM			                            |
|                        Nome: Felipe Augusto Cortez Muniz da Silva			                      	|
#-----------------------------------------------------------------------------------------------
|                                        Descrição				                                  		|
#-----------------------------------------------------------------------------------------------

 Etapa 1.
 Este programa utiliza um motor de reconhecimento ótico de caracteres (OCR) de código aberto
 conhecido como Tesseract. Ele foi desenvolvido pelo Google e é capaz de converter imagens
 de texto em arquivos de texto editáveis. O Tesseract é instalado a parte no PC local e o
 acesso a sua funcionalidade é feito através da biblioteca pytesseract.

 Essa biblioteca é uma interface para a utilização do Tesseract OCR na linguagem de programação
 Python. A biblioteca pytesseract atua como um wrapper em torno do Tesseract, fornecendo uma
 maneira mais conveniente de interagir com o OCR usando Python. Outra biblioteca usada neste
 programa é OpenCV2 (Open Source Computer Vision Library). Esta biblioteca também é de código
 aberto e fornece ferramentas e algoritmos para procesasmento de imagens e visão computacional.
 A lógica do programa consiste em ler cada uma das imagens de carros do diretório de entrada e
 submeter a imagem lida ao OCR Tesseract. Caso a placa da imagem seja reconhecida, ela será
 impressa na tela. Caso contrário, o programa tentará reprocessar a imagem para resubmetê-la
 ao Tesseract

 Etapa 3 e 4
 A geolocalização associada a cada arquivo de imagem está sendo feita com valores aleatórios
 para longitude e latitude, e utiliza a biblioteca 'piexif' (para dados Exif - Exchangeable image
 file format - em imagens JPEG). As restrições associadas a estas geolocalizações de cada arquivo
 estão sendo implementadas como uma simples comparação com o valor de longitude de cada arquivo
 com um valor limite, que quando ultrapassado gera um alerta na saída do programa.
