---
title: Currículo
---
<section id="education">
  <h2>Formação</h2>

  <div class="education-item">
    <div class="degree-info">
      <h3>M.Sc. Mechatronics, Robotics and Biomechanical Engineering</h3>
      <p class="date">Out. 2025 – Set. 2027 (previsto)</p>
      <p>Universidade Técnica de Munique (TUM), Alemanha</p>
    </div>
    <div class="degree-details">
      <p><strong>Disciplinas selecionadas:</strong> Multidisciplinary Design Optimization, Physics-Informed Machine Learning, Machine Learning and Optimization, Optimal Control and Decision Making, Advanced Control, Robot Motion Planning, Modeling and Reduction of Complex Systems, Methods in Neuromechanics, Numerical Methods for Conservation Laws.</p>
    </div>
  </div>

  <div class="education-item">
    <div class="degree-info">
      <h3>Bacharelado em Engenharia Mecatrônica</h3>
      <p class="date">Jan. 2022 – Jun. 2025</p>
      <p>Escola Politécnica da Universidade de São Paulo (USP), Brasil</p>
    </div>
    <div class="degree-details">
      <h4>Duplo Diploma TUM–USP</h4>
      <p>A Engenharia Mecatrônica integra mecânica, eletrônica, controle e computação para desenvolver sistemas automatizados.</p>
      <p><strong>Disciplinas selecionadas:</strong> Aprendizado de Máquina e Reconhecimento de Padrões, Métodos Numéricos, Mecânica Computacional, Controle I, Sistemas Dinâmicos I e II, Sistemas Embarcados, Microprocessadores em Automação e Robótica, Mecanismos para Automação, Atuadores e Acionamentos, Sistemas Computacionais para Mecatrônica.</p>
    </div>
  </div>

  <div class="education-item">
    <div class="degree-info">
      <h3>Ensino Médio Brasileiro e Americano</h3>
      <p class="date">Jan. 2019 – Dez. 2021</p>
      <p>Texas Tech University (TTU), EUA e Colégio Agostiniano Mendel, Brasil</p>
    </div>
    <div class="degree-details">
      <p>Cursei em paralelo os currículos do ensino médio brasileiro e americano, por meio de uma parceria entre o Colégio Agostiniano Mendel e a Texas Tech University.</p>
    </div>
  </div>
</section>

<section id="experience">
  <h2>Experiência Profissional</h2>

  <div class="experience-item">
    <div class="job-info">
      <h3>Assistente de Pesquisa (HiWi)</h3>
      <p class="date">Fev. 2026 – atual</p>
      <p>Universidade Técnica de Munique, Alemanha</p>
    </div>
    <div class="job-details">
      <h4>Laboratório de Desenvolvimento de Produto e Construção Leve (LPL)</h4>
      <p>Orientador: Prof. Markus Zimmermann</p>
      <ul>
        <li>Desenvolvi modelos substitutos (surrogates) para análises de elementos finitos de alto custo computacional, reduzindo o tempo de avaliação com alta fidelidade em casos práticos.</li>
        <li>Desenvolvo e mantenho a LPL Optimization Toolbox, ampliando o cálculo de Espaços de Soluções (Solution Spaces) para fluxos de Otimização Multidisciplinar de Projeto.</li>
        <li>Apliquei o método de Espaços de Soluções com um parceiro industrial da Baviera em um martelo compactador de solo, com ganhos mensuráveis de desempenho e mais segurança para o operador.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="job-info">
      <h3>Iniciação Científica</h3>
      <p class="date">Ago. 2023 – Jul. 2025</p>
      <p>Universidade de São Paulo, Brasil</p>
    </div>
    <div class="job-details">
      <h4>Laboratório de Otimização de Sistemas Multifísicos (MSOL)</h4>
      <p>Bolsa FAPESP, renovada duas vezes · Orientador: Prof. Dr. Emílio Carlos Nelli Silva</p>
      <ul>
        <li>Desenvolvi modelos termo-magnéticos em elementos finitos de motores de relutância chaveados no FEniCS; as rotinas de otimização topológica obtiveram redução significativa de material com ganhos mensuráveis de eficiência.</li>
        <li>Estendi as rotinas para otimização multimaterial discreta com o TOBS e validei os modelos open source em software comercial.</li>
        <li>Desenvolvi redes neurais hidráulicas e mecânicas que codificam tarefas de aprendizado de máquina em dinâmica dos fluidos e mecânica estrutural.</li>
      </ul>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Projetos e Pesquisa</h2>

  <div class="experience-item">
    <div class="job-info">
      <h3>Redes Neurais Hidráulicas e Mecânicas</h3>
      <p class="date">2025 – 2026</p>
      <p>Pesquisa financiada pela FAPESP · COMSOL, MATLAB, Python, método adjunto</p>
    </div>
    <div class="job-details">
      <ul>
        <li>Projetei uma rede neural hidráulica em que as seções transversais dos tubos são os pesos treináveis: as entradas definem as condições de contorno e o escoamento em regime permanente codifica a classe; validada no conjunto Iris no COMSOL Multiphysics.</li>
        <li>Desenvolvi uma rede neural mecânica em treliças não lineares, com rigidezes das barras como parâmetros treináveis, cargas como entradas e deslocamentos nodais como saídas.</li>
        <li>Treinei ambas de ponta a ponta com otimização baseada em gradiente e sensibilidades pelo método adjunto (COMSOL LiveLink for MATLAB), mostrando que sistemas físicos passivos podem computar como redes neurais.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="job-info">
      <h3>Sistema de Posicionamento por Cabos (PI7)</h3>
      <p class="date">2025</p>
      <p>Projeto Integrado da USP · Raspberry Pi Pico W, PIC16F886, C, Python, MATLAB, placa própria</p>
    </div>
    <div class="job-details">
      <ul>
        <li>Construí, em uma equipe de oito, um robô no estilo "câmera aranha": dois motores CC enrolam e desenrolam carretéis de cabo para mover uma carga suspensa em um plano vertical.</li>
        <li>Todas as áreas da mecatrônica em um só sistema: estrutura e mecanismo de carretéis, placas próprias de driver de motor com L298N, controle PID de posição com encoder em microcontroladores PIC16F886 e um Raspberry Pi Pico W coordenando os motores.</li>
        <li>Sistema funcional entregue do conceito ao hardware. <a href="/pt/expertise/robotics/">Mais na página de Robótica →</a></li>
      </ul>
    </div>
  </div>
</section>

<section id="certifications">
  <h2>Certificações</h2>

  <div class="experience-item">
    <div class="job-info">
      <h3>Cisco Cybersecurity Associate</h3>
      <p class="date">Jan. 2022 – Abr. 2023</p>
      <p>Cisco Networking Academy</p>
    </div>
    <div class="job-details">
      <h4>Segurança de Redes e Gestão de Riscos</h4>
      <p>Obtida na 5ª Maratona de CyberEducação da Cisco Brasil: cinco cursos certificados (240 horas) sobre monitoramento de redes, detecção de ameaças, controle de acesso, análise de vulnerabilidades e políticas de segurança.</p>
      <div class="badges">
        <div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="f442e4d9-2139-4f6f-bfd0-50ce22c50a04" data-share-badge-host="https://www.credly.com"></div>
        <div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="01c59af6-f075-439e-afe6-08b492f4c963" data-share-badge-host="https://www.credly.com"></div>
        <div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="0d934d92-553f-410e-aa6e-74fd0e243e29" data-share-badge-host="https://www.credly.com"></div>
        <div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="26826204-42cc-4750-b09b-c22aeb0be69f" data-share-badge-host="https://www.credly.com"></div>
        <div data-iframe-width="150" data-iframe-height="270" data-share-badge-id="c35660bb-5d7b-4dee-8b3b-12a89b617f47" data-share-badge-host="https://www.credly.com"></div>
      </div>
      <script type="text/javascript" async src="//cdn.credly.com/assets/utilities/embed.js"></script>
    </div>
  </div>
</section>

<section id="skills">
  <h2>Habilidades e Interesses</h2>

  <div class="experience-item skills">
    <ul>
      <li><strong>Idiomas:</strong> Português (nativo), Inglês (fluente), Alemão (avançado, B2)</li>
      <li><strong>Programação e ferramentas:</strong> Python, C++, C, MATLAB/Simulink, Linux (avançado) · Verilog, Java (intermediário) · CSS, VBA, Power BI (básico)</li>
      <li><strong>Simulação e otimização:</strong> COMSOL Multiphysics, FEniCS, modelos substitutos, otimização de projeto</li>
      <li><strong>Interesses:</strong> IA responsável, robótica e sistemas autônomos, inteligência estrutural, otimização matemática, computação científica, análise de dados</li>
    </ul>
  </div>
</section>
