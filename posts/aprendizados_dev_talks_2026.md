No dia 07/11/2026 pude participar do [Dev Talks](https://devtalks.com.br/). Foi a minha primeira participação, e com certeza não será a última.

Pude encontrar ex-colegas de trabalho, além de conhecer pessoas novas e obter novos conhecimentos para ter um perfil profissional melhor desenvolvido.

# Começando o dia

Cheguei no evento as 07:50, com o evento previsto para iniciar as 08:00 e acabar as 18:00, porém como se não bastasse o tornado que afetou a cidade de Chapecó dia 04/11/2026, ainda houve uma leva de chuva que também chegou ao dia do evento, então além tomar um pouco de chuva saindo do carro, o evento atrasou 1h.

Logo que cheguei, fiz o credenciamento, os itens do evento foram bons, caderneta, caneta, porta itens, crachá e principalmente a bolinha anti-stress.

Também enalteço o café da [Brasitália](https://www.brasitaliacafe.com.br/) que estava bem bom e sustentando os devs de ressaca do deploy da sexta.

Durante as palestras, fiquei a maior parte do tempo acompanhado do [Gabriel Vivian](https://www.linkedin.com/in/gabrielvivian/) e do [Vicenzo Scalvi](https://www.linkedin.com/in/vicenzo-scalvi/)

# Segurança de Software Depois do Momento Mythos

Começando com o Fábio Olivé Leite, que trabalha na Red Hat a cerca de 20 anos, e atualmente está na área de segurança.

Já dando ponta, ele nos mostrou como a IA expôs muitas vulnerabilidades de uma vez, e como hoje em dia se um sistema for mal otimizado para ser seguro, ele demora segundos para ser explorado e atacado, principalmente usando o modelo Mythos da Antropic como exemplo.

Também deu dicas de como otimizar as ferramentas que já existiam antes como o Sonar para evitar falsos positivos, quais as diferenças no ambiente empresarial de ter essa estrutura elaborada no DevOps e os pontos positivos e negativos.

Uma das informações que mais agregou para mim foi descobrir a existência das CVE's (Common Vulnerabilities and Exposures), que são mais de 406.000 trechos que podem conter falhas implicitas e explicitas, desde as mais básicas até as mais críticas, como JWT versionado por exemplo. Todas catalogadas e com identificadores, isso vai mudar minha visão para próximos trechos de código.

Além é claro de ressaltar a importância da capacitação dos devs na área de cibersecurity, e com muitos sistemas feitos por IA, essa área tem uma tendência de bombar para os próximos anos.

Foi uma baita aula!

# GitLab e PostgreSQL: operando um dos maiores clusters do mundo

Seguindo para a palestra do Leonardo da Rosa, que nos mostrou um pouco da arquitetura do GitLab (o cara trabalha no GitLab, nossos commits assinaturas implicitas do cara), e curiosamente eu entendi pouca coisa, mas o pouco que entendi me ajudou a desenhar na minha cabeça um pouco de como a plataforma de versionamento realmente funciona.

Conforme um dos slides: "não é um cluster, é um ambiente", o GitLab dedica 103TB de armazenamento para os projetos, sendo 55TB só na main, também utilizando PostgreSQL 17 migrando para o 18.

Deixando 3 lições para levar no dia a dia:

- Otimizaar o básico antes de distribuir os dados;
- Planejar mudanças de banco como mudanças de produção;
- A escala trará novos trade-offs;

Também me trouxe a pesquisa de ir atrás do que é um cluster, aprendendo mais sobre uma das possíveis formas de hospedar sistemas, caso não saiba o que é um, confira [aqui](https://www.opservices.com.br/o-que-e-um-cluster/).

