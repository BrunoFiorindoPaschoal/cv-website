---
title: Aprendizado de Máquina
weight: 2
image: images/Machine.png
papers:
  - title: Task Learning with Mechanical Neural Networks
    file: papers/Paper_TO_MNN_Bruno_Paschoal1.pdf
  - title: Classification with Hydraulic Neural Networks
    file: papers/Paper_TO_MNN_Bruno_Paschoal_Hidraulic.pdf
---
Tenho interesse em aprendizado de máquina tanto como ferramenta de engenharia quanto como algo que pode ser construído na própria matéria.

### Redes neurais físicas
Na minha pesquisa financiada pela FAPESP, desenvolvi redes neurais que computam com física em vez de eletrônica:

- uma **rede neural hidráulica**, em que as seções transversais dos tubos são os pesos treináveis, as entradas definem as condições de contorno e o escoamento em regime permanente codifica a classe; validada no conjunto Iris no COMSOL Multiphysics;
- uma **rede neural mecânica** em treliças não lineares, em que as rigidezes das barras são os parâmetros treináveis, as cargas externas são as entradas e os deslocamentos nodais, as saídas.

Ambas foram treinadas de ponta a ponta com otimização baseada em gradiente e sensibilidades pelo método adjunto (COMSOL LiveLink for MATLAB), visando aplicações como estruturas inteligentes e robótica flexível.

### ML para engenharia
No LPL da TUM, desenvolvo **modelos substitutos** que substituem simulações de elementos finitos caras dentro de laços de otimização.

### LLMs, agentes e aprendizado por reforço
- **Tutor de voz com IA para alemão** (projeto pessoal): um pipeline de LLM fala-a-fala em tempo real (Pipecat, Gemini Live API) com cenários de role-play, correção de erros na hora e memória de longo prazo em SQLite alimentada por resumos gerados por LLM ao fim de cada sessão.
- **Certificações Hugging Face** (2026): Deep Reinforcement Learning com Certificate of Excellence (agentes DQN/PPO, incluindo controle de braço robótico no Panda-Gym), Agentes de IA (smolagents, LangGraph, LlamaIndex, avaliados no GAIA) e Model Context Protocol.

### Disciplinas relacionadas
Physics-Informed Machine Learning, Machine Learning and Optimization (TUM) · Aprendizado de Máquina e Reconhecimento de Padrões com o Prof. Dr. Fabio Gagliardi Cozman, abordando a teoria numérica do aprendizado e a implementação de algoritmos de classificação (USP).
