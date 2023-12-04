# Hyper Tickets
Documentação de referência para o bot Hyper Tickets, para gerenciar tickets no seu servidor.

`Vídeo de demonstração usando o BOT:` https://www.youtube.com/watch?v=iF2a5R0Oir4

##### `/activate` - Ativa o servidor com a key.

O comando deve ser usado com uma key **válida**, para que o BOT fique disponível para uso. Esse comando deve ser usado apenas **UMA VEZ POR MÊS**. Usar várias keys de forma seguida não vai aumentar o tempo de funcionamento do BOT, você deve reativar todo mês.

##### `/expires` - Mostra a data de expiração da última key usada.

Esse comando não requer nenhum parâmetro. Para mais informações, olhe a seção **Keys.**

##### `/addcargo` - Dá acesso ao ticket para membros do cargo.

O comando deve ser usado passando um cargo. Todos os membros que possuirem esse cargo vão ter acesso ao canal do ticket.

##### `/configticket` - Abre uma tela para configurar um painel de ticket personalizado.

Ao usar esse comando, aparecerá um menu intuitivo, onde você poderá personalizar o seu painel de ticket. A cada mudança feita, você deve pressionar o botão "Atualizar configurações" para que elas sejam atualizadas. **Além disso, existem algumas observações para o menu:**
  - Você não pode adicionar emojis padrões nas opções, apenas emojis únicos do seu servidor. Podem ser emojis animados.
  - Para adicionar quebras de linha, use o "\n". Por exemplo, digamos que você queira escrever:
    ```
    Por favor,

    Aperte no botão abaixo para abrir um ticket
    ```
    Você deve escrever da seguinte forma na descrição: "Por favor,\n\nAperte no botão abaixo para abrir um ticket". Note que aqui usamos duas quebras de linha:
```
Por favor, <- uma quebra de linha
 <- outra quebra de linha
Aperte no botão abaixo para abrir um ticket
```
  - Uma imagem anexada ao ticket é opcional.

##### `/fecharticket` - Envia um arquivo transcrito com todas as mensagens do ticket e deleta o canal.

Esse comando deve ser utilizado quando você pretende "fechar" o ticket. Ao usá-lo, todas as mensagens enviadas no canal do ticket serão reenviadas no seu privado dentro de arquivo .txt, e o canal do ticket será deletado.

##### `/sendembed` - Envia um embed no canal escolhido.

Esse comando tem 6 paramêtros para serem passados: O título do Embed, a descrição, o canal onde será enviado, o emoji (opcional), o link que será contido no botão do Embed, e o título do botão (intitulado msgbotao).

##### `/ticket` - Envia um menu padrão com a funcionalidade de ticket.

Envia um menu que já vem padronizado com um ticket sem necessidade de configuração.

## Keys

Keys são usadas para a ativação da aplicação. Confira a seguir informaçãoes essenciais sobre as keys:

- Você deve usar apenas uma key e **uma vez** por mês. Se você tem 2 ou mais keys, aguarde até 1 ou 2 dias antes da data de expiração da key para usar uma nova. Se você usar uma key e em seguida usar outra, isso não extenderá o prazo de expiração.
- Uma key funciona só uma vez. Se você tentar usar uma key usada, você vai receber uma mensagem de erro.
- O horário da expiração da key é de acordo com o horário de brasília. Se sua key expira em `22/12/2031`, e são `00:01` do dia `22/12/2031` no horário de brasília, sua key já expirou.
- Nenhum comando ou interação com o bot será possível se o seu servidor não estiver ativado com a key.

## Contato

- Email: miguelup01@outlook.com
- Servidor: [HyperStore](https://discord.gg/M7FURN5R88)
- Discord: miguelnto
