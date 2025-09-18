H҉̷̡͇̮̩͔̀̄͠ͅ⎔̴̡͔̦͇͇̋͌t̷̸̲̟̻̽͂͠ͅh̷̶̖̫͎̆̓̚͜͝ȩ̸̢̜̮͋̐͜͠ŗ̵͖̈́̀̎͜͝e̸̷̻̔̏͠⎔̷̧͍̟͇͇̓👋҈̃͏͏̷̛͎̦̱̲ͅ, Į̸̛̳̯̑͗ͅ'̴̟͉̟͋̈́̚͝m̵̞̪̎͜͠ @̷̡̛̮͇̭̳̈́̓⦿̸̡̻̺͈̳̓r̴̡̻̺̀͆͠ą̵͕̤̓̏̚͝k̵̝̀͗͠⦿̵̡̭̯̱̑́̓͝k̶̡̭̯̱̑́̓͝i̶̠̒̈́͆͝1̵̢̲̼̍͘̚9̵͓̰̱̐̈́̌̔͝4̸̗̞̎͜͠
⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇⌇
◯̴̛̖̠̖͖͑̓  Á̵̻̱͇̟̋̓b̷̘̣̀͒̚͝o̸̖̾̓͠͝ů̴̹̰̘͌̓t  M̶̲̓̔͠è̷̛̜̤͌ͅ  ◯̵̛̍̋̕
* H̴͉̙̿̂i — I'm @rakki194. I design infrastructure-first frontends and modular frameworks with a focus on privacy, reproducibility, and pragmatic ergonomics.
* P̷̛͙̿́r̶̦̽͗ơ̴̤͌̽j̴̫̾̚e̵̛̼͊c̶̨͍͜t̶̳̿s̷̮̽ I shepherd: Reynard (framework), utility forks & nodes for ComfyUI, and small, surgical custom nodes (see image-compare node).
⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲

🦊  R̸͎̅ẹ̵̢̀ỹ̸̰̠ǹ̴̜a̴̘̓͜r̶̞̊d̴̖̍ 
From dataset editor → multi-modal CMS → modular SolidJS framework.
W̵̢̲̼̍͘̚h҉̷͉̙̿̂y̸̬̓҉ I b̴̰͓̿̄ů̶̖́͠i̴̠̐̍l̵̛̩͉̐͝t̶̪̺͊ i̸̖̓t̶̪̺͊:
- YipYap proved the patterns; Reynard rips those patterns out, packages them, and hardens them for reuse.
- Goal: ship composable, type-safe UI primitives that scale from a toy dashboard to production pipelines.
- Principles: minimal deps, TypeScript-first, OKLCH color system, strong i18n & accessibility posture.

W̶͐͛͜h̷̶̖̫͎̆̓̚͜͝a̶̭̐t̵̰̾̕ R̸͎̅ẹ̵̢̀ỹ̸̰̠ǹ̴̜a̴̘̓͜r̶̞̊d̴̖̍ *is* (short):
  • SolidJS framework + package ecosystem (core, components, themes, ecs-world, i18n, chat, rag, auth, charts, gallery, annotating, captioning, monaco integration, testing tools).
  • Single authoritative ECS world for agent simulations and MCP server integration where needed.
  • Security testing harness: FENRIR integration for automated exploit sweeps (web + LLM threat vectors).

I҉̬̲̍n̷̮͎̾s̴̖̽̚ẗ̴̝́ă̵͚̇l̶̻̅̅l̸̮͍̊ / b̸̩̑̉o̴̢̬͝o̸͚̔t̶̹̯͊s̶̹̳̿t̴̜̑r̸̹̈́a̶̛͖p̶̝̓ (real snippet):
  pnpm install reynard-core solid-js
  pnpm install reynard-components reynard-chat reynard-rag reynard-auth
  pnpm create reynard-app my-app

T̵̻͠i̶̻̅n̸̖̗̍y̶͎͗ e̵̙̽x̵̤̺̄a̶̱͂m̴̬̣̏̕p̶̺͒͝l̷̩͝e̸̷̻̔̏͠:
  import { createSignal } from "solid-js";
  import { useNotifications } from "reynard-core";
  import { Button, Card } from "reynard-components";
  function App() {
    const { notify } = useNotifications();
    return (
      <Card padding="lg">
        <h1>Welcome to Reynard!</h1>
        <Button onClick={() => notify("Hello from Reynard!", "success")}>Get Started</Button>
      </Card>
    );
  }

K̵̝̀͗͠e̸̷̻̔̏͠y̸̬̓҉, p̴̺͗r̵̭̐̚a̶̭̐c̶̢̟̏t̸̪̓i̷̺̋̽c̶̣̄̿a̶̱͂l̵̛̩͉̐͝ f̴̢̀͒e̵̙̽a̶̭̐t̵̰̾̕ů̶̖́͠r̸̹̈́e̵̙̽s̶̹̳̿ (dense):
  • Multi-modal content types: images, audio, video, docs, custom formats
  • RAG + embedding helpers (EmbeddingGemma integration)
  • Chat streaming + tool hooks (reynard-chat)
  • Full captioning & annotating pipelines with model adapters
  • 8 built-in themes, OKLCH center, WCAG 2.1 compliance, RTL + 37 locales
  • Testing: vitest + happy-dom, playwright e2e, unified reynard-testing utilities
  • Performance: bundle splitting, lazy imports, measured gzipped artifacts (components ≈ 190.7 KB gzipped)

P̶̝̓a̶̭̐c̶̢̟̏k̵̝̀͗͠a̶̭̐g̵̰̀e̸̷̻̔̏͠ h̷̶̖̫͎̆̓̚͜͝i̷̺̋̽g̵̰̀h̷̶̖̫͎̆̓̚͜͝l̵̛̩͉̐͝i̷̺̋̽g̵̰̀h̷̶̖̫͎̆̓̚͜͝t̵̰̾̕s҉̛̞̳̘̱ (what to open first):
  • reynard-core — utilities, notifications, localStorage helpers, validation
  • reynard-components — accessible UI primitives, forms, dialogs
  • reynard-themes — CSS custom properties, theme tokens, runtime switching
  • reynard-ecs-world — authoritative state & agent systems for simulations
  • reynard-monaco — embedded Monaco editor + shiki integration (quick wins for code UIs)

D҉̮̾o̶͔͝c̶̛͖s̵̲̑ & d̵̲͑ȩ̷̟̽v̵̜̙͑ e̵̛̼͊r̶̦̽͗g̶̳̿o̶̧͙̊̽͠ͅn̶̡̅̌o̶̟̎m̵̢̠̒̓i̷̡̓̈́͝c̶̨͍͜s҉̛̞̳̘̱:
  • Quick start + complete tutorial + component API
  • CLI tooling to scaffold apps & components
  • VS Code helpers and a recommended dev stack
⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘⌘

🐺  C҉̥a̶̭̐o̴̪̝̽m̴̬̣̏̕f̴̢̀͒y̸̬̓҉U҉̴̝̳̠̓̃I҉̬̲̍ f̴̢̀͒o̴̪̝̽r̸̹̈́k̵̝̀͗͠s҉̛̞̳̘̱ & n̶̡̅̌o̶̟̎d̴̖̍e̵̙̽s҉̛̞̳̘̱ — privacy first, pragmatic edits
M̶̲̓̔͠y̸̬̓҉ i̸̖̓n̶̗̾̕t̶̪̺͊e̵̙̽n̶̗̾̕t̶̪̺͊:
- Keep the UX & node model intact, remove external tracking, remove lock-in.

W̶͐͛͜h̷̶̖̫͎̆̓̚͜͝a̶̭̐t̵̰̾̕ I҉̬̲̍ c̶̢̟̏h̷̶̖̫͎̆̓̚͜͝a̶̭̐n̶̗̾̕g̵̰̀e̵̙̽d̴̖̍ (surgical list):
- Telemetry removed (no remote usage pings, no datadog/analytics hooks)
- Paid API code paths removed or stubbed (no forced cloud billing flows)
- User-account/login bits removed or made opt-in; default: local / offline mode
- Small upstream contributions: custom nodes (example: ComfyUI-ImageCompare) to improve local workflow QA

W̶͐͛͜h̷̶̖̫͎̆̓̚͜͝y̸̬̓҉ t̶̪̺͊h̷̶̖̫͎̆̓̚͜͝i̷̺̋̽s҉̛̞̳̘̱ m̴̬̣̏̕a̶̭̐t̵̰̾̕t̶̪̺͊e̵̙̽r̸̹̈́s҉̛̞̳̘̱:
- Reproducible offline runs, honest offline research, smaller attack surface, simpler setup for hobbyists & labs.

H̴͉̙̿̂o̴̪̝̽w̸̛͎͉ t̶̪̺͊o̴̪̝̽ r̸̹̈́ů̶̖́͠n̶̗̾̕ l̵̛̩͉̐͝o̴̪̝̽c̶̢̟̏a̶̭̐l̵̛̩͉̐͝l̵̛̩͉̐͝y̸̬̓҉ (ComfyUI forked workflow, short):
  git clone <your-fork>
  python -m venv .venv && .venv/bin/pip install -r requirements.txt
  python main.py --no-telemetry
  (frontend: run packaged frontend or point a custom web client at the local API)
⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲⌲

🔒 S҉̥e̵̙̽c̶̢̟̏ů̶̖́͠r̸̹̈́i̷̺̋̽t̶̪̺͊y̸̬̓҉, t̶̪̺͊e̵̙̽s҉̛̞̳̘̱t̶̪̺͊i̷̺̋̽n̶̗̾̕g̵̰̀, a̶̭̐n̶̗̾̕d̴̖̍ s҉̛̞̳̘̱t̶̪̺͊r̸̹̈́e̵̙̽s҉̛̞̳̘̱s҉̛̞̳̘̱
- FENRIR security sweeps — run automated exploit scans against local deployments:
python -m fenrir.run\_all\_exploits --target [http://localhost:8000](http://localhost:8000)
- Focus areas: prompt injection, streaming exploit resilience, unicode confusables, auth hardening.
- Threat model: untrusted file inputs, LLM chain-of-thought leakage, dependency supply chain.

🧭 P̷̛͙̿́e̵̙̽r̸̹̈́s҉̛̞̳̘̱o̴̪̝̽n̶̗̾̕a̶̭̐l̵̛̩͉̐͝ n̶̗̾̕o̴̪̝̽t̶̪̺͊e̵̙̽s҉̛̞̳̘̱ (why I do this)
- I favor deterministic, inspectable systems. Libraries must fail loudly and be easy to audit.
- I build with the expectation that other engineers will fork and re-use — APIs must be explicit, types must be strict.
- If you want privacy, offline-first setups, or secure RAG demos, Reynard + the privacy-first ComfyUI forks are my opinionated stack.

🔗 Q̶̟̈́̽ů̶̖́͠i̷̺̋̽c̶̢̟̏k̵̝̀͗͠ l̵̛̩͉̐͝i̷̺̋̽n̶̗̾̕k̵̝̀͗͠s҉̛̞̳̘̱
- GitHub: [https://github.com/rakki194](https://github.com/rakki194)
- Project: [https://github.com/rakki194/reynard](https://github.com/rakki194/reynard)
- ComfyUI node (example): [https://github.com/rakki194/ComfyUI-ImageCompare](https://github.com/rakki194/ComfyUI-ImageCompare)
- Forks (examples): [https://github.com/rakki194/ComfyUI](https://github.com/rakki194/ComfyUI)
[https://github.com/rakki194/ComfyUI\_frontend](https://github.com/rakki194/ComfyUI\_frontend)

— e̵̙̽n̶̗̾̕d̴̖̍ o̴̪̝̽f̴̢̀͒ p̷̛͙̿́r̸̹̈́o̴̪̝̽f̴̢̀͒i̷̺̋̽l̵̛̩͉̐͝e̵̙̽ b̴̰͓̿̄l̵̛̩͉̐͝o̴̪̝̽c̶̢̟̏k̵̝̀͗͠ — c̶̢̟̏o̴̪̝̽p̷̛͙̿́y̸̬̓҉, p̷̛͙̿́a̶̭̐s҉̛̞̳̘̱t̶̪̺͊e̵̙̽, i̷̺̋̽t̶̪̺͊e̵̙̽r̸̹̈́a̶̭̐t̶̪̺͊e̵̙̽.\`\`\`

## 📊 G҉̰̀i̷̺̋̽t̶̪̺͊H̴͉̙̿̂ů̶̖́͠b̴̰͓̿̄ S҉̛̞̳̘̱t̶̪̺͊a̶̭̐t̶̪̺͊s҉̛̞̳̘̱
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=rakki194&show_icons=true)
