---
title: Resume
---
<section id="education">
  <h2>Education</h2>

  <div class="education-item">
    <div class="degree-info">
      <h3>M.Sc. Mechatronics, Robotics and Biomechanical Engineering</h3>
      <p class="date">Oct 2025 – Sep 2027 (expected)</p>
      <p>Technical University of Munich (TUM), Germany</p>
    </div>
    <div class="degree-details">
      <p><strong>Selected coursework:</strong> Multidisciplinary Design Optimization, Physics-Informed Machine Learning, Machine Learning and Optimization, Optimal Control and Decision Making, Advanced Control, Robot Motion Planning, Modeling and Reduction of Complex Systems, Methods in Neuromechanics, Numerical Methods for Conservation Laws.</p>
    </div>
  </div>

  <div class="education-item">
    <div class="degree-info">
      <h3>B.Sc. Mechatronics Engineering</h3>
      <p class="date">Jan 2022 – Jun 2025</p>
      <p>Escola Politécnica, University of São Paulo (USP), Brazil</p>
    </div>
    <div class="degree-details">
      <h4>TUM–USP Double Degree</h4>
      <p>Class rank: top 15 of 69, selected for the double degree fellowship.</p>
      <p>Mechatronics integrates mechanics, electronics, control and computing to build automated systems.</p>
      <p><strong>Selected coursework:</strong> Machine Learning and Pattern Recognition, Numerical Methods, Computational Mechanics, Control I, Dynamic Systems I &amp; II, Embedded Systems, Microprocessors in Automation and Robotics, Mechanisms for Automation, Actuators and Drives, Computational Systems for Mechatronics.</p>
    </div>
  </div>

  <div class="education-item">
    <div class="degree-info">
      <h3>Brazilian–American High School Diploma</h3>
      <p class="date">Jan 2019 – Dec 2021</p>
      <p>Texas Tech University (TTU), USA &amp; Colégio Agostiniano Mendel, Brazil</p>
    </div>
    <div class="degree-details">
      <p>Completed the Brazilian and the American high school curricula in parallel through a partnership between Colégio Agostiniano Mendel and Texas Tech University.</p>
    </div>
  </div>
</section>

<section id="experience">
  <h2>Work Experience</h2>

  <div class="experience-item">
    <div class="job-info">
      <h3>Student Research Assistant (HiWi)</h3>
      <p class="date">Feb 2026 – Present</p>
      <p>Technical University of Munich, Germany</p>
    </div>
    <div class="job-details">
      <h4>Laboratory for Product Development and Lightweight Design (LPL)</h4>
      <p>Supervisor: Prof. Markus Zimmermann</p>
      <ul>
        <li><strong>Industrial collaboration with a Bavarian industry partner:</strong> applied the Solution Space method to a soil-compaction motor hammer, reducing average vibration by 30% and improving soil compaction by 25%, lowering operator vibration exposure.</li>
        <li>Built surrogate models that replace computationally expensive Finite Element Analysis in design studies, evaluating designs ~100× faster.</li>
        <li>Develop and maintain the LPL Optimization Toolbox, extending its Solution Space computation for Multidisciplinary Design Optimization (MDO) workflows.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="job-info">
      <h3>Undergraduate Research Scholar</h3>
      <p class="date">Aug 2023 – Jul 2025</p>
      <p>University of São Paulo, Brazil</p>
    </div>
    <div class="job-details">
      <h4>Multiphysics Systems Optimization Laboratory (MSOL)</h4>
      <p>FAPESP grant, renewed twice · Supervisor: Prof. Dr. Emílio Carlos Nelli Silva</p>
      <ul>
        <li>Developed thermo-magnetic FEM models of switched reluctance motors in FEniCS; topology optimization reduced material by 20% with no loss in performance.</li>
        <li>Extended the topology optimization routines to discrete multi-material design with TOBS, and validated the open-source models against commercial software.</li>
      </ul>
    </div>
  </div>
</section>

<section id="projects">
  <h2>Projects &amp; Research</h2>

  <div class="experience-item">
    <div class="job-info">
      <h3>Hydraulic &amp; Mechanical Neural Networks</h3>
      <p class="date">2025 – 2026</p>
      <p>FAPESP-funded research · Submitted to Elsevier <em>Neural Networks</em> · COMSOL, MATLAB, Python, adjoint method</p>
    </div>
    <div class="job-details">
      <ul>
        <li>Designed a hydraulic neural network whose pipe cross-sections are trainable weights: inputs set boundary conditions and the steady-state flow encodes the class; validated on the Iris dataset in COMSOL Multiphysics.</li>
        <li>Developed a mechanical neural network on nonlinear trusses, with beam stiffnesses as learnable parameters, loads as inputs and nodal displacements as outputs.</li>
        <li>Trained both end-to-end with gradient-based optimization using adjoint sensitivities (COMSOL LiveLink for MATLAB), showing that passive physical systems can compute like neural networks.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="job-info">
      <h3>AI Voice Tutor for Learning German</h3>
      <p class="date">Jun 2026 – Present</p>
      <p>Personal project · Python, Pipecat, Gemini Live, SQLite, Whisper</p>
    </div>
    <div class="job-details">
      <ul>
        <li>Built a personalized German tutor that holds real-time spoken conversations, simulates everyday situations through role-play, and points out mistakes as they happen, with memory that persists between sessions.</li>
        <li>Orchestrated a multimodal LLM pipeline in Python (Pipecat, Gemini Live API): real-time speech-to-speech streaming with voice activity detection, context engineering of system prompts from the learner's profile and past lessons, and model fallback routing under API rate limits.</li>
        <li>Designed a relational SQLite database as the tutor's long-term memory: an end-of-session LLM summarization step stores lesson summaries, mistakes and a versioned learner profile, which SQL queries load into the next session's context in place of vector-based RAG.</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="job-info">
      <h3>Cable-Driven Aerial Positioning System (PI7)</h3>
      <p class="date">2025</p>
      <p>USP Integrated Engineering Project · Raspberry Pi Pico W, PIC16F886, C, Python, MATLAB, custom PCB</p>
    </div>
    <div class="job-details">
      <ul>
        <li>Built a spidercam-style robot in a team of eight: two DC motors wind and unwind cable spools to move a suspended payload in a vertical plane.</li>
        <li>Covered all of mechatronics in one system: frame and spool mechanism, custom L298N motor-driver PCBs, encoder-based PID position control on PIC16F886 microcontrollers, and a Raspberry Pi Pico W coordinating the motors.</li>
        <li>Delivered a working system from concept to hardware. <a href="/expertise/robotics/">More on the Robotics page →</a></li>
      </ul>
    </div>
  </div>
</section>

<section id="certifications">
  <h2>Certifications</h2>

  <div class="experience-item">
    <div class="job-info">
      <h3>Hugging Face Certifications</h3>
      <p class="date">Sep – Nov 2026</p>
      <p>Online courses on <a href="https://huggingface.co/brunopaschoal">Hugging Face</a> · Deep Reinforcement Learning, AI Agents, Model Context Protocol</p>
    </div>
    <div class="job-details">
      <ul>
        <li><strong>Deep Reinforcement Learning – Certificate of Excellence:</strong> trained DQN/PPO agents with Stable-Baselines3 that passed all benchmark thresholds on the Hugging Face Hub, including robotic-arm control (Panda-Gym) and multi-agent Unity ML-Agents environments.</li>
        <li><strong>AI Agents:</strong> built agents with smolagents, LangGraph and LlamaIndex (tool calling, agentic RAG); the final agent was evaluated on the GAIA benchmark.</li>
        <li><strong>Model Context Protocol (MCP):</strong> built MCP servers (Gradio) and clients in Python and JavaScript, including workflow-automation servers (PR review, CI/CD webhooks).</li>
      </ul>
    </div>
  </div>

  <div class="experience-item">
    <div class="job-info">
      <h3>Cisco Cybersecurity Associate</h3>
      <p class="date">Jan 2022 – Apr 2023</p>
      <p>Cisco Networking Academy</p>
    </div>
    <div class="job-details">
      <h4>Network Security &amp; Risk Management</h4>
      <p>Earned through the 5th Cisco Brazil CyberEducation Marathon: five certified courses (240 hours) on network monitoring, threat detection, access control, vulnerability assessment and security policy.</p>
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
  <h2>Skills &amp; Interests</h2>

  <div class="experience-item skills">
    <ul>
      <li><strong>Languages:</strong> Portuguese (native), English (fluent, C1 – US High School Diploma), German (B2 – TUM Language Center; Goethe-Zertifikat B1)</li>
      <li><strong>Programming &amp; tools:</strong> Python, C++, C, MATLAB/Simulink, SQL (SQLite), Git, Linux (advanced) · Verilog, Java (intermediate) · CSS, VBA, Power BI (basic)</li>
      <li><strong>Simulation &amp; optimization:</strong> numerical and nonlinear optimization, gradient-based optimization with adjoint sensitivities, topology optimization (TOBS), surrogate modeling, Multidisciplinary Design Optimization / Solution Spaces, FEM (FEniCS, COMSOL Multiphysics)</li>
      <li><strong>AI &amp; ML:</strong> PyTorch, reinforcement learning (Stable-Baselines3, DQN, PPO), LLM agents (smolagents, LangGraph, LlamaIndex), Model Context Protocol, real-time multimodal LLM pipelines (Pipecat, Gemini Live API, Whisper)</li>
      <li><strong>Interests:</strong> Responsible AI, robotics &amp; autonomous systems, structural intelligence, mathematical optimization, scientific computing, data analysis</li>
    </ul>
  </div>
</section>
