# THOTH
Local Ai Companion That able to play in desktop and talk with mic.
바탕화면에 3D모델과 함께 마이크로 대화하고 로컬 Ai 컴패니언

# HOW WORK?
## Core Concept
The system runs locally in a Persistent Background Mode, designed for ultra-low idle power consumption. To minimize client-side electricity costs and hardware strain, it utilizes a Distributed Model Architecture (sharding/modularization), activating only the necessary components on demand.

## Base Model
Engine: Meta Llama 3 8B

## Main System Cores (The 10-Core Framework)
Root Core: The central orchestrator that manages system resources and routes tasks.

Dialogue Core: Handles natural language processing and conversational flow.

Advanced Core: Processes high-complexity reasoning and creative tasks.

Logic Core: Dedicated to mathematical, algorithmic, and structured reasoning.

Multi-Function Core: Manages versatile tasks that don't fit into a single category.

Knowledge Core: An indexed RAG (Retrieval-Augmented Generation) or specialized parameter set for factual info.

Tool Core: Manages API calls, function calling, and external software interaction.

Memory Core: Handles long-term/short-term context retention and vector database storage.

Security Core: Monitors for malicious inputs, privacy leaks, and ethical alignment.

Inspection Core: Performs self-correction, hallucination checks, and final output verification.

## Extensibility Cores (Expansion Modules)
Offline Core: Enables functionality without an internet connection (Edge computing focus).

Simulation Core: Runs "what-if" scenarios or predictive modeling in a sandboxed environment.

User Model Core: Personalizes the AI by learning specific user habits, preferences, and writing styles.

## Implementation Strategy for Low Electricity Cost
To achieve your goal of "minimal electricity," I recommend the following technical approach:

Dynamic Quantization: Use 4-bit or 3-bit (GGUF/EXL2) quantization for background cores to reduce VRAM and GPU polling.

Core Gating: Only the Root Core stays active in a "Listen Mode." It acts as a gatekeeper, waking the other cores (Dialogue, Logic, etc.) only when their specific expertise is required.

Distributed Sharding: Distribute the 8B parameters across available compute units (e.g., sharing the load between integrated graphics and dedicated GPU) to prevent any single component from hitting high-wattage peaks.

로컬에서 Ai를 구동하지만 클라이언트측의 전기 요금을 덜 부담하기 위해 항상 백그라운드에서 가동하지만, 최소한의 전기로 작동하고, 부담을 줄이기위해 모델 분산식 방식을 이용합니다.

아래는 모델입니다

1. 루트코어

2. 대화코어

3. 고급코어

4. 로직코어

5. 다기능 코어

6. 지식 코어

7. 툴코어

8. 메모리 코어

9. 보안코어

10. 검수코어



아래는 기본 모델에 붙힐수 있는 확장성 코어입니다.

1. 오프라인 코어

2. 시뮬레이션 코어

3. 유저 모델 코어

기반 모델은 Meta의 LLaMa 3 8B 모델입니다.

# translation
The primary language for this project is Korean. Please be advised that this README.md file was translated from Korean to English using Gemini; therefore, some technical nuances or expressions may be inaccurate.

Thank you for your understanding.

기본 언어는 한국어입니다. 귀하께서 읽고계신 ReadMe.md도 한글 -> 영어로 Gemini를 통해 해석한것으로 부정확할수있습니다.

이용해주셔서 감사합니다.

# How To Use?
나중에 쓸게요^^

# Contributer
Whoasked

Chun.Tak

# IMPORTANT
THOTH's based image made by Gemini

Rigging : Whoasked

토트의 기반 이미지는 제미나이에 의해 생성되었습니다.

리거 : Whoasked
