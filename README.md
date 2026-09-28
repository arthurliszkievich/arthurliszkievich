<div align="center">

<img src="./header%20(1).svg" alt="Arthur Liszkievich - Back-End & Systems Engineer" width="100%" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=4FC3F7&center=true&vCenter=true&width=700&lines=Python+%E2%80%A2+Django+%E2%80%A2+DRF+%E2%80%A2+gRPC;Criptografia+%E2%80%A2+Engenharia+Reversa+%E2%80%A2+APIs;Clean+Architecture+%E2%80%A2+SOLID+%E2%80%A2+Testes" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/arthurliszkievich/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arthurliszkievich@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/arthurliszkievich)

![Visitas](https://komarev.com/ghpvc/?username=arthurliszkievich&label=Visitas&color=2c5364&style=flat-square)

</div>

---

## 👨‍💻 Sobre mim

Desenvolvedor **Back-End** focado em **arquiteturas de alta performance**, **APIs REST e gRPC**, **criptografia aplicada (AES/HMAC)** e **automação headless multiplataforma** (Windows, Linux e Android/Termux). Aplico **Clean Architecture**, **SOLID**, **resiliência de rede** e **defesa em profundidade** no dia a dia.

Cursando **Análise e Desenvolvimento de Sistemas (ADS)**.

```python
class Developer:
    name = "Arthur Liszkievich"
    role = "Back-End & Systems Software Engineer"
    education = "Análise e Desenvolvimento de Sistemas (ADS)"
    location = "Brasil 🇧🇷"

    stack = {
        "languages": ["Python", "SQL", "Bash", "Protocol Buffers"],
        "backend": ["Django", "DRF", "FastAPI", "Flask", "gRPC", "SQLAlchemy", "Peewee"],
        "security": ["AES-CBC", "HMAC-SHA", "PyCryptodome", "SQLCipher", "OAuth2"],
        "databases": ["PostgreSQL", "SQLite", "MySQL"],
        "infra": ["Docker", "Linux", "Git", "GitHub Actions", "Pytest"],
    }

    principles = [
        "🏗️ Clean Architecture, SOLID e Service Layer",
        "🔐 Criptografia aplicada e bancos cifrados",
        "⏱️ Resiliência: retry com jitter, renovação de token, cache TTL",
        "📱 Multiplataforma, inclusive ambientes restritos (Termux ARM64)",
        "🧪 Testes automatizados e CI/CD",
    ]

🛠️ Stack

🤖 Engenharia aumentada por IA

💼 Expertise

🔐 Criptografia & Engenharia Reversa

  - REST proprietário: montagem e consumo de payloads criptografados (AES-CBC +
    HMAC)
  - SQLCipher: consultas relacionais via Peewee em bancos cifrados
  - OAuth2 via CDP: captura de códigos de autorização com Chrome DevTools
    Protocol
  - Parser em camadas: custom schemes, URL encoding e regex

🧠 Algoritmos & Regras de Negócio

  - Seleção multicritério: ranking por tupla hierárquica (raridade, nível, SA,
    potencial)
  - Condições "OU": heurística que elege a categoria com maior score acumulado
  - Ciclo de vantagem elemental: PHY → INT → TEQ → AGL → STR
  - Defesa em profundidade: guard clauses e proteção de ativos raros com
    frozenset

⚡ Resiliência & Confiabilidade

  - Ciclo de vida de tokens: interceptor mid_handler com renovação de Bearer e
    reenvio atômico
  - Anti-429: cache TTL em memória (300s) protegendo a API do Discord
  - Retry com jitter: pausas aleatórias em loops de automação
  - Fallback gracioso: preserva estado em oscilações de rede

📱 Sistemas & Multiplataforma

  - Android (Termux): solução para a compilação Rust/Maturin no ARM64
    (Python 3.13)
  - Carregamento dinâmico: 65+ módulos headless, sem dependências de desktop
  - Gatekeeper multi-tier: validação de cargos Discord (Free, Mobile, VIP, APEX)
  - Release management: SemVer, patches (v1.4.7) e major (v2.0)

🎯 Projetos em destaque

🛡️ Yoda Engine & Dokkan Bot

Automação headless e engenharia reversa de protocolo para Dragon Ball Z Dokkan
Battle.

Papel: Core Developer
Tecnologias: Python PyCryptodome Peewee SQLCipher CDP Flask Termux ARM64 Linux

|    | Contribuição                         | Detalhes                                                                                                                                                                           |
| -- | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ⚔️ | **Overhaul do Ultimate Clash**       | Correção de inversão semântica no payload `/finish` (`damage` vs `remaining_hp`), integração de `crypto.decrypt_sign()` e seleção de time por ciclo elemental com pausas humanas   |
| 🧠  | **Smart Category Auto-Team Builder** | Parser de missões endgame, cruzamento com o banco cifrado via Peewee, resolução heurística de condições "OU" e correção de deck fixo em `change_team.py` respeitando `config.deck` |
| 🔑  | **Google OAuth2 via CDP**            | Captura de códigos em redirects de custom scheme pelos Performance Logs do Chrome, com decodificação em 4 camadas (`extract_code`)                                                 |
| 🚦  | **Interceptor de sessão**            | `mid_handler` com renovação transparente de token em `invalid_token` e cache TTL de 300s contra HTTP 429                                                                           |
| 📱  | **Infra mobile (Termux)**            | Contorno da compilação Rust/Maturin no Python 3.13 e resolução de dependências de desktop: de 8 para mais de 65 comandos no Android                                                |
| 💎  | **Hidden Potential em 1 clique**     | Pipeline alinhado às regras da API (v5.31+ e v6.2.0), consumindo cópias pela trilha evolutiva sem reversões legadas                                                                |

🛒 E-Commerce Microservice

Backend de e-commerce com comunicação binária via gRPC e arquitetura em camadas.

Tecnologias: Python 3.12 gRPC Protobuf PostgreSQL SQLAlchemy Docker

  - ⚡ gRPC + Protobuf: baixa latência e tipagem estrita
  - 🏛️ Camadas: Models → Repositories → Services → Validators → gRPC Servicers
  - 🛡️ Baixa de estoque atômica: transações com rollback automático (ACID)
  - 🎯 Strategy (OCP): motor extensível para cupons, descontos e regras de
    checkout
  - 🐳 PostgreSQL em container isolado

🐾 ZoeVet

Gestão clínica veterinária com suporte à decisão diagnóstica.

Tecnologias: Python 3.12 Django 5 DRF PostgreSQL 16 Docker Compose Pytest GitHub
Actions

  - 🧠 Motor de diagnóstico com F1-Score: correlaciona sintomas equilibrando
    precisão e sensibilidade
  - 🏛️ Service Layer isolada: DiagnosticoService, ConsultaService e
    TutorService, com redução de 67% na complexidade das Views
  - 🧪 100% de cobertura na camada de serviços com Pytest
  - 🐳 Docker Compose para dev e prod, com CI/CD no GitHub Actions

📊 GitHub Analytics

📫 Vamos conversar?

💼 Aberto a oportunidades como Desenvolvedor Back-End / Engenheiro de Software
(Python, APIs, microsserviços).

LinkedIn Gmail GitHub
