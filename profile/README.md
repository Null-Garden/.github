<div align="center">

# NULL GARDEN

Projetos orientados a alta performance, arquiteturas resilientes, ferramentas para desenvolvedores e computação científica.

<br />

[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.kernel.org/)

<br />

</div>

---

## Manifesto e Filosofia Técnica

A **Null Garden** opera como núcleo de pesquisa e engenharia de software fundado por **Samuel Spineli** (Engenheiro de Software e Bacharel em Ciência da Computação pela PUC Minas). 

O desenvolvimento de cada projeto apoia-se em quatro pilares fundamentais:

1. **Eficiência e Baixa Latência:** Preferência por tecnologias de execução nativa (Rust, C++, Bun) e otimização de tempo de ciclo em computação paralela e processamento multimídia.
2. **Arquitetura Estrita e Modularidade:** Adoção rigorosa de padrões de projeto (DAO/DTO, RBAC, Clean Architecture), tipagem estrita de ponta a ponta e desacoplamento de responsabilidades.
3. **Local-First e Integridade de Dados:** Sistemas desktop com persistência local resiliente, sincronização sob demanda e autonomia total de execução offline.
4. **Automação de Engenharia:** Pipelines consolidados de Integração e Entrega Contínua (CI/CD) com validação de tipagem, compilação cruzada e empacotamento automatizado para múltiplos sistemas operacionais.

---

## Portfólio de Repositórios e Projetos

### 1. Sistemas Nativos e Clientes de Inteligência Artificial

| Repositório | Descrição Técnica | Stack Tecnológica |
| :--- | :--- | :--- |
| **Esperto** | Cliente desktop de IA multimodal e streaming com arquitetura híbrida de alto desempenho. Suporta múltiplos provedores (Gemini, Claude, GPT, DeepSeek) com memória persistente Dexie e CI/CD multiplataforma. | Tauri v2 (Rust), React, TypeScript |
| **Anamnese** | Plataforma de avaliação contínua e telemetria técnica em Ciência da Computação e IA. Suporte cruzado para Web, Android (Capacitor) e Windows (Electron) com ingestão automatizada de dados e modo offline. | TypeScript, React, Electron, Capacitor |
| **Universal Downloader** | Ferramenta desktop para extração e multiplexação assíncrona de fluxos de vídeo 4K de alta vazão via pipelines de baixo nível com yt-dlp e FFmpeg. | Python, FFmpeg, yt-dlp |
| **PDF Assistant AI** | Arquitetura RAG (Retrieval-Augmented Generation) para indexação vetorial, particionamento e consulta semântica profunda sobre corpos documentais complexos. | Python, OpenAI API, LangChain |

---

### 2. Pesquisa Científica, Algoritmos e Computação de Alto Desempenho

| Repositório | Descrição Técnica | Stack Tecnológica |
| :--- | :--- | :--- |
| **GenreID AI** | Trabalho de Conclusão de Curso (TCC). Avaliação comparativa entre Random Forest e Redes Neurais para identificação de gêneros musicais via extração de Mel-Espectrogramas (Escala Mel de Stevens) e síntese algorítmica de acompanhamentos MIDI por BPM. | Python, Scikit-learn, Librosa, Flask |
| **Blockchain Parallel** | Estudo de escalabilidade e vazão de processamento de blocos criptográficos através de aceleração por hardware e paralelismo multi-thread. | C++, OpenMP, HPC |
| **Osteo Classifier** | Sistema assistido por computador para identificação de osteoartrose de joelho a partir de matrizes de imagens médicas, utilizando técnicas de computação distribuída. | C++, Processamento Digital de Imagens |
| **Geometric Renderer** | Motor de renderização gráfica fundamentado em álgebra linear e geometria analítica. Implementação matemática pura dos algoritmos de linha de Bresenham e DDA sem bibliotecas gráficas auxiliares. | C++, Álgebra Linear |

---

### 3. Plataformas Corporativas, Extensões e Ferramentas

| Repositório | Descrição Técnica | Stack Tecnológica |
| :--- | :--- | :--- |
| **Osaka Tech CRM** | Sistema corporativo de gestão de incidentes com separação formal DAO/DTO, controle de acesso baseado em papéis (RBAC), autenticação JWT e criptografia de credenciais via algoritmo scrypt. | Python, PostgreSQL, JWT, RBAC |
| **Kaiji** | Extensão de produtividade gamificada para o ecossistema Visual Studio Code fundamentada em Webviews isoladas e máquinas de estado finitas para resposta a eventos de salvamento de arquivos. | TypeScript, VS Code Extension API |
| **Conexão Hemocentros** | Plataforma para logística de doação de sangue integrando geolocalização em tempo real e sincronização de dados assíncrona para encaminhamento hospitalar. | Flutter, Firebase, Google Maps API |
| **Fretly** | Aplicação web pedagógica para partitura à primeira vista. Aplica o algoritmo Shuffle Bag para eliminação de viés de amostragem em conjuntos aleatórios e síntese de áudio sintetizado em Web Audio. | TypeScript, Tone.js, VexFlow |
| **UVC Seguro** | Sistema IoT integrado para monitoramento de radiação ultravioleta com comunicação via HTTP e firmware de medição em tempo real. | ESP32, C++, Flutter |

---

## Matriz de Competências e Tecnologias

### Linguagens e Fundamentos
- **Linguagens Primárias:** TypeScript, Python, C++, Rust, C
- **Banco de Dados & Armazenamento:** PostgreSQL (Modelagem Relacional, Índices, Otimização), Dexie (IndexedDB), Firebase Realtime / Firestore
- **Sistemas & Protocolos:** Linux, POSIX, REST APIs, JSON-RPC, WebSocket, TCP/IP, Active Directory

### Arquitetura de Software e Padrões
- Padrões Estruturais e Criacionais (DAO, DTO, Repository, Singleton, Factory)
- Arquitetura de Microsserviços e Monolitos Modulares
- Controle de Acesso Baseado em Papéis (RBAC) e Criptoanálise Aplicada (scrypt, hashing, tokens JWT)
- Métodos Ágeis, Engenharia de Requisitos e Documentação Operacional Técnica (SLAs)

### Inteligência Artificial e DSP
- Retrieval-Augmented Generation (RAG) e Engenharia de Contexto para LLMs
- Processamento Digital de Sinais de Áudio (DSP, Escala Mel de Stevens, STFT, Coeficientes MFCC)
- Modelagem Preditiva Supervisionada (Random Forest, Redes Neurais Densas, Scikit-learn)

---

## Liderança Técnica e Mantenedor

- **Samuel Spineli** — Engenheiro de Software e Cientista da Computação
- **Atuação:** Engenheiro Full Stack (TypeScript / Python / PostgreSQL) na Draft Solutions
- **Localidade:** Belo Horizonte, MG — Brasil

Para colaborações técnicas, parcerias institucionais ou revisão de código:

- GitHub: [github.com/samuelspineli34](https://github.com/samuelspineli34)
- Portfólio & Perfil Profissional: Disponível via perfis oficiais

---

<div align="center">
<sub>Null Garden • Software Architecture, Native Systems & Machine Intelligence • 2026</sub>
</div>
