# Técnico
**Vizualizer como é o funcionamento do aplicativo do tecnico**
***

<!-- ## Instalação  -->

##                  
**Cadastre um questionário para que o tecnico possa realizar**

**No milkroute web acesse à abá de cadastro e selecione questionário**
***

### Cadastrar Novo questionário

![](./img/tecnico/cadastro.jpg)

##### **Campos para Preencher :**

* `Descrição` - Permite informar a descrição do questionátio.
* `Data Inicio` - Permite inserir a data de inicio de uso do questionário
* `Data Fim` - Permite informar a data máxima de uso do questionário

![](./img/cadastros/questionario1.png)

#### **Cadastrar Categoria**

* `Descrição` - Permite inserir um nome para a categoria

![](./img/tecnico/categoriaCadastro.jpg)
***
#### **Cadastrar Perguntas para Categoria :**

![](./img/cadastros/questionario2.png)

###### **Principais campos para preencher :**

* `Descrição` - Permite informar a descrição de referência para a pergunta.
* `Tipo de Resposta` - Permite informar o tipo de resposta para essa pergunta, sendo elas:
    - Escolha Uma: permitirá que a pergunta tenha somente uma resposta, por exemplo: Sim ou Não.
    - Multipla Escolha: permitirá que a pergunta aceite mais de uma resposta.
    - Texto: permitirá que a pergunta aceite uma resposta de texto curto.
    - Combo: permitirá que o técnico selecione uma das respostas parametrizadas.
    - Data: permitirá que a pergunta aceita somente data como resposta.
* `Ativa` - Caso desativado a pergunta não irá aparecer no questionário
* `Tamanho Máximo` - Permite definir um tamanho máximo de resposta para essa pergunta, utilizado em perguntas do tipo texto, caso contrário pode definir como zero.
***

#### **Incluir Respostas**

![](./img/tecnico/incluirPergunta.jpg)

###### **Campos para preencher :**

* `Descrição` - Informe uma descrição para a resposta| **"Um nome para ser mais especifico"**
* `Valor Resposta` - Permite Inserir um valor de respotas, sendo elas
    - Escolha uma: o valor deve ser **true** para positivo ou **false** para negativo
    - Multipla escolha: o valor deverá ser **"text"**
    - Texto: o valor deverá ser **"text"**
    - Combo: o valor deverá ser **"text"**
    - Date: o valor da respota deverá ser **"date"**
* `Cor` - Defina uma cor para agradar a visualização da resposta
* `Ativa` - caso está opção esteja desativada a resposta não aparecerá

![](./img/tecnico/op%C3%A7%C3%A3oPergunta.jpg)
***
## Tecnico
**Tenha um tecnico cadastrado para que possa definir seus questionários**

**No milkroute web vá em basico e acesse o campo tecnico**
***
Selecione um tecnico e clique na opção para alterar
![](./img/tecnico/ess.jpg)

**Selecione um questionário desejado clique na seta unica para enviar esse questionário escolhido, caso deseja mandar mais de um questionário é possivel, caso queria manda todos de uma só vez clique na seta dupla, clique nas setas em suas respectiva direção para mandar onde quiser**
***
## Mapa Visita
**Cadastre uma agenda para a visitas dos tecnicos**

#### **Nova Visita**

![](./img/tecnico/novaVisita.jpg)

###### **Campos para preencher :**

* `Questionário` - Selecione qual questionário será usado na visita
* `Propriedade` - Informe o nome da propriedade

![](./img/tecnico/cadastroVisita.jpg)

Appós criar uma nova visita, uma listagem de todos os itens aparecerá
![](./img/tecnico/listagem.jpg)
***

![](./img/tecnico/set1.jpg)

**Vizualizar observações e recomendações** 
***

![](./img/tecnico/set2.jpg)

**Exibir respostas**
***

![](./img/tecnico/set3.jpg)

**Opção para baixar um pdf sobre as informações da visita**
***
## Aplicativo
**O app tem a função da visita do tecnico, ele sera usado no momento da visita**
***
### Visitas

![](./img/tecnico/visitasBot%C3%A3o.jpg)

![](./img/tecnico/visitasPage.jpg)

**Ao acessar a pagina, mostrará todos as visitas que devem ser feitas**

* `Visitas em azul` - Todas as visitas que tiverem em azul estão confirmada
* `Visitas em amarelo` - Todas as visitas que tiverem em amarelo são vistas solicitada
* `Visitas em cinza claro` - Todas as visitas que estiverem com uma cor acizentada são visitas agendada
* `Vistas em branco` - Todo tipo de visita que estiver em branco são visitas em andamento

**Ao clicar no ponto de interrogação na parte superior da pagina, uma mensagem será exibida**

![](./img/tecnico/mensagem.jpg)

- Pressione uma visita para iniciar
- Segure pressionado para reagendar uma visita
- arraste para o lado para cancelar um agendamento

![](./img/tecnico/XRecorder_Edited_17112022_135816_AdobeExpress%20(2).gif)
***
### Nova Visita
<br>
![](./img/tecnico/novaVisitaAPP.jpg)

**Ao clicar na opção de nova visita, você será redirecionado para uma nova abá onde você deve colar o nome da propriedade para a visita**

![](./img/tecnico/visitaAgendada.jpg)

**Selecione a visita para ser iniciada, ao clicar uma mensagem aparecerá se deseja iniciar o preenchimento do questionario, ao inicar você sera redirecionado para uma nova abá com informações da visita, recomendações e observações**

![](./img/tecnico/vamosComecar.jpg)

**Ao ler as recomendações e observações passe para continuar o questionario**

**!!!OBS: Todas as perguntas e categorias do questionario são apenas para demonstração, elas não serão iguais a que aparecerão em seu aplicativo**

![](./img/tecnico/questionario.jpg)

!!!A imagem acmia demostrar perguntas de escolha unica, selecione a opção mais adequada para a pergunta

##### **Exemplo de Resposta:**

![](./img/tecnico/exResposta.jpg)
***
#### **Outros Exemplos de Resposta :**
<!-- <br> -->
###### **Resposta de Multiplas Escolhas**

![](./img/tecnico/multiplaEscolha.jpg)

###### **Resposta Combo**

![](./img/tecnico/combo1.jpg)

![](./img/tecnico/combo2.jpg)

###### **Resposta com apenas Numeros**

![](./img/tecnico/respostaNumero.jpg)
***
##### **Resposta com apenas Datas**

![](./img/tecnico/data.jpg)

**!!Ao clicar uma abá para você escolher a data aparecerá**
***

### Finalizar

**Após preencher todos os campos, só resta finalizar**

###### **Video de Exemplo para tutorial :**
<!-- ![](./img/tecnico/visitaAgendada_AdobeExpress.mp4) -->
<video width="350" height="300" controls muted poster="../img/tecnico/testePoster.png">
  <source src="../img/tecnico/visitaAgendada_AdobeExpress.mp4" type="video/mp4" >
  <!-- <source src="movie.ogg" type="video/ogg"> -->
</video>

<br>

### Visita Imprevista
**Caso tenha que realizar um visita imprevista basta acessar nova visita inserir o nome da propriedade e arrastar para o lado na opção visita imprevista e selecione qual questionario será usado para essa visita imprevista, após selecionar siga os mesmos passos de uma visita agendada**

###### **Video de Exemplo :**
<!-- ![](./img/tecnico/visitaImprevistaVideo_AdobeExpress.mp4) -->
<video width="350" height="300" controls muted poster="../img/tecnico/testePoster.png">
  <source src="../img/tecnico/visitaImprevistaVideo_AdobeExpress.mp4" type="video/mp4">
  <!-- <source src="movie.ogg" type="video/ogg"> -->
</video>