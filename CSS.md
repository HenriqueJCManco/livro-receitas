```

display:flex = torna a tag um elemento do tipo flex container e seus filhos tornam-se flex items.
-----------------------------------------------------
 flex-direction = estabelece os principais eixos 
 (row = esquerda -> direita) 
 (row-reverse= direita ->esquerda)
 ----------------------------------------------------
 (column= ordena em coluna) 
 (column-reverse=de baixo para cima) 
 ----------------------------------------------------
flex-wrap= quebra de linha 
(nowrap = sem quebra de linha) 
(wrap = permite a quebra de linha)
(wrap-reverse = quebra de linha no sentido contrario (desce um enter quando completar a linha))
----------------------------------------------------
flex-flow = comprime a escrita
----------------------------------------------------
justify-content alinhamento dos itens dentro do container 
(flex-star = no inicio do container) 
(flex-end = !flex-start) 
(center= no centro) 
(space-between= cia um espaçamento igual entre os elementos) 
(space-around=os espaçamentos do meio são duas vezes maiores que o inicial e o final)
----------------------------------------------------
align-items= permite o alinhamento no eixo vertical
(stretch =crescem igualmente)
(ceter=alinhamento ao centro do container)
(flex-star e flex-end)
(baseline= alimento de acordo com a linha do texto)
----------------------------------------------------
align-content = propriedade responsável por tratar o alinhamento das linhas do container em relação ao eixo vertical [precisa respeitar a quebra de linha && altura do container maior que a soma das linhas dos itens]
(center)
(stretch)
(flex-start e flex-end)
(space-between = cria um espaçamento igual entre os itens)
(space-around= espaçamento no meio é duas vezes maiores)
-----------------------------------------------------
Flax-grow = define a proporcionalidade de crescimento dos itens, respeitando o tamanho de seus conteúdos internos (apenas numeros) [Não funciona se for adicionado justify-content no container]
-----------------------------------------------------
Flex-basis = estabelece o tamanho inicial do item antes das distribuição de espaço restante dentro dele
(auto = caso n tenha tamanho, proporcional ao conteudo)
(px, %, em, ... = são valores exatos)
(0= tera relação com a definição do flex-grow)
--------------------------------------
flex-shrink =capacidade de redução ou compressão de um um item
--------------------------------------
flex = abreviação de grow, shrink, basis [Nessa ordem]
--------------------------------------
Order (ordem dos itens apresentados)
-----------------------------------------------------
align-self = estabelece o alinhamento de modo individual
(auto = respeita o align-tems)
(flex-star = inicio do container)
(flex-end)
(center = relativo ao centro de acordo com o eixo)
(stretch = ocupa todo o espaço relativo)
(baseline = utiliza a linha base da tipografia)
```