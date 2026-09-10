# ROS 2 Engineering & Robotics Lab

Repositório estruturado para o aprendizado prático e teórico do ROS 2 (Robot Operating System), focado no desenvolvimento de software para robótica autônoma, sistemas embarcados e engenharia de software distribuída.

O objetivo deste repositório é construir uma base sólida em arquitetura de sistemas robóticos, aplicando conceitos fundamentais de Ciência da Computação (sistemas concorrentes, comunicação distribuída, orientação a objetos e sistemas operacionais de tempo real) voltados para a atuação profissional na área.

---

## Estado Atual do Projeto
* **Primeiros Passos:** Criação de estrutura base de Nodes em Python (`rclpy`) e configuração do ambiente de desenvolvimento local integrado ao Git/GitHub.

---

## Trilha de Desenvolvimento & Roadmap

### 1. Comunicação Distribuída & Middleware
* [x] Arquitetura ROS 2 e conceitos fundamentais de Nodes
* [ ] Arquitetura ROS 2 e DDS (Data Distribution Service)
* [ ] Implementação de Nodes, Publishers e Subscribers (C++20 / Python 3)
* [ ] Comunicação Síncrona: Client/Server com Services
* [ ] Tarefas Assíncronas de Longa Duração: Actions, Feedback Loops e Preempção
* [ ] Tipos de Mensagens Customizadas (`.msg`, `.srv`, `.action`)

### 2. Arquitetura de Software & Orquestração
* [ ] Parâmetros Dinâmicos e Reconfiguração em Tempo de Execução
* [ ] Modularização de Executáveis via Composable Nodes (Components)
* [ ] Automação e Orquestração de Processos com Python Launch Files
* [ ] Gerenciamento de Ciclo de Vida de Nós (Lifecycle Nodes)

### 3. Cinemática, Transformadas & Modelagem
* [ ] Gerenciamento de Sistemas de Coordenadas com TF2 (Transform Library)
* [ ] Modelagem de Robôs usando URDF e Xacro (Propriedades Físicas, Inércia e Colisão)
* [ ] Cinemática Direta e Inversa aplicada a Robôs Móveis / Manipuladores

### 4. Simulação, Percepção & Autonomia
* [ ] Ambientes de Simulação com Gazebo / Ignition Gazebo
* [ ] Visualização de Sensores e Debugging Espacial via RViz2 e rqt
* [ ] Integração com Algoritmos de Visão Computacional (OpenCV + ROS Image Transport)
* [ ] Mapeamento e Navegação Autônoma utilizando SLAM e Nav2

---

## Estrutura do Workspace

```text
.
├── src/
│   ├── core_concepts/      # Experimentos de Pub/Sub, Services e Actions
│   ├── custom_interfaces/  # Definições de mensagens, serviços e ações
│   ├── robot_description/  # Arquivos URDF/Xacro e malhas 3D de modelos
│   ├── robot_gazebo/       # Mundos e configurações de simulação
│   └── navigation_bringup/ # Pipeline de SLAM, TF2 e nós de controle
└── README.md
