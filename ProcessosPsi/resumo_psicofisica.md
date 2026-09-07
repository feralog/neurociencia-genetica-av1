## O que a psicofísica mede

A psicofísica é o estudo da relação entre os **estímulos do mundo físico** e as
**sensações e percepções psicológicas** que eles produzem. De um lado há uma grandeza
mensurável em unidades objetivas — gramas de peso, candelas de luminância, decibéis de
pressão sonora, molaridade de uma solução. Do outro há a experiência do sujeito, que não
tem régua própria: *pesado*, *claro*, *alto*, *doce*. A pergunta que funda o campo é se
existe uma função matemática ligando as duas colunas, e a resposta clássica é que sim.

O achado central, e o que torna a psicofísica interessante, é que essa função **não é
uma reta**. Dobrar o estímulo físico não dobra a sensação. Entre o mundo e a experiência
há uma transformação sistemática, e é essa transformação que Weber e Fechner descreveram.

Isso não é curiosidade de laboratório. Saber qual diferença física uma pessoa
efetivamente nota é o que sustenta:

- **Design e ergonomia de tecnologias** — quanto o contraste de uma tela, o passo de um
  controle de volume ou a vibração de um alerta precisam mudar para que o usuário perceba;
- **Avaliação sensorial** — provas de degustação, controle de qualidade, comparação de
  formulações;
- **Artes** — cinema, música, pintura e arquitetura trabalham com gradações que só
  funcionam se estiverem acima do limiar de quem assiste, ouve ou olha;
- **Pesquisa básica em percepção**, que fornece as constantes usadas por todas as
  aplicações acima.

---

## Weber: a diferença perceptível é proporção do estímulo inicial

Ernst Heinrich Weber chegou por observação sistemática à conclusão que dá nome à lei:

> A menor percepção de diferença entre dois estímulos é uma **proporção constante do
> estímulo inicial**. Em outras palavras, sentir a mudança de um estímulo para outro
> depende de quanto já havia antes — não do acréscimo bruto.

O exemplo canônico é o do peso. Segurando um peso leve, percebe-se com facilidade quando
se acrescenta um pouco mais. Segurando um peso muito maior, **o mesmo acréscimo pode
passar completamente despercebido**. O acréscimo físico é idêntico nos dois casos; o que
mudou foi o ponto de partida.

A demonstração visual mais limpa usa quadros com pontos. Compare o par 10 → 20 com o par
110 → 120: em ambos foram somados exatamente 10 pontos.

![Mesmo acréscimo de 10 pontos sobre bases diferentes: 10→20 é notado, 110→120 não](img:pg09)

No primeiro par, os 10 pontos acrescentados equivalem a **100%** do valor inicial
(10/10) e a diferença salta aos olhos. No segundo, os mesmos 10 pontos equivalem a cerca
de **9%** (10/110) e a diferença some. O acréscimo absoluto não decide nada; a **razão**
entre acréscimo e valor inicial decide tudo.

O mesmo raciocínio explica situações cotidianas: um passo do controle de volume é
claramente audível quando o som está baixo e quase inaudível quando o som já está alto;
acender uma vela num quarto escuro muda tudo, acender a mesma vela ao meio-dia não muda
nada.

---

## Primeira versão: ΔE = C · E, o limiar de diferença

Coube a **Gustav Theodor Fechner** dar forma matemática à observação de Weber. A primeira
versão da lei descreve o **limiar de diferença**, também chamado **Diferença Apenas
Perceptível (D.A.P.)**:

`ΔE = C · E`

| Termo | Significado |
| --- | --- |
| `ΔE` | Diferença perceptível — o menor acréscimo de estímulo que chega a ser detectado |
| `C` | Constante, que **varia conforme o tipo de estímulo** (peso, luz e som têm valores próprios) |
| `E` | Intensidade do **estímulo inicial**, o valor já presente antes do acréscimo |

Para peso, a constante usada é **C = 0,025**, ou seja, 2,5% do estímulo inicial.

![Primeira versão da lei, com os termos e o exemplo da mala de 40 kg](img:pg12)

#### O cálculo da mala

Com uma mala de 40 kg no braço:

`ΔE = 0,025 × 40 = 1 kg`

Só a partir de **1 kg** somado a esses 40 kg a pessoa nota que a mala ficou mais pesada.
Menos que isso existe fisicamente, mas não gera diferença de sensação. A tabela abaixo
mostra como o mesmo cálculo se comporta em outras bases:

| Estímulo inicial (E) | Cálculo | Limiar diferencial (ΔE) |
| --- | --- | --- |
| 200 g | 0,025 × 200 | 5 g |
| 5 kg | 0,025 × 5 | 0,125 kg |
| 20 kg | 0,025 × 20 | 0,5 kg |
| 40 kg | 0,025 × 40 | 1 kg |
| 80 kg | 0,025 × 80 | 2 kg |

Note o que a tabela revela: **dobrar o estímulo inicial dobra o acréscimo necessário**.
A fórmula também se inverte — se alguém detecta a mudança a partir de 0,5 kg, o peso que
segurava era `E = ΔE ÷ C = 0,5 ÷ 0,025 = 20 kg`.

> **Pegadinha frequente:** um acréscimo de 1 kg é percebido numa mala de 5 kg (que exige
> apenas 0,125 kg) e pode passar despercebido numa de 50 kg (que exige 1,25 kg). O
> acréscimo é o mesmo; o veredito é oposto. Sempre calcule a partir de `E`.

---

## Limiar absoluto × limiar diferencial

São dois conceitos distintos, e trocá-los é o erro mais comum do assunto.

| | Limiar absoluto | Limiar diferencial (D.A.P.) |
| --- | --- | --- |
| Pergunta | Há sensação? | A sensação **mudou**? |
| Definição | Quantidade **mínima** de estímulo para que ele seja perceptível | Menor **acréscimo** sobre um estímulo já presente que é detectado |
| Quantos estímulos | Um | Dois — um antes e um depois |
| Fórmula | — | `ΔE = C · E` |
| Abaixo dele | Estimulação **inconsciente** | A mudança não é notada |

> Limiar **absoluto** é o ponto de partida da percepção: abaixo dele o estímulo existe
> no mundo mas não entra na consciência — são **estimulações inconscientes**. Limiar
> **diferencial** já pressupõe que se está percebendo algo e pergunta quanto é preciso
> somar para notar a mudança. Enunciado que fala em "quantidade mínima para haver
> percepção" pede o absoluto; enunciado que fala em "menor diferença entre dois
> estímulos" pede o diferencial.

---

## Fechner: progressão geométrica × progressão aritmética

A segunda conclusão, essa propriamente de Fechner, generaliza o achado do limiar para a
escala inteira da sensação:

> A **estimulação física aumenta em progressão geométrica** enquanto a **percepção
> sensorial correspondente aumenta em progressão aritmética**.

Traduzindo: enquanto o estímulo é **multiplicado**, a sensação apenas **soma** unidades.
Para que a experiência avance de um degrau, o mundo físico precisa ser multiplicado por
um fator — e o mesmo fator aplicado a um valor já alto significa um acréscimo absoluto
muito maior.

A consequência prática é a frase que costuma cair na prova: **é preciso um aumento cada
vez maior de estimulação para que se tenha um aumento razoável da sensação**. Subir o
volume de um som já alto exige um ganho de potência muito superior ao que bastava quando
o som estava baixo, para produzir o mesmo salto subjetivo.

Uma relação em que uma variável cresce por multiplicação e a outra por soma é,
matematicamente, uma **relação logarítmica**. Daí a segunda versão da lei.

---

## Segunda versão: S = k · log E

`S = k · log E`

| Termo | Significado |
| --- | --- |
| `S` | **Sensação** — a magnitude da experiência psicológica produzida |
| `k` | **Constante de Weber**, específica de cada tipo de estímulo |
| `log E` | **Logaritmo** da intensidade do estímulo |

![Segunda versão da lei e o significado de cada termo](img:pg15)

O ponto essencial é que a sensação é proporcional ao **logaritmo** da intensidade, não à
intensidade em si. As duas versões não competem: a primeira descreve o **passo mínimo**
(quanto somar para notar) e a segunda descreve a **escala inteira** (quanta sensação
corresponde a cada intensidade). A segunda é o resultado de empilhar sucessivos passos da
primeira.

### A leitura do gráfico

Colocando as unidades de sensação (medidas em D.A.P.) no eixo vertical e a intensidade do
estímulo no horizontal, obtém-se uma curva **côncava**: sobe rápido no início e vai se
achatando conforme a intensidade cresce.

![Unidades de sensação (DAP) em função da intensidade: os degraus se alargam](img:pg16)

O detalhe que mais rende questão está nos degraus do eixo horizontal. As intensidades
`I₁, I₂, I₃…` que separam unidades sucessivas de sensação `S₁, S₂, S₃…` **não são
equidistantes**: os primeiros intervalos são estreitos e os últimos, muito largos. Cada
nova unidade de sensação custa um acréscimo de estímulo maior que o anterior — a
progressão geométrica de Fechner, desenhada.

- **Intensidades baixas:** um pequeno acréscimo físico já produz muita sensação;
- **Intensidades altas:** a curva se achata, e é preciso muito mais estímulo para ganhar
  a mesma unidade de sensação.

---

## Como se mede um limiar: os métodos psicofísicos clássicos

Nenhuma constante aparece por dedução — todas saem de procedimento experimental. Três
métodos formam o repertório clássico, e o que os distingue é **quem controla o estímulo**
e **como ele varia**.

| Método | Como funciona | Vantagem | Limitação |
| --- | --- | --- | --- |
| **Método dos limites** | O experimentador varia o estímulo em passos pequenos, em séries ascendentes e descendentes; o sujeito diz a cada passo se percebe. O limiar é a média dos pontos de transição. | Rápido e econômico; poucas apresentações bastam para uma estimativa. | Sofre com **erro de habituação** (o sujeito continua respondendo o mesmo) e **erro de antecipação** (ele prevê a mudança); a ordem previsível enviesa a resposta. |
| **Método do ajustamento** | O próprio sujeito manipula o estímulo até que ele apareça, desapareça ou fique igual a um padrão de comparação. | O mais rápido dos três e o mais intuitivo; envolve o participante ativamente. | Como o sujeito controla o processo, o resultado é o mais suscetível a viés e critério pessoal; menos preciso. |
| **Método do estímulo constante** | Um conjunto fixo de intensidades é apresentado em **ordem aleatória**, muitas vezes cada. O limiar é o valor detectado em 50% das apresentações. | O mais **preciso e confiável**: a aleatorização elimina habituação e antecipação. | O mais **demorado e cansativo** — exige grande número de apresentações, e o cansaço do sujeito vira um problema. |

> Note o compromisso: a precisão cresce na mesma direção em que cresce o custo. O
> ajustamento é o mais rápido e o menos confiável; o estímulo constante é o mais
> confiável e o mais caro. O método dos limites fica no meio, e por isso é o mais usado
> em rotina.

Em qualquer um dos três, o limiar não é um ponto rígido: é uma **medida estatística**,
convencionada como a intensidade detectada em metade das apresentações. Essa convenção já
antecipa o problema da seção seguinte.

---

## Limitações da psicofísica clássica

A lei de Weber-Fechner descreve bem uma faixa ampla de fenômenos, mas tem fronteiras
reconhecidas — e elas costumam ser cobradas separadamente.

#### 1. Variabilidade entre pessoas e dentro da mesma pessoa

As unidades de sensação, isto é, os limiares diferenciais, **variam de pessoa para
pessoa** e também **dentro de um mesmo indivíduo** em momentos diferentes. As constantes
tabeladas são médias populacionais, não valores rígidos: não descrevem com exatidão
nenhum sujeito particular numa medida particular.

#### 2. Dependência do estado do sujeito

As unidades de sensação e o **limiar absoluto** se deslocam conforme o estado de quem é
testado: **saudável, cansado, sob efeito de substâncias**, atento ou distraído. Uma
pessoa exausta precisa de mais estímulo para perceber o mesmo evento. Daí a exigência de
controlar rigorosamente as condições do participante em qualquer medida psicofísica.

#### 3. Falha nos extremos da escala

A relação logarítmica se sustenta na **faixa intermediária** de intensidades, mas se
afasta do relato das pessoas nos dois extremos: nas estimulações **altíssimas** e nas
**muito pequenas**, próximas do limiar absoluto. A previsão da fórmula e a experiência
deixam de coincidir justamente onde a escala termina.

> Resumo das três limitações, em ordem de cobrança: varia **entre e dentro** dos
> sujeitos; varia com o **estado** do sujeito; e **não vale nos extremos** de
> intensidade. Nenhuma delas invalida a lei — todas delimitam onde ela se aplica.

---

## O que precisa estar na ponta da língua

- **Psicofísica** = relação entre estímulo físico e sensação psicológica.
- **Weber**: a menor diferença perceptível é **proporção constante do estímulo inicial**.
- **Fechner** formalizou. Primeira versão: `ΔE = C · E` (limiar de diferença, ou D.A.P.),
  com `C` variando por modalidade e `C = 0,025` para peso.
- **Limiar absoluto** = mínimo para haver percepção; abaixo dele, estimulação
  inconsciente. Não confundir com o **limiar diferencial**.
- **Fechner (conclusão)**: estímulo em progressão **geométrica**, sensação em progressão
  **aritmética** — daí `S = k · log E`, com `S` = sensação e `k` = constante de Weber.
- **Curva**: côncava, achatando à direita; os degraus de intensidade **se alargam**.
- **Métodos**: limites (rápido, sujeito a habituação e antecipação), ajustamento (o mais
  rápido, o menos preciso), estímulo constante (o mais preciso, o mais demorado).
- **Limites**: variabilidade inter e intraindividual, estado do sujeito, e falha nas
  intensidades altíssimas e muito pequenas.
