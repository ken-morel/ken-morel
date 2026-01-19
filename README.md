# 👋 Mbolo — I'm Ama (Ken Morel)

> Junior System Developer • Data Science student  
> First-year Software Engineering student | Building systems, UIs, and game tooling

[![Current Project: Gama](https://img.shields.io/badge/project-Gama-blue?logo=github)](https://github.com/ken-morel/gama)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)]

---

Hi — I’m Ken. I build small, developer tools that teach and ship. I love Julia for data work(still learning though), V and C for systems-level control, and WebAssembly + TypeScript for making native things run in the browser or simply building some little svelte project. When I’m not coding or helix, or sleeping, I’m eating, or perhaps watching some anime, designing tiny APIs, or iterating on some game engine idea.

Location: Yaoundé, Cameroon — open to collaborations and mentoring conversations.

---

## What I do now
- Lead development on **Gama**, a lightweight educational C game engine (native + WASM).
- Build reactive UI tooling and templating in Julia (Efus.jl, Ionic.jl).
- Experiment with systems tooling in V, C, and Rust-backed helpers (like rrr).
- Study Data Science in part time, HND level 1 in university.

---

## Top skills & tools
(ordered by priority)
1. Julia
2. Helix (editor)
3. C
4. TypeScript
5. V
6. fish
7. WebAssembly

Other tools I use: fish, Zig, TCC, GitHub Actions, SvelteKit

[![My Skills](https://skillicons.dev/icons?perline=7&i=arch,hx,julia,v,c,fish,wasm,typescript,svelte,github)](https://github.com/ken-morel)

---

## Featured projects

- Gama — A simple C game engine (C, V, TS) 
  https://github.com/ken-morel/gama  
  https://gama.rbs.cm  
  Lightweight, educational engine focused on a small C API, stack-first memory, immediate-mode 2D rendering, and easy WebAssembly builds.

- Efus.jl — Declarative UI templating for Julia  
  https://github.com/ken-morel/Efus.jl  
  A pug-like declarative templating macro that expands to Julian code for building UI components — great for composing Julia UIs.

- Ionic.jl — Reactive primitives for Julia UIs  
  https://github.com/ken-morel/Ionic.jl  
  Provides subscribable values, computed values, and subscription managers used by Efus.jl to build reactive interfaces with tracing and lifecycle helpers.

- rrr — Remote REPL Runner (Rust)  
  https://github.com/ken-morel/rrr  
  Small remote REPL runner that spawns processes and sends/receives commands via tiny shell-friendly tools — useful for automation and remote development scripts.

(See my pinned repositories for runnable examples and demos.)

---

## Quick start — try Gama
Create and run a new Gama project:
```bash
gama new my_first_game
cd my_first_game
gama dev
```

Tiny Gama snippet:
```c
#include <gama.h>

int main() {
  gm_init(600, 400, "Hello Gama!");
  gm_background(GM_DARKSLATEGRAY);

  do () {
    gm_draw_rectangle(0, 0, 0.5, 0.3, GM_RED);
    gm_draw_text(0, 0, "Hello, World!", "", 0.1, GM_WHITE);
  } while(gm_yield());
  return 0;
}
```

---

## How I like to collaborate
- I enjoy working with students and pairing on projects that teach a new concept.
- Open to contributions on Gama, Efus.jl, Ionic.jl, and others — start with an issue or a small enhancement.

---

## Contact & links
- GitHub: [ken-morel](https://github.com/ken-morel)  
- LinkedIn: [Ken Morel](https://www.linkedin.com/in/ken-morel-8ba00a296)  
- X (Twitter): [@kenmorel8](https://twitter.com/kenmorel8)  
- Discord: kenmorel  
- Email: engonken8@gmail.com  
  engon@rbs.cm

---

## A few more things
- Tone: I try to keep things a mix of casual and professional — clear, friendly, and focused on learning.
- Education: First-year Software Engineering student (Level 1) — I apply coursework directly into small OSS projects.
- Fun fact: I’m a big fan of writing little fish scripts to help me with common tasks.
