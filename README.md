# 🎹 mobile_frameworks: Interatividade Criativa e Física

> Um repositório de projetos **FLOSS** (Free/Libre and Open Source Software) dedicado a explorar a fronteira da interatividade em dispositivos móveis. Aqui, transformamos smartphones e tablets em instrumentos musicais, portais para realidades estendidas e centros de comando para o mundo físico.

Bem-vindo a um laboratório de experimentação onde o desenvolvimento mobile encontra a tecnologia criativa, a computação imersiva e a eletrônica. Este espaço é dedicado a criar e compartilhar frameworks, componentes e projetos completos que ultrapassam os limites dos aplicativos convencionais.

---

## 🚀 Filosofia e Visão

Nossa visão é usar a onipresença e o poder dos dispositivos móveis para criar experiências interativas, artísticas e úteis.

1.  **Tecnologia como Expressão:** Focamos em ferramentas que permitem a criação artística, como **sintetizadores, sequenciadores e drum machines**.
2.  **Realidades Estendidas (XR):** Exploramos **Realidade Aumentada (AR), Virtual (VR) e Mista (MR)** para mesclar o mundo digital com o físico.
3.  **Controle do Mundo Físico:** Construímos pontes entre o software e o hardware, criando interfaces para **Single-Board Computers (SBCs)** e dispositivos de **Internet das Coisas (IoT)**.
4.  **Portabilidade e Código Aberto:** Todos os projetos são FLOSS e projetados para serem "cool portable stuff" – ferramentas legais e portáteis.

---

## 🗺️ Estrutura Detalhada do Repositório

O conteúdo está organizado em módulos que representam os principais domínios de exploração.

<br>

* ### `01-Audio-and-Music-Tech/`
    > Módulos e projetos para a criação de instrumentos musicais digitais e ferramentas de áudio.
    >
    * **`01.1-Synthesizers/`** (Ex: Osciladores, filtros, envelopes em apps mobile)
    * **`01.2-Sequencers/`** (Ex: Sequenciadores de passos, MIDI controllers)
    * **`01.3-Drum-Machines/`** (Ex: Drum pads, samplers, geradores de ritmo)
    * **`01.4-Audio-Effects-Processors/`** (Ex: Reverbs, delays, distorções)

* ### `02-XR-and-Immersive-Tech/`
    > Frameworks e protótipos para experiências de Realidade Aumentada, Virtual e Mista.
    >
    * **`02.1-Augmented-Reality-AR/`** (Ex: Projetos com ARCore/ARKit, reconhecimento de marcadores, visualização de modelos 3D)
    * **`02.2-Virtual-Reality-VR/`** (Ex: Experiências para Google Cardboard, WebXR)
    * **`02.3-Mixed-Reality-MR/`** (Ex: Conceitos e integrações para MR)

* ### `03-Physical-Computing-and-IoT/`
    > Aplicativos que servem como interface para hardware externo.
    >
    * **`03.1-SBC-Dashboards/`** (Ex: Apps para monitorar e controlar Raspberry Pi, Jetson Nano, etc.)
    * **`03.2-BLE-Device-Control/`** (Ex: Framework para comunicação com microcontroladores via Bluetooth Low Energy)
    * **`03.3-IoT-and-MQTT-Clients/`** (Ex: Apps para interagir com redes de sensores e atuadores via MQTT)
    * **`03.4-Robotics-Interfaces/`** (Ex: Joysticks virtuais, telemetria e controle para projetos do `mecha-blocks`)

* ### `04-Core-Frameworks-and-Components/`
    > A base para os outros projetos. Componentes reutilizáveis e arquiteturas.
    >
    * **`04.1-UI-Component-Library/`** (Ex: Knobs, sliders, pads otimizados para controle em tempo real)
    * **`04.2-Communication-Protocols/`** (Ex: Implementações de OSC (Open Sound Control), MIDI via Bluetooth/USB)
    * **`04.3-State-Management-Patterns/`** (Ex: Arquiteturas para apps reativos e complexos)

* ### `05-Demos-and-Integrated-Projects/`
    > Projetos completos que combinam módulos de diferentes áreas para criar uma experiência única.
    >
    * **`05.1-AR-Synthesizer/`** (Ex: Um sintetizador cujos controles são objetos virtuais ancorados no mundo real)
    * **`05.2-IoT-Music-Sequencer/`** (Ex: Um sequenciador que controla luzes e motores via MQTT)

---

## 🛠️ Tecnologias-Chave

Este repositório explora uma variedade de tecnologias e frameworks, incluindo:

* **Desenvolvimento Mobile:** Kotlin (Android), Swift (iOS), Flutter, React Native, Dart
* **Áudio:** JUCE, SuperCollider, Pure Data (integrados via libpd), Web Audio API
* **Gráficos e XR:** OpenGL ES, Vulkan, ARCore, ARKit, Unity, Unreal Engine, WebXR
* **Comunicação com Hardware:** Bluetooth Low Energy (BLE), Wi-Fi, MQTT, OSC, MIDI

---

## 📜 Licença

Este repositório é distribuído sob a licença [MIT](LICENSE).
