# Shipay Product Owner Assistant - Chalenge

### 1) Leia abaixo a descrição de uma API para desenvolvimento da integração entre um sistema de frente de caixa (PDV) com um gateway de pagamentos digitais: 

#### [GET /carteiras]: Lista de carteiras digitais disponíveis na loja 

> "Este serviço retorna todas as carteiras digitais que estejam disponíveis no estabelecimento comercial.
>
> Este serviço deve ser chamado pelo PDV sempre antes de enviar um pedido para o gateway. A ideia é que o PDV exiba na tela a lista de carteiras disponíveis e o operador de caixa selecione a carteira informada pelo comprador.
> 
> (...)"


Como complemento ao trecho da documentação acima, assista à esse vídeo e veja como o **[GET /carteiras]** funciona na prática: https://www.youtube.com/watch?v=19PTw_9pJX0 (no vídeo, o **[GET /carteiras]** é chamado no trecho a partir de 0:31).


Agora que você já conhece o serviço **[GET /carteiras]** do gateway de pagamentos, analise a seguinte situação:


> **O sistema de PDV XPTO está desenvolvendo a integração com as APIs do gateway e deu este feedback:**
>
> "Seria muito interessante para nosso sistema XPTO se o serviço **[GET /carteiras]** nos retornasse, além do nome das carteiras disponíveis no estabelecimento, também uma imagem com o logo de cada uma das carteiras para exibir na tela do sistema de PDV e melhorar a experiência do operador de caixa."


- Escreva uma user-story para que o time de desenvolvimento possa densevolver essa melhoria na próxima sprint:

-> 

---

### 2) Na tela de Login do Painel Shipay existe a funcionalidade "Esqueceu a senha?". Veja nas imagens "02-esqueceu_senha.png" e "02-redefinicao_senha.png" como ela funciona.

- Supondo que essa funcionalidade acabou de ser entregue pelo time de desenvolvimento, quais testes você faria para validar essa nova funcionalidade? 

-> 

---

### 3) Precisamos atualizar nossa documentação para incluir uma nova forma de "confirmação de pagamento" (chamada de *"callback"*) no fluxo de criação de pedidos e confirmação de pagamentos através das APIs da Shipay. Veja o fluxo anterior e o novo fluxo nas imagens:

> 03-fluxo_anterior.png -> **Fluxo anterior:** a confirmação do pagamento é feita de forma ativa pelo sistema integrado à Shipay
>
> 03-fluxo_callback.png -> **Novo fluxo:** o sistema integrado à Shipay recebe de forma passiva a confirmação do pagamento (*callback*)

- Considerando que o "CALLBACK" é um estímulo que a Shipay envia para o sistema parceiro integrado quando o pagamento é confirmado, descreva o novo fluxo. Utilize a descrição dos passos do "Fluxo anterior" como base.

-> 

