AWO: Agentic Workflow Orchestration
A multi-agent deep reasoning cluster orchestrating complex codebase Directed Acyclic Graphs (DAGs). Featuring competitive validation networks to achieve token-heavy enterprise scale logic.
Overview
AWO (Agentic Workflow Orchestration) is an enterprise-grade framework designed to solve the "long-context hallucination" and "single-thread logic interruption" problems inherent in monolithic Large Language Models during complex legacy system refactoring and massive private knowledge base analysis.
By breaking down massive directive intents into autonomous Worker Agents and validating them through Adversarial Critic Networks, AWO achieves resilient, self-correcting code generation and system architecture at scale.
Architecture
Dispatcher Node: Tokenizes intent and projects an architectural DAG.
Worker Swarm: Independent context-isolated agents for parallel research and code generation.
Critic Network: Red-team adversarial evaluation ensuring code passes vulnerability and architectural constraint checks before merging.
Getting Started
Prerequisites
Node.js (v18+)
npm or pnpm
MiMo / OpenAI compatible API Key or Gemini API Key
Installation
Clone the repository
```bash
git clone https://github.com/yourusername/awo-swarm-framework.git
cd awo-swarm-framework
```
Install dependencies
```bash
npm install
```
Configure Environment
Copy `.env.example` to `.env.local` and add your API keys:
```env
VITE_OPENAI_API_KEY="your_api_key_here"
VITE_OPENAI_BASE_URL="https://token-plan-cn.xiaomimimo.com/v1"
Or alternatively:
GEMINI_API_KEY="your_gemini_key_here"
```
Run the Development Server
```bash
npm run dev
```
License
MIT License.
