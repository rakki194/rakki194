```
H҉̷̡͇̮̩͔̀̄͠ͅ⎔̴̡͔̦͇͇̋͌t̷̸̲̟̻̽͂͠ͅh̷̶̖̫͎̆̓̚͜͝ȩ̸̢̜̮͋̐͜͠ŗ̵͖̈́̀̎͜͝e̸̷̻̔̏͠⎔̷̧͍̟͇͇̓👋҈̃͏͏̷̛͎̦̱̲ͅ, Į̸̛̳̯̑͗ͅ'̴̟͉̟͋̈́̚͝m̵̞̪̎͜͠ @̷̡̛̮͇̭̳̈́̓⦿̸̡̻̺͈̳̓r̴̡̻̺̀͆͠ą̵͕̤̓̏̚͝k̵̝̀͗͠⦿̵̡̭̯̱̑́̓͝k̶̡̭̯̱̑́̓͝i̶̠̒̈́͆͝1̵̢̲̼̍͘̚9̵͓̰̱̐̈́̌̔͝4̸̗̞̎͜͠

⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇

◯̴̛̖̠̖͖͑̓  Á̵̻̱͇̟̋̓b̷̘̣̀͒̚͝o̸̖̾̓͠͝ů̴̹̰̘͌̓t  M̶̲̓̔͠è̷̛̜̤͌ͅ  ◯̵̛̍̋̕

* I design frameworks, security tools, and diffusion utilities with a strong emphasis on privacy, reproducibility,
  and type safety.
* My work spans Reynard, a modular SolidJS framework, to hardened forks of ComfyUI that remove telemetry and lock-ins,
  to advanced sigma scheduling and probing utilities.
* I value deterministic systems, reproducibility, and making tools auditable, forkable, and offline-friendly.
* P̷̛͙̿́r̶̦̽͗ơ̴̤͌̽j̴̫̾̚e̵̛̼͊c̶̨͍͜t̶̳̿s̷̮̽  I shepherd: Reynard (framework), forks & nodes for ComfyUI, and surgical custom nodes.

⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲

🦊  ＲＥＹＮＡＲＤ  ＦＲＡＭＥＷＯＲＫ

Ｔｈｅ  Ａｐｅｘ  Ｐｒｅｄａｔｏｒ  ｏｆ  Ｍｏｄｕｌａｒ  ＳｏｌｉｄＪＳ  Ｄｅｖｅｌｏｐｍｅｎｔ

From dataset editor → multi-modal CMS → modular SolidJS framework.

W̵̢̲̼̍͘̚h҉̷͉̙̿̂y̸̬̓҉ I b̴̰͓̿̄ů̶̖́͠i̴̠̐̍l̵̛̩͉̐͝t̶̪̺͊ i̸̖̓t̶̪̺͊:

- YipYap proved the patterns; Reynard rips those patterns out, packages them, and hardens them for reuse.
- Goal: ship composable, type-safe UI primitives that scale from a toy dashboard to production pipelines.
- Principles: minimal deps, TypeScript-first, OKLCH color system, strong i18n & accessibility posture.

W̶͐͛͜h̷̶̖̫͎̆̓̚͜͝a̶̭̐t̵̰̾̕ R̸͎̅ẹ̵̢̀ỹ̸̰̠ǹ̴̜a̴̘̓͜r̶̞̊d̴̖̍ *is*:

  • SolidJS framework + package ecosystem (40+ specialized packages)
  • Single authoritative ECS world for agent simulations and MCP server integration
  • Security testing harness: FENRIR integration for automated exploit sweeps
  • Production-ready AI/ML integration with caption generation, RAG, and multimodal capabilities
  • Advanced theming system with OKLCH color space and comprehensive theme management
  • Built-in internationalization with RTL support and translation management
  • Enterprise-grade authentication and authorization with Gatekeeper service
  • Comprehensive file processing and multimodal repository management
  • Real-time collaboration tools with WebSocket integration
  • Advanced 3D rendering and game engine capabilities

🏗️ ＣＯＲＥ ＡＲＣＨＩＴＥＣＴＵＲＥ

┌─ Frontend Ecosystem (40+ Packages) ─┐
│  • reynard-core: Foundation utilities and reactive primitives
│  • reynard-components: Production-ready UI component library
│  • reynard-charts: Advanced data visualization with D3.js integration
│  • reynard-3d: Three.js-based 3D rendering and game engine
│  • reynard-games: ECS-based game development framework
│  • reynard-chat: Real-time messaging and collaboration
│  • reynard-rag: Retrieval-Augmented Generation system
│  • reynard-auth: JWT-based authentication with social providers
│  • reynard-gallery: Advanced media gallery with AI integration
│  • reynard-annotating: Multi-model AI caption generation
│  • reynard-caption: Intelligent image captioning system
│  • reynard-multimodal: Cross-modal data processing
│  • reynard-i18n: Comprehensive internationalization
│  • reynard-themes: OKLCH-based theming system
│  • reynard-monaco: VS Code editor integration
│  • reynard-testing: Comprehensive testing utilities
|  • .. and more!
└─────────────────────────────────────┘

┌─ Backend Services (Python/FastAPI) ─┐
│  • RAG Service: Vector embeddings + PostgreSQL + pgvector
│  • Caption Generation: JTP2, JoyCaption, Florence2, WDv3
│  • File Processing: Multi-format support with metadata extraction
│  • Authentication: Gatekeeper service with multiple backends
│  • ECS World: Agent simulation with trait inheritance
│  • MCP Server: 47 tools for development automation
│  • Security: FENRIR automated exploit scanning
└─────────────────────────────────────┘

┌─ Advanced Features ─┐
│  • ECS World Simulation: Time-accelerated agent ecosystems
│  • Agent Naming System: Animal spirit-based identity generation
│  • LoRA Integration: Personality modeling for AI agents
│  • Semantic Search: Vector-based content discovery
│  • Batch Processing: Efficient multi-file operations
│  • Circuit Breakers: Fault tolerance and error handling
│  • Health Monitoring: Real-time system metrics
│  • Event System: Comprehensive logging and monitoring
└─────────────────────┘

🚀 ＩＮＳＴＡＬＬＡＴＩＯＮ ／ ＢＯＯＴＳＴＲＡＰ
```

```bash
# Core framework
pnpm install reynard-core solid-js
pnpm install reynard-components reynard-chat reynard-rag reynard-auth

# AI/ML capabilities
pnpm install reynard-annotating reynard-caption reynard-multimodal

# Advanced features
pnpm install reynard-3d reynard-games reynard-charts reynard-monaco

# Create new project
pnpm create reynard-app my-app
```

```
🎭 ＥＸＡＭＰＬＥＳ ＡＮＤ ＴＥＭＰＬＡＴＥＳ

• **Comprehensive Dashboard**: Full-featured admin interface with charts, tables, and real-time updates
• **Image Caption App**: AI-powered image processing with multi-model caption generation
• **3D Demo**: Three.js integration with interactive 3D scenes and game mechanics
• **Auth App**: Complete authentication flow with social providers and JWT
• **RAG Demo**: Retrieval-Augmented Generation with vector search and embeddings
• **ECS Agent Tracker**: Real-time agent simulation with trait inheritance and breeding
• **Algorithm Benchmarks**: Performance testing and optimization tools
• **I18n Demo**: Internationalization showcase with RTL support
• **Multi-Theme**: Dynamic theming with OKLCH color space
• **Error Demo**: Comprehensive error handling and boundary management

🔧 ＤＥＶＥＬＯＰＭＥＮＴ ＴＯＯＬＳ

• **MCP Server**: 47 development tools including linting, formatting, security scanning
• **Agent Naming**: Animal spirit-based identity system with trait inheritance
• **ECS World**: Time-accelerated simulation with genetic algorithms
• **FENRIR Security**: Automated exploit scanning for web and LLM threat vectors
• **Comprehensive Testing**: Unit, integration, and E2E testing with Playwright
• **Documentation Generator**: Automated API documentation and guides
• **Monorepo Management**: Advanced package orchestration and dependency management

⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘

🐺  C҉̥o̴̪̝̽m̴̬̣̏̕f̴̢̀͒y̸̬̓҉U҉̴̝̳̠̓̃I҉̬̲̍ W̶̲̓̔͠o̴̪̝̽l̵̛̩͉̐͝f̴̢̀͒ Ṩ̵̢̙̹̃̕i̷̺̋̽g̵̰̀m̴̬̣̏̕a̶̭̐s҉̛̞̳̘̱

ＡＤＶＡＮＣＥＤ ＤＩＦＦＵＳＩＯＮ ＳＡＭＰＬＩＮＧ ＡＮＤ ＳＩＧＭＡ ＳＣＨＥＤＵＬＩＮＧ ＴＯＯＬＫＩＴ ＦＯＲ ＣｏｍｆｙＵＩ

- S҉̛̞̳̘̱c̶̢̟̏r̸̹̈́i̷̺̋̽p̷̛͙̿́t̶̪̺͊a̶̭̐b̴̰͓̿̄l̵̛̩͉̐͝e̵̙̽ s҉̛̞̳̘̱i̷̺̋̽g̵̰̀m̴̬̣̏̕a̶̭̐ g̵̰̀e̵̙̽n̶̗̾̕e̵̙̽r̸̹̈́a̶̭̐t̶̪̺͊i̷̺̋̽o̴̪̝̽n̶̗̾̕ & sampler logic
- Ｍ̴̬̣̏̕ｏ̴̪̝̽ｄ̴̖̍ｅ̵̙̽ｌ̵̛̩͉̐͝ i̷̺̋̽ｎ̶̗̾̕ｔ̶̪̺͊ｒ̸̹̈́ｏ̴̪̝̽ｓ҉̛̞̳̘̱ｐ̷̛͙̿́ｅ̵̙̽ｃ̶̢̟̏ｔ̶̪̺͊ｉ̷̺̋̽ｏ̴̪̝̽ｎ̶̗̾̕ utilities (list blocks, visualize activations)
- E҉̛̞̳̘̱x̸̰̾̕p̷̛͙̿́e̵̙̽r̸̹̈́i̷̺̋̽m̴̬̣̏̕e̵̙̽n̶̗̾̕t̶̪̺͊a̶̭̐l̵̛̩͉̐͝ ＳＶＤ̴̖̍ ａ̶̭̐ｃ̶̢̟̏ｔ̶̪̺͊ｉ̷̺̋̽ｖ̵̙̽ａ̶̭̐ｔ̶̪̺͊ｉ̷̺̋̽ｏ̴̪̝̽ｎ̶̗̾̕ modification
- W҉̛̞̳̘̱o̴̪̝̽l̵̛̩͉̐͝f̴̢̀͒P̷̛͙̿́r̸̹̈́o̴̪̝̽b̴̰͓̿̄e̵̙̽ for deep model debugging w̶̲̓̔͠i̷̺̋̽t̶̪̺͊h̷̶̖̫͎̆̓̚͜͝ f̴̢̀͒o̴̪̝̽r̸̹̈́w҉̛̞̳̘̱a̶̭̐r̸̹̈́d̴̖̍/b̴̰͓̿̄a̶̭̐c̶̢̟̏k̵̝̀͗͠w҉̛̞̳̘̱a̶̭̐r̸̹̈́d̴̖̍ h̷̶̖̫͎̆̓̚͜͝o̴̪̝̽o̴̪̝̽k̵̝̀͗͠s҉̛̞̳̘̱
- C҉̥u̸̖̓s҉̛̞̳̘̱t̶̪̺͊o̴̪̝̽m̴̬̣̏̕ ｎ̶̗̾̕ｏ̴̪̝̽ｉ̷̺̋̽ｓ҉̛̞̳̘̱ｅ̵̙̽ generators (DCT, scriptable, structured Perlin)

F̵̙̈́ȩ̷̟̽a̶̭̐t̸̪̓ů̶̖́͠r̸̹̈́e̵̙̽ ＨＩ̶̠̐̍Ｇ̵̰̀Ｈ̷̶̖̫͎̆̓̚͜͝Ｌ̵̛̩͉̐͝Ｉ̷̺̋̽Ｇ̵̰̀Ｈ̷̶̖̫͎̆̓̚͜͝Ｔ̴̪̺͊Ｓ̷̮̽:

- ★ FLUX/DiT/Chroma model support for activation visualization
- ★ JSON sigma schedule import/export workflows
- ★ Transform utilities: power, clamp, quantize, reverse, slice

🎭 C҉̥o̴̪̝̽m̴̬̣̏̕f̴̢̀͒y̸̬̓҉ f̴̢̀͒o̴̪̝̽r̸̹̈́k̵̝̀͗͠s҉̛̞̳̘̱ — p̷̛͙̿́r̸̹̈́i̷̺̋̽v̶̹̯̕a̶̭̐c̶̢̟̏y̸̬̓҉ Ｆ̴̢̀͒Ｉ̷̺̋̽Ｒ̸̹̈́Ｓ̷̮̽Ｔ̴̪̺͊, p̷̛͙̿́r̸̹̈́a̶̭̐g̵̰̀m̴̬̣̏̕a̶̭̐t̶̪̺͊i̷̺̋̽c̶̢̟̏ e̵̙̽d̴̖̍i̷̺̋̽t̶̪̺͊s҉̛̞̳̘̱

M̶̲̓̔͠y̸̬̓҉ i̸̖̓n̶̗̾̕t̶̪̺͊e̵̙̽n̶̗̾̕t̶̪̺͊:

- Keep the UX & node model intact, remove external tracking, remove lock-in.

W̶͐͛͜h̷̶̖̫͎̆̓̚͜͝a̶̭̐t̵̰̾̕ I҉̬̲̍ c̶̢̟̏h̷̶̖̫͎̆̓̚͜͝a̶̭̐n̶̗̾̕g̵̰̀e̵̙̽d̴̖̍:

- Telemetry removed (no remote usage pings, no datadog/analytics hooks)
- Paid API code paths removed or stubbed (no forced cloud billing flows)  
- User-account/login bits removed or made opt-in; default: local / offline mode

W̶͐͛͜h̷̶̖̫͎̆̓̚͜͝y̸̬̓҉ t̶̪̺͊h̷̶̖̫͎̆̓̚͜͝i̷̺̋̽s҉̛̞̳̘̱ m̴̬̣̏̕a̶̭̐t̵̰̾̕t̶̪̺͊e̵̙̽r̸̹̈́s҉̛̞̳̘̱:

- Reproducible offline runs, honest offline research, smaller attack surface, simpler setup for hobbyists & labs.

⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲

🔒 Ｓ̷̮̽ｅ̵̙̽ｃ̶̢̟̏ｕ̶̖́͠ｒ̸̹̈́ｉ̷̺̋̽ｔ̶̪̺͊ｙ̸̬̓҉ ＆ Ａ̶̭̐ｎ̶̗̾̕ａ̶̭̐ｌ̵̛̩͉̐͝ｙ̸̬̓҉ｓ̷̮̽ｉ̷̺̋̽ｓ̷̮̽
- FENRIR security sweeps — run automated exploit scans against local deployments:

    ```bash
    python -m fenrir.run_all_exploits --target http://localhost:8000
    ```

- Focus areas: prompt injection, streaming exploit resilience, unicode confusables, auth hardening.
- Threat model: untrusted file inputs, LLM chain-of-thought leakage, dependency supply chain.

🌊 D҉̮ę̷̟̽e̵̙̽p̷̛͙̿́ Ｄ̴̖̍ｉ̷̺̋̽ｆ̴̢̀͒ｆ̴̢̀͒ｕ̸̖̓ｓ̷̮̽ｉ̷̺̋̽ｏ̴̪̝̽ｎ̶̗̾̕ Ｒ̸̹̈́ｅ̵̙̽ｓ̷̮̽ｅ̵̙̽ａ̶̭̐ｒ̸̹̈́ｃ̶̢̟̏ｈ̷̶̖̫͎̆̓̚͜͝

I̷̺̋̽n̶̗̾̕v̶̹̯̕e̵̙̽s҉̛̞̳̘̱t̶̪̺͊i̷̺̋̽g̵̰̀a̶̭̐t̶̪̺͊i̷̺̋̽n̶̗̾̕g̵̰̀:

- ★ Ｓ̷̮̽ｉ̷̺̋̽ｇ̵̰̀ｍ̴̬̣̏̕ａ̶̭̐ ｓ҉̛̞̳̘̱ｃ̶̢̟̏ｈ̷̶̖̫͎̆̓̚͜͝ｅ̵̙̽ｄ̴̖̍ｕ̸̖̓ｌ̵̛̩͉̐͝ｉ̷̺̋̽ｎ̶̗̾̕ｇ̵̰̀ dynamics & custom noise patterns
- ★ Ｎ̶̗̾̕ｅ̵̙̽ｕ̸̖̓ｒ̸̹̈́ａ̶̭̐ｌ̵̛̩͉̐͝ activation flow analysis through targeted model introspection
- ★ Ｓ̷̮̽ＶＤ̴̖̍ ｍ̴̬̣̏̕ａ̶̭̐ｎ̶̗̾̕ｉ̷̺̋̽ｐ̷̛͙̿́ｕ̸̖̓ｌ̵̛̩͉̐͝ａ̶̭̐ｔ̶̪̺͊ｉ̷̺̋̽ｏ̴̪̝̽ｎ̶̗̾̕ ｏ̴̪̝̽ｆ̴̢̀͒ model activation layers for interpretability
- ★ Ａ̶̭̐ｄ̴̖̍ｖ̵̙̽ｅ̵̙̽ｒ̸̹̈́ｓ҉̛̞̳̘̱ａ̶̭̐ｒ̸̹̈́ｉ̷̺̋̽ａ̶̭̐ｌ̵̛̩͉̐͝ ｒ̸̹̈́ｏ̴̪̝̽ｂ̴̰͓̿̄ｕ̸̖̓ｓ҉̛̞̳̘̱ｔ̶̪̺͊ｎ̶̗̾̕ｅ̵̙̽ｓ҉̛̞̳̘̱ｓ҉̛̞̳̘̱ in sampling workflows

🔗 Q̶̟̈́̽ů̶̖́͠i̷̺̋̽c̶̢̟̏k̵̝̀͗͠ l̵̛̩͉̐͝i̷̺̋̽n̶̗̾̕k̵̝̀͗͠s҉̛̞̳̘̱

- **Reynard Framework**: [https://github.com/rakki194/reynard](https://github.com/rakki194/reynard)
- **ComfyUI Wolf Sigmas**: [https://github.com/rakki194/ComfyUI_WolfSigmas](https://github.com/rakki194/ComfyUI_WolfSigmas)
- **ComfyUI ImageCompare**: [https://github.com/rakki194/ComfyUI-ImageCompare](https://github.com/rakki194/ComfyUI-ImageCompare)
- **Privacy-First ComfyUI**: [https://github.com/rakki194/ComfyUI](https://github.com/rakki194/ComfyUI)
- **ComfyUI Frontend Fork**: [https://github.com/rakki194/ComfyUI_frontend](https://github.com/rakki194/ComfyUI_frontend)

---
```
