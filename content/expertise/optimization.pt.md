---
title: Otimização
weight: 1
image: images/Topologic.png
papers:
  - title: Otimização Topológica de Máquinas Elétricas
    file: papers/Paper_TO___Electric_Machines.pdf
---
A otimização numérica é o fio condutor do meu trabalho: deixar um algoritmo, e não apenas a intuição, decidir a forma de um sistema.

### Otimização topológica
A otimização topológica altera a distribuição de material dentro de um domínio de projeto para maximizar o desempenho de um sistema. Como bolsista FAPESP no Laboratório de Otimização de Sistemas Multifísicos (MSOL) da USP, desenvolvi um algoritmo próprio para otimizar **motores de relutância chaveados**:

- modelos termo-magnéticos em elementos finitos na plataforma open source **FEniCS**, com **dolfin-adjoint** para as sensibilidades e **IPOPT** como otimizador;
- redução significativa de material com ganhos mensuráveis de eficiência;
- extensão para **otimização multimaterial discreta** com o TOBS, validada em software comercial.

### Otimização de projeto na TUM
No Laboratório de Desenvolvimento de Produto e Construção Leve (LPL) da TUM, trabalho com **Otimização Multidisciplinar de Projeto** e com o método de **Espaços de Soluções (Solution Spaces)**, que encontra faixas de bons projetos em vez de um único ótimo. Desenvolvo modelos substitutos que dispensam análises de elementos finitos caras e mantenho a Optimization Toolbox do laboratório. Com um parceiro industrial da Baviera, aplicamos o método a um martelo compactador de solo, melhorando seu desempenho e a segurança do operador.

### Disciplinas relacionadas
Multidisciplinary Design Optimization, Optimal Control and Decision Making, Machine Learning and Optimization, Numerical Methods for Conservation Laws (TUM) · Métodos Numéricos e Aplicações, Mecânica Computacional para Mecatrônica (USP).
