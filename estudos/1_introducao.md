# 1 - Introdução à Computação Quântica

## Superposição Quântica

É um princípio da mecânica quântica que permite que um sistema quântico esteja em vários estados ao mesmo tempo.

Equação de Schrödinger, a qual descreve como o estado quântico de um sistema físico muda com o tempo:

<div align='center'>
<img src='https://wikimedia.org/api/rest_v1/media/math/render/svg/1799e4a910c7d26396922a20ef5ceec25ca1871c'/>
</div>

## Qubit vs Bit clássico

O **bit** (binary digit) é a menor unidade de informação que pode ser armazenada ou transmitida em sistemas digitais, podendo assumir dois valores: 0 ou 1.

O **qubit** (quantum bit) é a únidade básica da computação quântica. Ele utiliza do fenômeno da mecânica quântica chamado de superposição para atingir a combinação linear de dois estados (sendo estes estados 0 e 1). Ou seja, um qubit pode representar um |0⟩, um |1⟩ ou qualquer proporção de |0⟩ e |1⟩ em superposição dos dois estados, com uma certa probabilidade de ser |0⟩ e uma certa probabilidade de ser |1⟩.

<div align='center'>
<b>|Ψ⟩ = α|0⟩ + β|1⟩</b>
</div>

<br/>
Onde:

|0⟩ = mat(1 0)<br/>
|1⟩ = mat(0 1)

<br/>
<br/>

> Observação: n qubits = 2^n bits

## Emaranhamento (ou entrelaçamento) quântico

É um fenômeno que ocorre quando partículas quânticas se tornam interdependentes, mesmo a grandes distâncias. Ou seja, permite que dois ou mais objetos estejam de alguma forma tão ligados que um objeto não possa ser corretamente descrito sem que a sua contra-parte seja mencionada - mesmo que os objetos possam estar espacialmente separados por milhões de anos-luz.

## O estado de Bell

O estado de Bell na computação quântica é um tipo especial de estado de emaranhamento onde dois qubits estão interdependentes de forma que o estado de um qubit influencie instantâneamente o estado do outro, sem importar a distância entre eles.
