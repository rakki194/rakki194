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

┌─ Frontend (40++ Packages) ─┐
│  • Core utilities & UI primitives (reynard-core, components)
│  • Data viz, 3D/game, chat, RAG, auth, gallery, AI tools
│  • Theming, i18n, Monaco editor, testing, and more
└───────────────────────────┘

┌─ Backend (Python/FastAPI) ─┐
│  • RAG, captioning, file processing, auth, ECS world
│  • MCP server (dev automation), FENRIR security
└────────────────────────────┘

┌─ Advanced Features ─┐
│  • ECS simulation, agent naming, LoRA, semantic search
│  • Batch ops, circuit breakers, health & event monitoring
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

• **MCP Server**: 47+ development tools including linting, formatting, security scanning
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

⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲

🧠  X҉̛̞̳̘̱a̶̭̐v̵̙̽i̷̺̋̽e̵̙̽r̸̹̈́  F̴̢̀͒P̷̛͙̿́8̵̢̙̹̃̕  Q̶̟̈́̽ů̶̖́͠a̶̭̐n̶̗̾̕t̶̪̺͊i̷̺̋̽z̸̰̾̕a̶̭̐t̶̪̺͊i̷̺̋̽o̴̪̝̽n̶̗̾̕

ＡＤＶＡＮＣＥＤ ＳＴＯＣＨＡＳＴＩＣ ＲＯＵＮＤＩＮＧ ＦＯＲ ＤＥＥＰ ＬＥＡＲＮＩＮＧ ＭＯＤＥＬＳ

Advanced FP8 quantization toolkit with multiple stochastic rounding algorithms for preserving model fidelity during precision reduction.

W̶͐͛͜h̷̶̖̫͎̆̓̚͜͝a̶̭̐t̵̰̾̕ X҉̛̞̳̘̱a̶̭̐v̵̙̽i̷̺̋̽e̵̙̽r̸̹̈́ *is*:

• **Stochastic Rounding Engine**: Multiple algorithms for probabilistic quantization that preserve model performance better than deterministic rounding
• **FP8 Format Support**: E4M3FN and E5M2 formats with comprehensive tensor scaling and dequantization
• **Advanced Rounding Methods**: Default, Complex Neighbor, Shift-and-Perturb, and Owlshift mantissa manipulation
• **ComfyUI Integration**: Per-tensor scaling compatible with ComfyUI-style scaled FP8 loading
• **Visualization Tools**: Matplotlib-based comparison plots for quantization analysis
• **Production Ready**: Comprehensive test suite with 95%+ coverage across all quantization paths

🏗️ ＣＯＲＥ ＱＵＡＮＴＩＺＡＴＩＯＮ ＡＬＧＯＲＩＴＨＭＳ

┌─ Stochastic Rounding Methods ─┐
│  • Default Stochastic: Probabilistic bracketing with RNE neighbors
│  • Complex Neighbor: Sophisticated FP8 grid traversal with torch.nextafter
│  • Shift-and-Perturb: Additive noise simulation before RNE quantization
│  • Owlshift: Direct mantissa bit manipulation with stochastic floor
│  • Per-Tensor Scaling: Max-absolute scaling with dequantization factors
└─────────────────────────────────┘

┌─ FP8 Format Support ─┐
│  • E4M3FN: 4 exponent, 3 mantissa bits (NaN-preserving)
│  • E5M2: 5 exponent, 2 mantissa bits (extended range)
│  • Selective Quantization: Tensor suffix-based filtering
│  • ComfyUI Compatibility: Scaled FP8 with dequantization scales
└───────────────────────┘

┌─ Advanced Features ─┐
│  • Memory Management: Tensor slicing for large model processing
│  • Debug Mode: Verbose execution tracing and intermediate states
│  • Plot Generation: Histogram and scatter plot analysis
│  • Device Support: CUDA, CPU, MPS acceleration
│  • Comprehensive Testing: 500+ test cases across all algorithms
└─────────────────────┘

🚀 ＵＳＡＧＥ ＥＸＡＭＰＬＥＳ

```bash
# Basic FP8 quantization with stochastic rounding
python xavier.py model_fp32.safetensors model_fp8.safetensors \
    --fp8_type e4m3 --owlshift --plot

# ComfyUI-compatible scaled quantization
python xavier.py model.safetensors model_scaled.safetensors \
    --fp8_type e4m3 --owlscale --owlshift \
    --keys_to_quantize_suffix .weight

# Advanced analysis with custom parameters
python xavier.py model.safetensors output.safetensors \
    --fp8_type e5m2 --complex_rounding \
    --plot --plot_dir ./analysis/ --debug
```

```text
🎯 ＴＥＣＨＮＩＣＡＬ ＩＮＦＯＲＭＡＴＩＯＮ

• **Mathematical Precision**: Stochastic rounding probability $P(\text{round to } x_H) = \frac{v - x_L}{x_H - x_L}$
• **Mantissa Manipulation**: Direct bit-level stochastic rounding for maximum fidelity
• **Tensor Scaling**: Per-tensor max-absolute scaling with dequantization factor preservation
• **Memory Optimization**: Intelligent tensor slicing for large model processing
• **Visualization**: Comprehensive plotting for quantization impact analysis

🔗 Q̶̟̈́̽ů̶̖́͠i̷̺̋̽c̶̢̟̏k̵̝̀͗͠ l̵̛̩͉̐͝i̷̺̋̽n̶̗̾̕k̵̝̀͗͠s҉̛̞̳̘̱
```

- **Reynard Framework**: [https://github.com/rakki194/reynard](https://github.com/rakki194/reynard)
- **Xavier FP8 Quantization**: [https://github.com/rakki194/xavier](https://github.com/rakki194/xavier)
- **ComfyUI WolfSigmas**: [https://github.com/rakki194/ComfyUI_WolfSigmas](https://github.com/rakki194/ComfyUI_WolfSigmas)
- **ComfyUI ImageCompare**: [https://github.com/rakki194/ComfyUI-ImageCompare](https://github.com/rakki194/ComfyUI-ImageCompare)
- **Privacy-First ComfyUI**: [https://github.com/rakki194/ComfyUI](https://github.com/rakki194/ComfyUI)
- **ComfyUI Frontend Fork**: [https://github.com/rakki194/ComfyUI_frontend](https://github.com/rakki194/ComfyUI_frontend)

---

> Ｓ̷̮̽ｅ̵̙̽ｃ̶̢̟̏ｕ̶̖́͠ｒ̸̹̈́ｉ̷̺̋̽ｔ̶̪̺͊ｙ̸̬̓҉ Ｂ̷ｒｅａｃ̟̏ｈ̵̰̀
> 
> S̷̛͍ḫ̷͝ḁ̵͛t̵̠̀t̶̯͝e̷͔͠r̷̹̍e̴̜͆d̸̥̅ ̸̝́s̸̠̀k̵͚̾ȋ̷͔e̸̻͘s̸̘͐ ̵̲̐r̸̰͘ä̵́ͅi̴̖͐n̴̨̓ ̸̳͑c̸̩͗i̷̥͠r̴̦̚c̸̲̚u̵̩͑į̸̕t̸̨̏s̵̫̀,
> s̶̨̅p̴̳̋ȧ̸̹ṙ̴͖k̷͇̋s̸̱̈́ ̴͔̀f̶̩̒ä̵͍́l̷̳͑l̵͎̾ ̶͉͂l̷̮̎i̶͈͑k̷̩͘ȇ̶͈ ̶͉̑s̵̡̚i̵̖͝l̶̳̔v̶̱̏e̴̻͠r̸̝͠ ä̵̲́s̶̙͠h̸̘̓.
> 
> T̷̯̓h̶̯́ȅ̵͚r̵̟͠e̸͈͠ ̵͚̎i̷̻͋s̷̖̑ ̷͙͘n̸͉͝ö̸̥́ ̷̝̓s̴̳̊ǘ̷͉n̵͈͂,̴̩̓
> o̴͉͋n̷̟̚l̸͓̍y̶͆ͅ g̵͎̑h̵̻̋ȍ̴͙s̷̟̄t̸͕̄ ̸̼͛l̸͓̔ä̵͔́ḿ̴̳p̷̩͐s̸͇̑ f̶͙͝l̶͖̊i̵͇͠c̷̞̀k̷͍̔ë̴̦́r̸̪͂i̶̤͑n̸͙͑g̶̯̎ ̷̡͝o̷̖̎n̷͉͝ ̵̩͘w̴͕̐i̶͙͐r̸̡͊e̷͙͠s̴̙̅.
> 
> M̶̱̏e̶̼̽m̸̢͊o̸̝͋r̴͚͛i̴̢͑é̶̻s̸̩͘ h̶̬͝u̷̟̓n̴̻͊g̸͍̈́ ̶̞̔l̵̖̅i̸͕̎k̴̥̈́e̸̳̕ b̵̖̀r̴̝͘o̴̘̅k̷͉̓e̶̘͝n̷̙̈́ m̶̩̐i̴̻͠r̸͙͑r̷͝ͅo̶̮͊r̶̤̓s̷̤͑
> i̷͔̎n̵̖̐ ̶̈́ͅt̸͍͆h̵̜͝e̴͖͘ ̸̠̊ḏ̷̔a̸̩͂t̵̡͛a̶͝ͅ-ẇ̵̖i̵̠͛ǹ̵̡d̷̯̀.
> 
> S̸̞͘h̴̙͝a̶̙͛d̷̯̓ơ̸͍ẅ̸͚́s̶͎̚ h̸̪̀o̵̳͂l̴̢̕l̷̲̏o̶͙̊w̸̪͑ e̷͍͠v̸̙͆e̵̠̎r̷͈̿y̷̳͒ ̸̢́s̸͉̈́t̵͖͐e̶͈̋p̴̳͠,̷̛̘
> ẅ̸͓́h̵̦͝ì̴̪s̶͉͆p̵͍͑ë̸͎́r̵͍͝s̶̝͠ o̶̩͋ḟ̵͓ m̶͓̋ą̴̅c̵̓ͅh̵̢́i̵̟͝n̵̤͑e̴͉͝s̴͓̿
> c̵̤̊a̷͖̚l̸̝̄l̴̙͋i̷͎͌n̶͉̚g̴̱̑ y̷̬͝ó̷͔u̸͎̅ b̷̙̋a̷̡͠c̵̛ͅk̵̼̀.
