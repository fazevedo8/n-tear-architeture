# n-tear-architeture
Abordagem a arquitetura de N camadas
https://medium.com/@felipe.azevedoit/n-tear-arquitetura-em-camadas-e8035ee2e0ee


Será que o velho BOLOVO voltou a moda?

Quem trabalha com desenvolvimento .net a bastante tempo vai se lembrar como inicialmente eram abordadas as questões arquiteturais dos projetos.
Criávamos projetos em N camadas, mas priorizando separar entidades de negócios e de acesso a dados, com o intuito de tornar sempre nosso desenvolvimento mais legível, reunitilizavel etc...
Ao decorrer dos anos, foram surgindo novas abordagens, tais quais os paterns Gof, mas principalmente implementações de certa forma equivocadas do bom e velho DDD.
Acredito não ser o único a ter enfrentado problemas com essas brigas arquiteturais, pois criávamos muitas complexidades em desenvolvimentos que aparentemente poderiam ser simples, famoso matar formiga com basuca.
Costumo dizer que a arquitetura de um projeto depende de diversos fatores, principalmente do negócio, pois sempre será o negócio a ditar as regras dentro de um orçamento especifico.
Quando criávamos projetos com BLL DAO e VO, de certa forma as coisas se perdiam, mas da mesma forma elas se perdem dentro de outras abordagens, por isso ao meu ver o mais importante não é só a arquitetura que se desenha para solucionar o problema, mas também a forma como isso será gerida, isso é muito mais importante.
Os ciclos se repetem na vida, é muito comum lá fora vermos essa abordagem que hoje dispõe de novos recursos para diminuir o acoplamento e a possibilidade de amplicar as camadas para camadas de patern’s estruturais.
Bom segue minha abordagem sobre o assunto:
 

Podemos concluir que as vezes as soluções simples do passado superam o tempo e podem contribuir com o presente. Antigamente não tínhamos todos os recursos para pensarmos de maneira desacoplada, ou abordagens de reais separações de contexto, ou uma infra escalável e disponível, são outros tempos, mas a boa e velha N-Tears parece estar voltando a ser utilizada principalmente em abordagem de micros serviços onde é necessário pensar em uma manutenção enxuta.
