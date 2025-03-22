# 3. Quantum Gates - Portas Quânticas

## Portas Lógicas Tradicionais

Portas lógicas são componentes presentes em circuitos eletrônicos que possibilitam operações a serem realizadas com bits (0s e 1s). Tanto operações aritméticas clássicas como somar ou subtrair binários como também invertê-los (transformar um 0 em 1 ou vice-versa).

As portas básicas são: OR, AND, NOT, XOR, XAND, NAND, NOR, XNAND e XNOR.

<div align='center'>
<img src='https://miro.medium.com/v2/resize:fit:1100/format:webp/1*OOJB74B_OohXNKtcnHcV1w.jpeg'/>
</div>

## Portas Lógicas Quânticas

Assim como na computação clássica precisamos das portas lógicas para realizar cálculos entre bits, na computação quântica precisaremos de portas quânticas para isso. Existem portas quânticas com objetivos simples até mais complexos, desde simplesmente inverter o valor de qubit de 0 para 1 como também permitir a sobreposição de seus estados.

## Íons aprisionados

Um íon pode armazenar um único qubit, o qual está codificado em dois estados atômicos relacionados à propriedade quântica das particulas para o íon chamada de 'spin'. Os estados do spin são independentes do ambiente externo, o que possibilita que ruídos externos não destruam ou modifiquem os estados dos qubits armazenados.

Em portas de apenas um qubit, nós aplicamos um pulso de micro-ondas de radiação. Ao ponto em que a frequência da onda corresponder exatamente à frequência de ressonância do qubit, fará com que seu estado inverta. Com essa mesma técnica podemos ajustar o pulso da onda para criar estados de superposição.

<div align='center'>
<img src='https://miro.medium.com/v2/resize:fit:1100/format:webp/1*QnuYi5v6sHS8ukihasjpUQ.png'/>
</div>

## Identity Gate (I) - Porta de Identidade

É apenas uma matriz identidade. Ou seja, qualquer qubit arbitrário, α1|0⟩ + α2|1⟩ por exemplo, multiplicado por essa matriz resultará nele mesmo.

<div align='center'>
I = <img src='https://wikimedia.org/api/rest_v1/media/math/render/svg/d0df1bbd611c3587f00ad4c03a383bdd4ee469fc'/>

<br/>

<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/2/2e/Qcircuit_I.svg/225px-Qcircuit_I.svg.png' height=30/>
</div>

## Portas de Pauli (Pauli Gates)

### Pauli Z Gate

A porta Z inverte a fase relativa entre os estados de |0⟩ e |1⟩.

<div align='center'>
Z = <img src='https://wikimedia.org/api/rest_v1/media/math/render/svg/803175a4c9799720d573725e522a618cc6fe6cf9'/>

<br/>

<img src='https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/Qcircuit_Z.svg/225px-Qcircuit_Z.svg.png' height=30/>
</div>

|ψ⟩ = a|0⟩ + b|1⟩, onde _a_ e _b_ são números complexos representando as amplitudes de estados do qubit.

Z|ψ⟩ = a|0⟩ - b|1⟩

### Pauli X Gate

### Pauli Y Gate

## Porta de Hadamard (Hadamard Gate)
