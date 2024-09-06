# • Athom Studios | Recrutamento
_Desenvolver uma aplicação Flutter para Android e iOS_
## Bem vindo(a)

Obrigado por participar do desafio da Athom! Estamos muito contentes pelo seu primeiro passo para fazer parte de um time excepcional. Você deverá criar um aplicativo para leitura e criação de QRCodes. Para termos um layout minimamente definido, anexamos abaixo um link de inspiração que podem te ajudar a desenvolver esse app:

- [Inspiração](https://dribbble.com/shots/6140065-QR-Code-scanner-microinteraction)

Pense no desafio como uma oportunidade de mostrar todo o seu conhecimento. E faça com calma, você tem duas semanas para entregar! Sua avaliação será baseada nos seguintes tópicos:

- Arquitetura
- Consumo de APIs
- GIT
- Layout's
- Fluxo de navegação.
- Não existe nenhum pré-requisito, portanto sinta-se a vontande para utilizar qualquer linguagem e usar ou não usar bibliotecas.

Sabemos que testes não é um tópico que todos dominam ou tem conhecimento, por isso aceitamos desafios de todos os perfis e diferentes níveis de conhecimento técnico. Mas nos preocupamos com a qualidade, saúde e evolução do produto e por isso acreditamos bastante em testes automatizados.

[[English](https://github.com/Athom-Studios/mobile-challenge/blob/main/README.md) | [Português](https://github.com/Athom-Studios/mobile-challenge/blob/main/README.pt.md)]

## Instruções
- Faça um fork desse projeto para a sua conta pessoal do GitHub.
- Siga as especificações abaixo.
- Crie um README com as instruções para compilar, testar e rodar o projeto.
- O link do repositório deverá ser enviado para o e-mail mathuscardoso@gmail.com com o título Teste Flutter Developer.

## Especificações Técnicas
- Utilizar os widgets do Cupertino do Flutter, visando uma experiência mais próxima do iOS.
- O app deve ser capaz de gerar e escanear QR codes.
- Implementar animações suaves para transições entre telas.
- Testes automatizados (Desejável).
- Layout responsivo para funcionar bem em diferentes tamanhos de tela (smartphones e tablets).

## Especificações Funcionais

### Tela Inicial
Essa tela terá duas funcionalidades principais posicionadas no centro da tela:

- Gerar QR Code: Um botão que leva o usuário a um formulário onde ele poderá inserir um texto/URL para gerar um QR Code.
- Escanear QR Code: Um botão que leva o usuário à tela de escaneamento utilizando a câmera do dispositivo.

### Funcionalidade de Geração de QR Code
- O usuário poderá digitar um texto ou URL e, ao pressionar o botão "Gerar", um QR Code correspondente será exibido na tela.
- O QR Code gerado deverá ser apresentado em um layout limpo, com opções para salvar a imagem do QR Code no dispositivo ou compartilhá-la diretamente.
- Deve-se utilizar os CupertinoTextField, CupertinoButton e outros componentes do Cupertino para a interface.

### Funcionalidade de Escanear QR Code
- O app deverá solicitar as permissões necessárias para acessar a câmera do dispositivo.
- Após escanear o QR Code, o app deverá apresentar o conteúdo codificado em uma nova tela.
- O app deve permitir copiar o conteúdo escaneado para a área de transferência e também redirecionar para URLs, caso o conteúdo seja um link.

### Detalhes Adicionais
- Caso o escaneamento falhe ou não seja encontrado um QR Code válido, deverá ser exibida uma mensagem informando o erro ao usuário.
- A aplicação deverá utilizar o plugin de escaneamento e geração de QR codes do Flutter, como o qr_flutter e o mobile_scanner.

### Requisitos Adicionais:
- Animação: Ao gerar o QR Code ou ao retornar com o resultado do escaneamento, a tela deve exibir uma transição suave entre as telas, utilizando animações Cupertino.
- Validação: O campo de entrada para a geração de QR Codes deve ser validado. Por exemplo, o campo não deve aceitar entradas vazias.
- Compartilhamento de Código: Após gerar um QR Code, o usuário deve poder compartilhar o código diretamente através de apps de mensagem ou redes sociais.

### Wireframe
Você pode criar um layout livre, mas os elementos principais devem estar bem distribuídos para proporcionar uma boa experiência ao usuário.

## O que será avaliado?
- Organização do projeto.
- Lógica do código.
- Uso do Git.
- Componentização e reutilização de widgets.
- Uso adequado de permissões de câmera.
- Testes automatizados (se aplicável).
- Responsividade e compatibilidade com diferentes dispositivos.
- Qualidade das animações e transições entre telas.

## Instruções para Compilar e Rodar o Projeto

### Pré-requisitos:
- Instale o Flutter SDK em sua máquina.
- Configure um emulador Android/iOS ou conecte um dispositivo físico para testar o aplicativo.

### Passos:

Clone seu repositório:
``` bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```
Instale as dependências do projeto:

``` bash
flutter pub get
```
Rode o app no emulador ou dispositivo físico:

``` bash
flutter run
```

