# EldritchCodex

**EldritchCodex** is a set of open-source projects by [Renan Bomtempo](https://github.com/renanbomtempo): the software I build to understand how things work and to use every day. It stands on three pillars: a framework for desktop applications, a renderer, and a personal agent. Tools built on them come next.

Rendering and simulation are still a big part of it: the software architecture, the numerics and the computer graphics behind interactive and scientific applications. They now sit beside the everyday tools that run on the same foundations, such as applications with a command line, and an agent that can reach them.

Each project grows one small working step at a time.

## Projects

- **[Nodens](https://github.com/eldritch-codex/nodens)**: a C++23 application framework built on modules. An app is a stack of layers on top of an interactive loop, with a thread-safe event bus, a multi-threaded job system, windows and input (GLFW), logging (spdlog), an immediate-mode GUI (Dear ImGui and ImPlot) and Tracy profiling built in. Linux for now.
- **[Nyar](https://github.com/eldritch-codex/nyar)**: a real-time Vulkan renderer, built as a separate module for Nodens. It starts from the Khronos "Drawing a triangle" tutorial and is being refactored, step by step, into a clean rendering API that Nodens applications import.
- **Armitage**: a personal agent and research toolkit. It keeps a coding agent honest: every factual claim has to point to your code, your Zotero library or its own memory, or it is cut or marked unverified. Its core stays small, and other tools plug in as plugins that declare what the agent may reach. (Private preview.)

## How they fit

Nodens and Nyar are the foundations for graphics, simulation and desktop applications. Armitage is the agent. Other tools are standalone apps with their own repositories and command lines, and they plug into Armitage only through that command line. Only Nodens and Nyar are public today; the rest will follow once they are well tested.

## Sources

The books, papers and documentation behind the projects are listed in the public [EldritchCodex Zotero library](https://www.zotero.org/groups/6489354/eldritchcodex).

## More

Documentation and project pages: **[eldritchcodex.com](https://eldritchcodex.com)**

---

> "For beyond the veil of our limited understanding there lies an arcane ballet of unseen dimensions."
