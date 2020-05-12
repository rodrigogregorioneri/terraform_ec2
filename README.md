# Criação de EC2 t2.micro

Caracteristicas:

OS: Ubunto
Tamanho: t2.micro
Imagem: "ami-03e33c1cefd1d3d74"
Provider:  AWS
Region: us-east-1

Comandos para testar:

terraform init ## Cria os states iniciais e o executavel do terraform

terraform plan ## testa antes o que vai subir de fato

terraform apply ## Sobe a infra no provider AWS


