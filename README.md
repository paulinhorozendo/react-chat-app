# Realtime Chat App em ReactJS e NodeJS | Socket.io 
## Wassup! 
- Aplicativo de bate-papo em tempo real completo utilizando o React no front-end, com a biblioteca web socket NodeJS + Socket.io no back-end.
- Essa build fornece um bom entendimento de como enviar e receber mensagens usando web sockets e Socket.io para fazer qualquer aplicação em tempo real.
- Sem dúvidas a utilização de apps de mensagens hoje em dia é fundamental para a comunicação em forma de textos, áudios, imagens e até mesmo vídeos.
- Por isso a construção desse tipo de app é um desafio e ao mesmo tempo uma ótima forma de estudo para entender melhor a integração entre Client e Server.
- E pra que isso seja feito de uma forma otimizada e funcional, o Node tem integração direta e fácil utilizando Socket.io.
- Socket.io é uma implementação em Node para web socket, ou seja, uma forma de fazer comunicação em tempo real, e mais importante que isso é sua possibilidade de fallBack. 
- Comunicação cliente-servidor em tempo real com Socket.IO
- O Socket.io é uma das melhores opções para comunicação em tempo real quando utilizamos o Node. Outra coisa muito importante é o fato de poder integrá-lo a outros Stacks, como em uma aplicação feita em PHP, Java, etc. E o mais interessante é que é possível fazer com autenticação e tudo mais.
- O Socket.io também é muito fácil de escalar, como é em tempo real, o chamamos de IO intensive, ou seja, acontece muito IO quando estamos utilizando o mesmo.
Exemplo: Por algum motivo seus clientes que estão se conectando ao Socket.io não têm suporte ao web Socket, então ele vai tentar outras maneiras (não tão performáticas como AJAX). Nesta situação, o Node se destaca de outras tecnologias, pois ele suporta mais usuários.
- ## Modus Operandi
- O acesso foi feito utilizando o "http://localhost:3001", onde no layout da aplicação é possível escolher um nome de usuário e uma ID de acesso a sala de bate-papo.
- É importante que seja usado o mesmo ID para que os usuários utilizem a mesma sala. Se algum usuário errar a ID ou digitar uma diferente, ele automaticamente cria outra sala, então para que 2 ou mais usuários utilizem uma mesma sala é necessário que todos digitem a mesma ID.








![chat](https://user-images.githubusercontent.com/81476932/168676480-9676fedc-668a-4715-9a03-f1adeab07d79.png)
