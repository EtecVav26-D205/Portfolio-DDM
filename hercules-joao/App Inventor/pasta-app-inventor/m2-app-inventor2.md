Relatório do Projeto – Aplicativo de Envio para Gmail
Projeto: Integração com Gmail no App Inventor
Desenvolvido em:

MIT App Inventor

## 1. Objetivo do Projeto ##
<img width="1919" height="989" alt="Captura de tela 2026-05-18 103754" src="https://github.com/user-attachments/assets/e544164d-6e61-4ee5-8e73-67044fa9edd2" />
<img width="1919" height="994" alt="Captura de tela 2026-05-18 103748" src="https://github.com/user-attachments/assets/d422e21c-0c80-44d1-baf3-c1ed83a2e1c0" />


O objetivo deste projeto foi desenvolver um aplicativo capaz de abrir automaticamente o aplicativo de e-mail do dispositivo utilizando o serviço Gmail, através da plataforma MIT App Inventor.

O sistema foi criado para demonstrar como realizar integração entre aplicativos utilizando programação em blocos, permitindo que o usuário informe um endereço de e-mail e seja redirecionado diretamente para o aplicativo de envio de mensagens.

## 2. Funcionalidade do Aplicativo ##

O aplicativo possui uma interface simples e funcional, contendo:

Campo de texto para digitação do e-mail;
Botão de acionamento;
Componente invisível ActivityStarter;
Integração com o Gmail utilizando o protocolo mailto:.

Quando o usuário digita um endereço de e-mail e pressiona o botão, o aplicativo executa automaticamente a abertura do aplicativo de e-mail instalado no celular.

## 3. Estrutura Utilizada ##
Componentes Visíveis
Componente	Função
CaixaDeTexto1	Receber o endereço de e-mail
Button1	Executar a ação de envio
Componentes Invisíveis
Componente	Função
ActivityStarter1	Abrir o aplicativo Gmail
## 4. Lógica de Programação ##

A lógica do sistema foi desenvolvida utilizando programação em blocos no App Inventor.

O aplicativo executa os seguintes passos:

O usuário digita o e-mail desejado;
O botão é pressionado;
O sistema junta o texto mailto: com o endereço informado;
O ActivityStarter recebe o link criado;
O Gmail é aberto automaticamente.

Estrutura utilizada nos blocos:

quando Button1.Clique
    ajustar ActivityStarter1.UriDeDados para
    juntar "mailto:" + CaixaDeTexto1.Texto

    chamar ActivityStarter1.IniciarAtividade
## 5. Diferencial do Projeto ##

O diferencial deste aplicativo está na integração prática entre o App Inventor e aplicativos externos do dispositivo móvel.

Entre os principais destaques:

Comunicação direta com aplicativos de e-mail;
Utilização do protocolo mailto:;
Interface simples e intuitiva;
Execução automática do Gmail;
Demonstração de integração entre sistemas mobile.

Além disso, o projeto mostra como aplicativos podem utilizar recursos nativos do Android para ampliar funcionalidades sem necessidade de programação avançada.

## 6. Tecnologias Utilizadas ##
MIT App Inventor
Programação em blocos;
ActivityStarter;
Protocolo mailto:;
Integração com aplicativos Android.
## 7. Conclusão ##

O desenvolvimento deste projeto permitiu compreender conceitos importantes sobre integração entre aplicativos móveis utilizando o App Inventor.

O aplicativo demonstrou de forma prática como abrir automaticamente o Gmail a partir de um endereço digitado pelo usuário, utilizando componentes simples e eficientes.

Durante o desenvolvimento foram aplicados conhecimentos sobre:

Programação por eventos;
Manipulação de texto;
Integração externa;
Navegação entre aplicativos;
Componentes invisíveis do App Inventor.

O projeto atingiu os objetivos propostos e pode ser expandido futuramente com novas funcionalidades, como:

Envio automático de assunto;
Corpo personalizado da mensagem;
Lista de contatos;
Histórico de e-mails enviados;
Integração com múltiplos aplicativos de e-mail.
