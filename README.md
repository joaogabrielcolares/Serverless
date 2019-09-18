# Serverless

## Objetivo: 
  Conhecer funcionamento dos serviços da AWS, principalmente S3 e Lambda.
  
## Funcionalidade:
  Criar uma função Lambda para otimizar imagens que são enviadas para o S3.

## Stacks:  
  - AWS;
  - Lambda;
  - S3;
  - Framework Serverless;
  - js;
  
## Comandos basicos
  - Comando para criação serverless
      * serverless create --template aws-nodejs --path nodeless

  - Serviço da AWS para configurar seu acesso
      * IAM

  - Comando para configurar seu ambiente para publicar suas lambdas. Após criar usuário no IAM.
      * serverless config credentials --o --provider aws --key=(key) --secret (secret)
      * --o (PARA SOBRESCREVER CONFIURAÇÕES QUE JA FORAM FEITAS NA MAQUINA)

  - Deploy
      * serverless deploy -v

  - Formas de disparar uma função serverless
      * Rota http
      
      * Eventos -  que são disparados por outros eventos da AWS
      
      * Linha de comando
          *serverless invoke -f hello -l
              *f (executar uma função)
              *l (Listar operações conforme ele for aparecendo)

  - Deletar serveless
      * serverless remove
  
