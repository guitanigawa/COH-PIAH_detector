# Detector COH-PIAH
Este é um projeto-desafio bastante simples e enxuto que compõe o curso <a href="https://www.coursera.org/learn/ciencia-computacao-python-conceitos">**Introdução à Ciência da Computação com Python Parte 1**</a> , disponibilizado pela Universidade de São Paulo (USP) no Coursera. 
Apesar de tê-lo concluído ainda em 2021, decidi refazer esse desafio apenas para relembrar alguns conceitos básicos da linguagem Python.

### -> Projeto:
Consiste em identificar possíveis casos de plágio utilizando análise linguística. O programa compara textos fornecidos com uma assinatura pré-definida baseada em estatísticas como tamanho médio das palavras, relação Type-Token e complexidade de sentença. O objetivo é calcular o grau de similaridade e detectar qual texto tem maior probabilidade de ter sido escrito por um aluno infectado com COH-PIAH. O código que segue demonstra o funcionamento do programa:

```
Bem-vindo ao detector automático de COH-PIAH.
Informe a assinatura típica de um aluno infectado:

Entre o tamanho médio de palavra: 4.51
Entre a relação Type-Token: 0.693
Entre a Razão Hapax Legomana: 0.55
Entre o tamanho médio de sentença: 70.82
Entre a complexidade média da sentença: 1.82
Entre o tamanho médio de frase: 38.5

Digite o texto 1 (aperte enter para sair): Num fabulário ainda por encontrar será um dia lida esta fábula: A uma bordadora dum país longínquo foi encomendado pela sua rainha que bordasse, sobre seda ou cetim, entre folhas, uma rosa branca. A bordadora, como era muito jovem, foi procurar por toda a parte aquela rosa branca perfeitíssima, em cuja semelhança bordasse a sua. Mas sucedia que umas rosas eram menos belas do que lhe convinha, e que outras não eram brancas como deviam ser. Gastou dias sobre dias, chorosas horas, buscando a rosa que imitasse com seda, e, como nos países longínquos nunca deixa de haver pena de morte, ela sabia bem que, pelas leis dos contos como este, não podiam deixar de a matar se ela não bordasse a rosa branca. Por fim, não tendo melhor remédio, bordou de memória a rosa que lhe haviam exigido. Depois de a bordar foi compará-la com as rosas brancas que existem realmente nas roseiras. Sucedeu que todas as rosas brancas se pareciam exactamente com a rosa que ela bordara, que cada uma delas era exactamente aquela. Ela levou o trabalho ao palácio e é de supor que casasse com o príncipe. No fabulário, onde vem, esta fábula não traz moralidade. Mesmo porque, na idade de ouro, as fábulas não tinham moralidade nenhuma.

Digite o texto 2 (aperte enter para sair): Voltei-me para ela; Capitu tinha os olhos no chão. Ergueu-os logo, devagar, e ficamos a olhar um para o outro... Confissão de crianças, tu valias bem duas ou três páginas, mas quero ser poupado. Em verdade, não falamos nada; o muro falou por nós. Não nos movemos, as mãos é que se estenderam pouco a pouco, todas quatro, pegando-se, apertando-se, fundindo-se. Não marquei a hora exata daquele gesto. Devia tê-la marcado; sinto a falta de uma nota escrita naquela mesma noite, e que eu poria aqui com os erros de ortografia que trouxesse, mas não traria nenhum, tal era a diferença entre o estudante e o adolescente. Conhecia as regras do escrever, sem suspeitar as do amar; tinha orgias de latim e era virgem de mulheres. 

Digite o texto 3 (aperte enter para sair): Senão quando, estando eu ocupado em preparar e apurar a minha invenção, recebi em cheio um golpe de ar; adoeci logo, e não me tratei. Tinha o emplasto no cérebro; trazia comigo a idéia fixa dos doidos e dos fortes. Via-me, ao longe, ascender do chão das turbas, e remontar ao Céu, como uma águia imortal, e não é diante de tão excelso espetáculo que um homem pode sentir a dor que o punge. No outro dia estava pior; tratei-me enfim, mas incompletamente, sem método, nem cuidado, nem persistência; tal foi a origem do mal que me trouxe à eternidade. Sabem já que morri numa sexta-feira, dia aziago, e creio haver provado que foi a minha invenção que me matou. Há demonstrações menos lúcidas e não menos triunfantes. Não era impossível, entretanto, que eu chegasse a galgar o cimo de um século, e a figurar nas folhas públicas, entre macróbios. Tinha saúde e robustez. Suponha-se que, em vez de estar lançando os alicerces de uma invenção farmacêutica, tratava de coligir os elementos de uma instituição política, ou de uma reforma religiosa. Vinha a corrente de ar, que vence em eficácia o cálculo humano, e lá se ia tudo. Assim corre a sorte dos homens.

Digite o texto 4 (aperte enter para sair):

O autor do texto 2 está infectado com COH-PIAH
```
