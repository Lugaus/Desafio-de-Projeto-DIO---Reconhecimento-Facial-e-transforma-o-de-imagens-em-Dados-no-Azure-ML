# Configuração do Serviço Azure AI Face

Este guia orienta você sobre como configurar um recurso de serviços de IA do Azure para utilizar o serviço Azure AI Face. Siga os passos abaixo para criar o recurso e conectá-lo ao Vision Studio.

## Criação do Recurso de Serviços de IA do Azure

1. Acesse o [portal do Azure](https://portal.azure.com) em uma nova guia do navegador e faça login com a conta da Microsoft associada à sua assinatura do Azure.

2. Clique no botão **+ Criar um recurso** e pesquise por **serviços de IA do Azure**. Selecione **Criar um plano de serviços de IA do Azure**. Você será redirecionado para a página de criação do recurso.

3. Configure o recurso com as seguintes configurações:
   - **Assinatura**: Selecione sua assinatura do Azure.
   - **Grupo de recursos**: Escolha um grupo de recursos existente ou crie um novo com um nome exclusivo.
   - **Região**: Selecione **Leste dos EUA**.
   - **Nome**: Insira um nome exclusivo para o recurso.
   - **Nível de preços**: Escolha **Padrão S0**.
   - Marque a caixa de confirmação dos termos de serviço.

4. Clique em **Revisar + criar** e, em seguida, em **Criar**. Aguarde até que a implantação seja concluída.

## Conexão do Recurso ao Vision Studio

1. Em outra guia do navegador, acesse o [Vision Studio](https://portal.vision.cognitive.azure.com) e faça login com sua conta. Certifique-se de estar no mesmo diretório onde você criou o recurso de serviços de IA do Azure.

2. Na página inicial do Vision Studio, clique em **Visualizar todos os recursos** no título **Introdução ao Vision**.

3. Na página **Selecione um recurso para trabalhar**, localize o recurso que você criou na lista. Marque a caixa à esquerda do nome do recurso e selecione **Selecionar como recurso padrão**.

   > **Nota**: Se o seu recurso não estiver listado, atualize a página.

4. Feche a página de configurações selecionando o ícone "x" no canto superior direito da tela.

Com isso, seu recurso de serviço de IA do Azure estará conectado ao Vision Studio, pronto para ser utilizado para reconhecimento facial e outras tarefas de processamento de imagem.

## Detecte rostos no Vision Studio
Para detectar rostos no Vision Studio, siga estas instruções:

Acesso ao Vision Studio: Abra um navegador e vá para o Vision Studio em https://portal.vision.cognitive.azure.com.

Seleção da Guia Face: Na página inicial "Introdução ao Vision", clique na guia "Face" e selecione o bloco "Detectar rostos em uma imagem".

Experimente com Imagens: Selecione cada imagem de amostra fornecida e observe os detalhes de detecção facial retornados.

 Faça upload das imagens de sua preferência e revise os detalhes de detecção de rosto retornados.

### Exemplo:
![Mulher de lado](https://github.com/Lugaus/Desafio-de-Projeto-DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML/assets/129623426/025c3279-c03e-4609-8535-d73a5d804fcb)
![Grupo de pessoas](https://github.com/Lugaus/Desafio-de-Projeto-DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML/assets/129623426/1aef2957-74e7-4a3c-b3e4-2ebaef45f28a)


## Extraia texto de imagens no Vision Studio
Para extrair texto de imagens usando o Vision Studio, siga estas etapas:

Acesso ao Vision Studio: Acesse o Vision Studio em https://portal.vision.cognitive.azure.com.

Seleção do Reconhecimento Óptico de Caracteres (OCR): Na página inicial "Introdução ao Vision", clique em "Reconhecimento óptico de caracteres" e selecione o bloco "Extrair texto de imagens".

 Selecione o arquivo de sua preferência e observe os detalhes do texto extraído, incluindo a localização do texto na imagem.
### Exemplo:
![logotipos](https://github.com/Lugaus/Desafio-de-Projeto-DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML/assets/129623426/680a038b-d6a6-48fc-8dbd-9bfbcd715ea5)
![retorno Nutrition Facts](https://github.com/Lugaus/Desafio-de-Projeto-DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML/assets/129623426/0e040e30-2f06-4dc0-8ccc-323a2c3c429a)









## Gerar legendas para uma imagem
Para gerar legendas para imagens no Vision Studio, siga estas instruções:

Acesso ao Vision Studio: Acesse o Vision Studio em https://portal.vision.cognitive.azure.com.

Seleção do Bloco de Análise de Imagem: Na página inicial "Introdução ao Vision", clique na guia "Análise de imagem" e selecione o bloco "Adicionar legendas às imagens".

 Carregue a imagem de de sua preferência e observe a legenda gerada visível no painel "Atributos detectados".
 ### Exemplo:
![Um urso panda sentado em uma pedra comendo bambu](https://github.com/Lugaus/Desafio-de-Projeto-DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML/assets/129623426/09d14baf-b617-4762-bc73-534d92b9472a)
![Um grupo de pessoas em um cassino](https://github.com/Lugaus/Desafio-de-Projeto-DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML/assets/129623426/f319b600-bda8-4988-b8bc-bac7b50dcde5)







 

## Insights e Possibilidades

Durante a exploração do conteúdo, identificamos diversas oportunidades oferecidas pelas ferramentas de IA do Azure:

- **Detecção Facial Avançada**: O Azure AI Face permite a detecção precisa de rostos em imagens, útil para segurança e análise de sentimentos.
  
- **Extração de Texto de Imagens**: O Reconhecimento Óptico de Caracteres (OCR) do Azure extrai texto de imagens, ideal para automação de processos e análise de documentos.
  
- **Geração de Legendas para Imagens**: O Vision Studio gera legendas descritivas para imagens, facilitando a compreensão visual em sistemas de busca e acessibilidade.

- **Análise Avançada de Imagens**: Além da detecção básica, o Vision Studio oferece recursos avançados, como identificação precisa de objetos em imagens.

Essas possibilidades destacam o potencial das ferramentas de IA do Azure para impulsionar a inovação em uma variedade de domínios, desde reconhecimento de imagem até análise de documentos e acessibilidade.
