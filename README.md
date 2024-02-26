# ponderadaSemana3
# Relatório técnico - Acesso SSH no EC2.

### Introdução
Esse relatório foi desenvolvido com a visão de auxilia-lo no processo de criação de uma Instãncia EC2 na AWS e acessá-la por meio do SSH, utilizando o Openssh.

### Objetivo
O objetivo desse relatório é compartilhar algumas das etapas na criação de uma instância EC2 na AWS, conectando-a por meio do SSH (Openssh) e em seguida, documentando o processo de criação feito.

### Materiais
- Conta AWS
- Uso da Openssh para ter o acesso SSH
- Interface de acesso a linha de comando
- VScode

### Métodos
Prints solicitados da criação:
- Console com a máquina criada
- Para essa primeira etapa, eu loguei na plataforma da AWS academy, ativei minha máquina e criei a instância EC2. Na configuração da minha instância, setei algumas confingurações, como chaves privadas, nome da instância, escolhi a AMI (Amazon Machine Image) - Ubuntu.

![alt text](console.png)

- SSH bem sucedido
- Após a instância ter sido criada com sucesso, entrei no menu da minha instância, conectar-se à distância, cliente SSH e copiei o código que inicia a instância e conecta-se a máquina pelo SSH- Openssh. Meu comando de conexão é esse: ssh -i "keypairname.pem" ubuntu@ec2-3-88-129-96.compute-1.amazonaws.com. Após eu abrir, procurar a pasta onde minhas privates keys se encontram. Sendo assim, consegui executar e me conectar à máquina.

![alt text](ssh.jpg)

- IP da máquina EC2 criada

- Por último, o print do IP da minha instãncia EC2. O IP pode ser visto no painel inicial das suas instâncias, ou no menu de configuração da instância. Você pode visualizar o endereço de IP público e privado. Sendo o primeiro responsável por acessar sua instância pela internet. Já o segundo, é responsável pela configuração dessa instância, por isso privada.

![alt text](ip.png)

### Resultados
Neste relatório, é apresentado com sucesso o passo a passo para criar uma instância do EC2 na AWS e acessá-la por meio do SSH utilizando o Openssh. O repositório no GitHub oferece um registro claro e bem organizado, contendo capturas de tela do console com a máquina criada na conta do usuário, comprovação do acesso SSH bem-sucedido e o endereço IP da instância do EC2. A documentação está estruturada através de commits distintos no GitHub, sendo preferencialmente realizados por meio da interface de linha de comando.

### Conclusão
A criação da instância EC2 foi concluída com sucesso. O usuário conseguiu realizar o acesso via SSH, inserindo corretamente os comandos por meio do SSH. Através deste relatório, foi possível realizar o acesso SSH na instância do Amazon Elastic Compute Cloud (EC2). O acesso SSH ao servidor EC2 foi realizado com sucesso, permitindo uma conexão segura e autenticada entre as instâncias do Amazon Web Services.