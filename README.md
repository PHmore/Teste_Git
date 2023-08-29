Esse é um modelo de uso do git flow para que seja feito um bom e entendivel network graph 

Aparentemente é necessário criar commits até 2 branches anteriores a mudança (não há certeza ainda)

Quando se é deletado se for feito um merge e um git vazio com sucesso o network graph no github continua mesmo que a branch tenha sido derrotada

Após fazer um merge ou criar uma commit é necessário fazer um commit vazio na branch pai ou a que está recebendo o merge antes de fazer o push

Aparentemente a manipulação de branches como merge ou criação é necessário uma sempre fazer um empty commit antes para que não se perca o gráfico 

Ainda há inconsistencias com o gráfico quando o merge é feito ou seja acho que precisa ser atualizado as branches que receberão as merges

Comando de commit vazio:
git commit --allow-empty -m "Mensagem commit vazio"

Ensinamento básico