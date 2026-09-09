# O Começo

Recemente, tive um interesse temporário muito forte por desenvolvimento de sistemas com Python, desde que comecei a estudar essa tecnologia, tanto no estágio onde estou atualmente, quanto em cursos da Alura, a linguagem se mostrou uma forte aliada para o desenvolvimento de apps desktop.

Como futuramente pretendo fazer projetos de aprendizado que quero usar na minha vida pessoal, o desenvolvimento desktop está indo de forma bem interessante.

O Python é uma linguagem muito boa para se trabalhar, principalmente nas seguintes ocasiões:

- Quando já tem experiência com linguagens de programação mais robustas e de baixo nível.
- Quando se pretende trabalhar com análise de dados e inteligência artificial.
- Quando a solução tem um escopo mais reduzido e não precisa atender demandas 24/7 (API de SaaS por exemplo).

Por ser uma linguagem interpretada, essa cobrinha tende validar muita coisa que não era pra ser válidado, o código compila, mas na hora da execução quebra. A versatilidade é o principal diferencial, da pra fazer APIs, apps desktop, apps mobile, automação... De tudo, então vale a pena aprender sim, mas considere o escopo do que você quer fazer.

# A Ideia: Teto

Depois de fazer alguns projetos e estudos na linguagem, busquei principalmente aplicar meus conhecimentos.

No brainstorming que fiz para decidir no que gostaria de focar inicialmente, lembrei de algo que ocorre aqui em casa, goteiras no telhado.

Faz um tempo que eu e meu pai tentamos desvendar o mistério por trás das goteiras que tenho no meu quarto, até hoje ainda sofro com elas, é um pé no saco. Subimos no telhado para verificar os possíveis locais com vazamento, sendo que as telhas estão ficando antigas... um piso em falso e caimos de 3 a 4 metros varando o telhado e o forro da casa... junto disso, remendo em possíveis infiltrações, analisado a possibilidade da troca das telhas, passar uma massa em cima...

Nisso, me acendeu uma lâmpada na cabeça.

> Por quê não comprar um drone, e fazer a análise do telhado com IA?

É uma ideia que eu jurava que ia desenvolver super bem de primeira, parecia perfeito na minha cabeça.

- Seguro.
- Desafiador.
- Inovador.
- Motivador.

Em março de 2025, tive o privilégio de participar na edição **Construtech** do SW Chapecó, muito do pouco que eu sei sobre construção civil eu aprendi lá. Como a proposta da nossa equipe era algo parecido, eu escolhi adaptar e replicar essa ideia.

Nessa mesma edição, eu soltei um "balão" entre meus colegas de faculdade, na minha visão maravilinda e simples na hora do pitch, o produto final teria **integração com 3 modelos treinados de IA para a análise dos patogenos das construções**. Totalmente desnecessário, apesar de com o conhecimento que tenho hoje saber que isso é possível, não muda o fato que seria exagerado, só em consumo de token a análise ia ser mais cara do que as manutenções... Ainda bem que aprender com o tempo é arte.

Que fique bem claro que esse foi um detalhe feito por um dev em começo de carreira que seria revisado e provavelmente ajustado, **o total da ôpera estava muito bem feito**, foi uma ideia digna do segundo lugar.

# Desenvolvimento

Toda a parte técnica pode ser avaliada nos meu repositórios públicos:

- TetoAPI
- TetoDesktop

Um é uma API, que contaria com a análise de no máximo 3 imagens por modelo, e outro o aplicativo que consumiria dessa API, desenhando nas imagens com base nas marcações dos poligonos retornados pela análise, junto da análise do telhado, pontos de desgate, de possíveis infiltrações etc...

Ao construir o projeto ao longo dos dias, fui percebendo que a partir de determinado ponto, precisaria de imagens precisas para trabalhar com a IA, o que me levou a considerar uma primeira operação com o drone para poder validar a qualidade da imagem, o que poderia dar errado na operação... E ai houve uma **falha** que acabou **tornando inviável a continuação da ideia**.

# A perda

[video]
https://res.cloudinary.com/diizw3dqm/video/upload/v1788912473/night_wpjwsw.mp4
[/video]

*Os vídeos estão em 720p, infelizmente é a melhor qualidade disponível nesses vídeos para upload no Cloudinary*

Esse primeiro vídeo é eu levantando voo com ele após ele chegar, pratiquei com ele por cerca de 2 dias levantanto e andando devagar pela área da minha casa, e nesse 2 dia de prática, durante a noite, pude botar ele para voar sobre a nossa casa, por mais que estivesse escuro, deu para realizar o voo com sucesso.

Nesse dia (sábado) eu peguei confiança que tinha conseguido o básico para poder fazer uma operação simples de tirar as fotos do telhado, pois em velocidade média e com um pouquinho de vento ainda sim ele voou e voltou, no outro dia (domingo) eu iria testar pra valer.

[video]
https://res.cloudinary.com/diizw3dqm/video/upload/v1788912468/fail_b4gjai.mp4
[/video]

Esse é o segundo e último vídeo do drone sob minha posse, conforme a gravação, até a parte de elevar o drone sob o telhado estava controlado, mas depois que ele ganhou certa altura... tudo foi pelo ralo.

O vento estava um pouco forte, mas como no dia anterior com velocidade média tinha dado boa, confiei na força do drone, mas a soma dos fatores:

- Vento forte;
- Perca de sinal.

Fizeram o drone se desordenar, ele foi sendo levado pelo vento mesmo com força total, e junto disso, a medida que ia sendo levado, perdia a conexão com o controle.

Em questão de 2 a 3 minutos ele caiu no meio da quadra ao lado, em algum lugar no meio de casas e mata que eu nunca vou saber, tentei ir atrás do mais próximo que tinha visto onde poderia estar, mas se foi.

Pra me ajudar, meu tio tinha vindo tirar umas férias, lá de Blumenau pra Chapecó, obviamente ele não ia perder a chance de me incomodar depois dessa façanha, pro resto da vida fica registrado a perca do drone e a zoação, mas faz parte.

O drone era um dos mais baratos e simples, R$130,00 na Amazon, dentro do orçamento era o que dava, e assim como veio, foi, olhando pelo lado bom, fica o aprendizado:

- Respeitar o limite da tecnologia disponível e não agir por achismo;
- Seguir os passos um de cada vez e controlar melhor a ansiedade;
- Lidar com a frustração, prejuízos e consequências após um erro mais grave.

Pode ser que um dia eu volte a tentar algo parecido, mas de maneira diferente, sabendo o que pode dar de errado, e por já ter sentido na pele, do jeito certo.

Fica aqui o convite para quem quiser desenvolver alguma coisa em cima, está lançado o desafio!