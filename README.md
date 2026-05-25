# Analisador-de-Documentos
Serviço que utiliza AWS Lambda, que processa documentos, extrai texto automaticamente e gera análises inteligentes.
#  recursusos principais 
upload dde documentos via s3
extração de texto usando tesseract ocr
resumo util0izando ia genererativa  olama llama
steackspot para funcionamento local

escrevendo arquitetura 


o usuario  faz uu´pload desses arquivos  para o s3 passanf=do pela api gateway .oarquivoao chegar no s3 a lambda é acionada . a lambda extrai o texto e faz o resumo usando aia generativa . por fim envia o resummopara o dynamodb
<img width="972" height="805" alt="image" src="https://github.com/user-attachments/assets/825274a6-5b93-4329-8201-881012253e67" />

