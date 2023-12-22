# Protocolos de internet - A linguagem secreta dos computadores
De uma forma ou de outra, todos sabemos o que é um protocolo. Seja ele formal ou informal, são regras que definem a comunicação entre duas pessoas, tornando a conversa fluida e natural.

Quando um amigo te encontra na rua, é comum ele te cumprimentar, fazer perguntas sobre você, parentes ou outro amigo. Após o cumprimento inicial, a conversa pode ser direcionada para outro tema, onde um fala e outro educadamente escuta e espera sua vez de falar novamente. Esse é um típico protocolo de amigos.

No contexto da internet, os protocolos são cruciais para que dispositivos e sistemas consigam se entender, pois definem como os dados devem ser solicitados, divididos, transmitidos e recebidos pelo destinatário, garantindo a comunicação entre computadores em uma rede qualquer.Dessa forma, o dispositivo que fala sabe como será ouvido e respondido por outro dispositivo dentro de uma mesma rede. 

Entenda o dispositivo sendo um aparelho eletrônico, como celular, tablet, smart tv, smart watch e etc. É por isso que você consegue enviar uma mensagem para sua mãe no WhatsApp Web e receber a resposta dela no celular. Todos os aparelhos sabem como essa comunicação deve acontecer.
## O modelo TCP/IP
Antes de falar sobre cada protocolo, é preciso entender o *modelo TCP/IP*. É muito fácil confundir o modelo com o protocolo *TCP/IP*. Enquanto o primeiro é um *cesto* contendo todos os protocolos o segundo é um protocolo que se encontra dentro do *cesto* já mencionado.

O modelo TCP/IP possui diversos protocolos com responsabilidades bem específicas. As principais camadas do modelo TCP/IP são:

## Camada Física ou de acesso
São os protocolos mais ao fundo do cesto. Eles funcionam em conjunto com as peças do computador, cuidando do funcionamento mecânico das peças para que os programas de computador possam conversar livremente.

Na camada física encontramos:

- **Ethernet:** Um dos protocolos mais difundidos para redes locais com fio. Define como os dados são transmitidos em cabos de rede e como os dispositivos se comunicam na mesma rede local.
- **Wi-Fi (IEEE 802.11):** Define as regras para comunicação sem fio, permitindo que dispositivos se conectem a redes locais sem a necessidade de cabos, usando sinais de rádio.
- **Bluetooth:** Um protocolo de comunicação sem fio de curto alcance, usado principalmente para conectar dispositivos próximos, como fones de ouvido, teclados e alto-falantes a um dispositivo principal, como um smartphone ou computador.


## Camada de Rede
Subindo para o meio do cesto, temos a região com a responsabilidade de descobrir os endereços dos outros dispositivos, saber com quem o seu dispositivo está conversando.

Na camada de rede encontramos:

- **IP (Internet Protocol):** É o protocolo fundamental desta camada. Ele atribui endereços únicos, como números de uma residência, para dispositivos na rede e define por onde o  áudio da conversa deve circular até alcançar seu destino final.

## Camada de transporte
Está acima da *camada de rede* e você pode entender ela como o serviço de entrega de mensagens. Agora que seu dispositivo sabe como as peças da rede física funcionam e sabe com quem estamos tentando conversar, essa camada possui protocolos que garantem o fluxo da conversa, permitindo que a outra pessoa escute o que você fala e vice-versa.

Na camada de transporte encontramos:

- **TCP (Transmission Control Protocol):** É um dos principais protocolos dessa camada. Ele garante que a conversa não seja atrapalhada por outras conversas paralelas e que os dois dispositivos escutem bem o que o outro está falando. Se tem muito barulho e a conversa flui de modo compreensível, é esse protocolo que pede ao falante que repita as palavras novamente pois o destinatário não escutou corretamente.
- **UDP (User Datagram Protocol):** É um protocolo mais simples em comparação com o TCP. Ele é mais rápido, porém menos confiável, pois ele não se importa se os dois dispositivos estão compreendendo a conversa. O UDP só se importa em garantir que os dois lados estejam na mesma conversa. Esse protocolo é usado nas situações em que a velocidade é mais importante do que a precisão, como em videoconferências ou transmissões ao vivo.

## Camada de aplicação
É a camada que está no topo do cesto, próximo da borda. Os programas de computador que conhecemos funcionam, como o navegador de internet ou programa de e-mails. Os protocolos da camada de aplicação recebem os dados dos programas de computador e usam os protocolos mais abaixo do cesto para realizar transmissão das informações.  

Na camada de aplicação encontramos:

- **HTTP (Hypertext Transfer Protocol):** É o protocolo utilizado para transferir páginas da web e recursos associados, como imagens e vídeos, entre um servidor web (um computador distante na rede) e um navegador de internet. O HTTPS é a versão segura do HTTP, pois usa mensagens protegidas durante a conversa entre dispositivos.
- **SMTP (Simple Mail Transfer Protocol):** É usado para enviar e-mails entre programas de correio eletrônico. Define a forma como as mensagens são enviadas e entregues entre a origem e o destinatário.
- **FTP (File Transfer Protocol):** É utilizado para transferir arquivos entre computadores na internet. Facilita a transferência de arquivos, seja para upload (envio) ou download (recebimento).

## Conclusão
Sem esses protocolos, a comunicação entre computadores, celulares, tablets e outros dispositivos seria como um quebra-cabeça sem instruções - confusa e caótica. Graças a eles, podemos enviar e-mails, acessar sites, assistir a vídeos e fazer tantas outras coisas online de forma fácil e segura.

Os protocolos são o alicerce invisível da internet, tornando possível toda a magia que experimentamos online. São eles que nos permitem navegar na vastidão da web e se comunicar com o mundo ao nosso redor, tornando a internet tão incrível como conhecemos hoje!

```
Créditos.
As ilustrações desse post foram geradas por civit.ai.
Esse conteúdo foi construído com auxílio do ChatGPT em algumas partes e revisado por humanos.
```
