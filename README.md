# Analisador-de-Documentos
Serviço que utiliza AWS Lambda, que processa documentos, extrai texto automaticamente e gera análises inteligentes.
#  recursusos principais 
* upload dde documentos via s3
* extração de texto usando tesseract ocr( do Google)
* resumo utilizando ia genererativa  ollama + llama ( da Meta)
* steackspot para funcionamento local

#escrevendo arquitetura 

o usuario  faz upload desses arquivos  para o s3 passando pela api gateway .O arquivoao chegar no s3 a lambda é acionada . A lambda extrai o texto usando tesseract ocr( do Google) e faz o resumo usando a ia generativa ollama + llama ( da Meta). Por fim envia o resummo para o dynamodb.
<img width="972" height="805" alt="image" src="https://github.com/user-attachments/assets/825274a6-5b93-4329-8201-881012253e67" />

