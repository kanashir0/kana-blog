# Google Cloud Day Lisbon 23

## Principais pontos técnicos comentados

### Contas de serviço únicas
No GCP é possível alcançar uma boa granularidade de controle de acessos utilizado ***service accounts*** (SA), e isso só é possível quando se cria uma SA para cada recurso utilizado (Ex: Um grupo de VMs onde cada VM possui sua própria SA). 

**E por que isso é importante?:** Quando nós temos cada recurso com sua própria SA, é possível saber exatamente qual recurso está passando através de uma liberação de acesso no IAM, ou então em uma regra de firewall, evitando que permissões sejam dadas para recursos inesperados. Pois quando muitos recursos compartilham uma mesma conta, normalmente essas contas acabam acumulando múltiplas tarefas, e consequentemente múltiplas permissões para conseguir realizar essas tarefas, gerando uma grande dificuldade em dar manutenção nessa SA, pois você perde o controle de quais permissões realmente são utilizadas/necessárias para aquela SA, já que ela realiza uma monte de tarefas diferentes.

### Infraestrutura como código (IaC)