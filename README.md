# Estrutura-de-Dados
Colocar arquivos de Ed para facilitar estudos

1- em fila_circ, descobrir e corrigir o problema do Item void pointer ===>> RESOLVIDOOO

2- Descobrir um meio de percorrer com eficiência os elementos das lista ---> FEITO <3 Rodrigo god 
    * criar novo void pointer que retorna a celula (typedef void* Cell) 
    e utilizarm no getFirst ===> RESOLVIDOOO
    * extrair e montar as figuras em svg.c ===> RESOLVIDOOO
    ---> FEITO  Rodrigo god sagrado divino

3- Nos arquivos de circulo, retangulo, linha e texto os valores extraidos do geo funcionam corretamente, fora dali fica tudo estranho  ====> RESOLVIDO
    * ver em geo.c
    * ver em svg.c (nas funções get)

4- Concatenação de geo e qry para gerar nome do svg ===> RESOLVIDO

5- Descobrir e arrumar erros na criação do txt pós qry ==> RESOLVIDO

6- Quando roda com o qry exibir tambem o svg puro, junto com o svg pos qry e o txt  ==> RESOLVIDO

==================================================================================================

 * Próximo passo: continuar a implementar o .qry ;-;
    -> arrumar os comando UPS, POL, SEL+
      * em pol "SO" falta fazer as linhas de preenchimento
      * em ups talvez esteja bem merda  ==> Parece que funciona mas não confio muito nele
      * em sel+ ta igual a sel ??? Devo considerar as areas selecionadas anteriormente e comparar com um grandee retângulo  ==> Parece que funciona mas não confio muito nele
    -> arrumar seg fault em DELS (URGENTE!!!) e talvez remover as figuras selecionadas do svg ==> resolvido? 

./ted -e /home/marcotuiio/ED1/EDor/T1/input -f vaso.geo -o /home/marcotuiio/ED1/EDor/T1/output -q vas.qry

./ted -e /home/marcotuiio/ED1/EDor/T1/input -f escada.geo -o /home/marcotuiio/ED1/EDor/T1/output -q esc.qry

./ted -e /home/marcotuiio/ED1/EDor/T1/input -f casa.geo -o /home/marcotuiio/ED1/EDor/T1/output -q ca.qry

./ted -e /home/marcotuiio/ED1/EDor/T1/input -f hino2.geo -o /home/marcotuiio/ED1/EDor/T1/output -q h2.qry

./ted -e /home/marcotuiio/ED1/EDor/T1/input -f espiralv2.geo -o /home/marcotuiio/ED1/EDor/T1/output -q esp02.qry

./ted -e /home/marcotuiio/ED1/EDor/T1/input -f hino.geo -o /home/marcotuiio/ED1/EDor/T1/output -q h1.qry

!!!PEDIR AJUDAR SEGUNDA PRO PROFESSOR EM POL(LINHAS INTERNAS), SEL+(TA CERTO?), UPS(TA CERTO?)!!!