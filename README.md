# Proposta de processo de desenvolvimento Ágil

Primeiramente:

> Não criar solução onde não existe problema

Cada projeto possui suas peculiariedades e problemas para resolver, então esse artigo se propõe a ser apenas uma base e ideias para problemas comuns de projetos de desenvolvimento de software.

## 1. Problemas comuns

- Entregas demoram mais de uma sprint
- Resolução de problemas (issues) demoradas
- Desenvolvedores novos da equipe tem rendimento muito inferior por muito tempo
- Contribuições no projeto não fucionam
- Equipe não está engajada
- Os problemas somente são resolvidos quando há reclamação

## 2 Entregas demoram mais de uma sprint

Um bom exercício mental para se fazer em várias situações, principalemente matemáticas, é extrapolar um dos valores da equação e ver para caminho vai o resultado e se ele é satisfatório. Aplicando isso ao desenvolvimento Ágil, temos que o desenvolvimento de uma tarefa demora mais do que 1 sprint. Se extrapolarmos esse "+ de 1" para "20" e refazermos a frase, "o desenvolvimento de uma tarefa demora 20 sprints", isso continua sendo certo no desenvolvimento Ágil? Uma sprint é o certo, duas sprints é menos certo, 20 menos ainda, ou seja... A certeza que temos é que se a tarefa for entregue em uma sprint, considerando só o tempo, foi uma entrega Ágil.

Uma tarefa que demora mais tempo para ser entregue é um problema baseado em outros problemas menores, muitos deles ferindo os princípios do Ágil. Alguns deles:

- Pequenas entregas de valor;
- Preciosismo na primeira entrega;
- Processos.

### 2.1 Pequenas entregas de valor

Depois de dar nome as coisas a segunda pior tarefa é conseguir quebrar tarefas em atividades menores. Essa trabalho normalmente precisa ser feito em conjunto das partes interessadas para que haja um pequena negociação do mínimo entregável. Alguns pontos devem ser considerados para se descobrir o mínimo entregável:

- O que é o mínimo entregável para alguém se beneficiar?

A partir do momento que sua entrega já tem valor para alguém, não precisa estender mais aquela tarefa, pois ela pode ser entregue, validada e posteriormente continuada. Um exemplo claro disso é na resolução de um problema, a solução não precisa no primeiro momento ser perfeita, precisa resolver a dor de quem está esperando. Isso de solução perfeita leva a outro ponto.

### 2.2 Preciosismo na primeira entrega

Esse problema geralmente é um sinal de que a equipe tende a não revisitar as entregas anteriores, ou seja, se foi mal feito fica mal feito para sempre, aí algum dia simplesmente é decido que aquilo vai fora e será feito algo melhor no lugar. Tal forma de agir não é progressiva e escalável, pois de tempos em tempos as _features_ serão refeitas sem que muitas vezes carreguem consigo o histórico de problemas resolvidos, onde a nova versão seja um progresso estrutural, porém um retrocesso na quanto a _bugs_ e pessoas beneficiadas, porque ao refazer nem sempre consegue-se separar o que era útil do que estava obsoleto.

Outro temor de uma entrega de menor qualidade, longe do perfeito, é que aquilo não será escalável, o que é uma verdade se a escalabilidade não for uma preocupação. Em primeiro momento se precisa entender se algo depende daquela entrega ou se ela é um ponto final de algo. Existem tarefas que começam e acabam em si mesmas, por exemplo uma _landing page_ promocional que é única, nada depende dela, ela não será melhorada no futuro, então não haveria motivo de segurar sua entrega por preocupações de qualidade referente a sua escalabilidade. Já uma entrega de um template de e-mail que com o tempo evolui, ganha novas derivações, este deve-se ter uma preocupação de ser reutilizável, feito de uma forma genérica e provavelmente quebrado em componentes menores.

Um bom primeiro passo para garantir que a entrega possa escalar, é a definição do que será dependende em entregas futuras. Definição de nomenclatura

Outro ponto importante para a escalabilidade é seguir o [Princípio da Responsabilidade Única](#) para que a manutenção daquela entrega não seja onerosa, por exigir que quem a faça tenha que mexer em várias partes do projeto para conseguir fazer uma alteração.
