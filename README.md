# AWS Lightsail Criando Instancia de Wordpress

### Definição

O **AWS Lightsail** é uma solução da Amazon Web Services (AWS) que facilita o uso de infraestrutura na nuvem para pessoas que não têm muita experiência técnica. Ele oferece servidores virtuais (chamados de **instâncias**) que podem ser configurados rapidamente para hospedar sites, aplicações, ou até mesmo bancos de dados.

Pense no Lightsail como uma "versão simplificada" dos serviços mais avançados da AWS, mas ainda poderosa o suficiente para atender à maioria das necessidades de um pequeno site ou aplicação.

Aqui estão alguns pontos principais sobre o AWS Lightsail:

1. **Instâncias de Servidores Virtuais:** São servidores "na nuvem" que você pode usar para rodar sites, armazenar arquivos, e executar aplicativos.
2. **Preços Fixos:** Ao contrário de outros serviços da AWS que cobram com base no uso, o Lightsail oferece planos com preços fixos, o que facilita o controle de custos.
3. **Facilidade de Uso:** Ele vem com interfaces e ferramentas simplificadas, como instaladores automáticos para WordPress, que tornam o processo de criação de um servidor e de hospedagem de sites mais fácil e rápido.
4. **Recursos Básicos:** Cada instância vem com um conjunto de recursos básicos, como armazenamento, largura de banda e memória RAM, e você pode escolher o que mais se adequa ao seu projeto.

Se você já usa o **Azure**, pode imaginar o Lightsail como algo similar ao **Azure Virtual Machines**, mas focado em simplicidade e custo previsível para quem está começando ou quer algo mais direto.


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


### Portal

**AWS Lightsail:** https://aws.amazon.com/pt/lightsail/

### Criando Instância de Wordpress

Selecione na aba lateral (esquerda) 'Instancia' -> 'Criar Instancia'.
![image](https://github.com/user-attachments/assets/76e04d75-e975-4c9a-a517-72f33e220dbb)

Seleciona a opção 'Linux' -> 'Apps + Os' -> 'Wordpress'.

![image](https://github.com/user-attachments/assets/1b73a559-a223-43ed-833b-b990fe526c87)

Seleciona o plano desejado.

![image](https://github.com/user-attachments/assets/f4a2e7bc-3d6b-4df5-98d3-176df50c140a)

Altera o nome da instancia.

![image](https://github.com/user-attachments/assets/c625d449-0f33-4b7b-aa69-c94d6ee8a227)

----------------------------------------------------------------------------------------------------------------------

### Acessando a instância do Wordpress

Acessa a aba instancia e pega o IP e adiciona no final da URL 'wp-admin'.

![image](https://github.com/user-attachments/assets/8ae4afee-d9cc-4b62-a9ba-f6a037185c08)

Conforme na imagem anterior (Destaque amarelo), abra o terminal e digite os comandos da imagem a seguir, para recuperar as credênciais.

![image](https://github.com/user-attachments/assets/128ec7d8-c353-4b77-944d-f680951c2975)

![image](https://github.com/user-attachments/assets/d3bd22e5-88ef-45f1-a607-f44636a43cfc)

----------------------------------------------------------------------------------------------------------------------

### Atribuindo IP estático a aplicação.

Selecione 'Instancia' -> 'Manage'(Na instância desejada)

![image](https://github.com/user-attachments/assets/4dc8d21f-db0b-4af6-b443-fddb0ff4a9bb)

Clique em 'Anexar IP estático' e atribua um nome.

