# Hyper Tickets
**Documentação de referência para o bot Hyper Tickets, desenvolvido para facilitar o gerenciamento de tickets no seu servidor.**

As principais funcionalides incluem:

- 💻 - *Painel para costumizar e enviar ticket.*
- 🏴 - *Dar acesso ao ticket para cargos específicos.*
- 📁 - *Acesso ao conteúdo inteiro do canal do ticket com arquivo de texto.*
- 🏷️ - *Ticket padrão sem necessidade de configuração.*

## Configuração inicial e como usar

Requisitos:

- Uma *key* para ativar o bot.
- O link de convite para o bot.

Se você tem todos esses requisitos, por favor siga os seguintes passos **na ordem:**

- Convide o BOT para seu servidor usano o link de convite.
- Use o comando `/activate` com a key. Se você digitou corretamente, o bot alertará que a key foi ativada com sucesso.
- Por favor leia mais informações sobre a key [abaixo](#keys).
- Use o comando `/expires` para checar quando sua key vai expirar. Esse comando pode ser usado no futuro quantas vezes você quiser.
- O BOT já está configurado e pode ser usado. Confira todos os comandos disponíveis na seção [comandos](#comandos).

## Keys

Keys são usadas para a ativação da aplicação. Confira a seguir informações essenciais sobre as keys:

- Você deve usar apenas uma key e **uma vez** por mês. Se você tem 2 ou mais keys, aguarde até 1 ou 2 dias antes da data de expiração da key para usar uma nova. Se você usar uma key e em seguida usar outra, isso não extenderá o prazo de expiração.
- Uma key funciona só uma vez. Se você tentar usar uma key usada, você vai receber uma mensagem de erro.
- O horário da expiração da key é de acordo com o horário de brasília. Se sua key expira em `22/12/2031`, e são `00:01` do dia `22/12/2031` no horário de brasília, sua key já expirou.
- Nenhum comando ou interação com o bot será possível se o seu servidor não estiver ativado com a key.

### Comandos com as keys

---

#### ⚙️ /activate - `key` 
Ativa o bot com uma key.

- `key` - A key que deve ser usada o bot seja ativado.

Exemplo:

`/activate [7Z8V-LIFO-2W5T]`

---

#### ⚙️ /expires 
Checa a data de expiração da key.

Esse comando não tem parâmetros.

---

## Observações

🚩 **ATENÇÃO!**

Detalhe muito importante sobre o comando **/configticket**:

Ao usar esse comando, aparecerá um menu intuitivo, onde você poderá personalizar o seu painel de ticket. A cada mudança feita, você deve pressionar o botão "Atualizar configurações" para que elas sejam atualizadas. **Além disso, existem algumas observações para o menu:**
  - Você não pode adicionar emojis padrões nas opções, apenas emojis únicos do seu servidor. Podem ser emojis animados.
  - Para adicionar quebras de linha, use o "\n". Por exemplo, digamos que você queira escrever:
    ```
    Por favor,

    Aperte no botão abaixo para abrir um ticket
    ```
    Você deve escrever da seguinte forma na descrição: "Por favor,\n\nAperte no botão abaixo para abrir um ticket". Note que aqui usamos duas quebras de linha:
   - ```
   Por favor, <- uma quebra de linha
   <- outra quebra de linha
   Aperte no botão abaixo para abrir um ticket
   ```
  - Uma imagem anexada ao ticket é opcional.


🚩 **ATENÇÃO!**

Nesta documentação, os comandos são referenciados da seguinte forma:

#### ⚙️ **/comando** - `parâmetro_1`, `parâmetro_2`, ...
Descrição do comando.

- `parâmetro_1` - Significado do parâmetro...
- `parâmetro_2` - Significado do outro parâmetro...

Exemplo:

Um exemplo de como usar o comando.

`/comando parametro_1 parametro_2`


## Comandos

---

##### ⚙️ /addcargo - `cargo`
Dá acesso ao ticket para membros do cargo especificado. Esse comando deve ser usado dentro do canal do ticket desejado.

- `cargo` - O cargo para qual esse comando deve ser aplicado. Um mini menu de seleção será aberto com os cargos disponíveis.

---

##### ⚙️ /configticket - `canal`
Abre uma tela para configurar seu painel de ticket personalizado.

- `canal` - O canal onde o painel de ticket será enviado. Uma pequena lista de canais irá aparecer e você deverá selecionar o canal.

---

##### ⚙️ /fecharticket
Envia um arquivo transcrito com todas as mensagens do ticket e deleta o canal.

Esse comando deve ser utilizado quando você pretende "fechar" o ticket. Ao usá-lo, todas as mensagens enviadas no canal do ticket serão reenviadas no seu privado dentro de arquivo .txt, e o canal do ticket será deletado.

---

##### ⚙️ /sendembed - `titulo`, `descricao`, `canal`, `emoji`, `link`, `msgbotao`
Envia um embed no canal escolhido.

- `titulo` - O título do Embed.
- `descricao` - A descrição do Embed.
- `canal` - O canal onde o Embed será enviado. Uma pequena lista de canais irá aparecer e você deverá selecionar o canal.
- `emoji` - O nome do emoji a ser mostrado no botão do Embed. Deve ser um emoji único do server, não pode ser um emoji padrão.
- `link` - O link que será aberto ao pressionar o botão do Embed.
- `msgbotao` - A mensagem a ser mostrada no botão do Embed. 

---

##### ⚙️ /ticket
Envia um menu padrão com a funcionalidade de ticket.

Envia um painel de ticket que já vem padronizado sem necessidade de configuração.

---

## Contato

- Email: miguelup01@outlook.com
- Servidor: [HyperStore](https://discord.gg/M7FURN5R88)
- Discord: miguelnto
