# EldritchCodex

**EldritchCodex** is a learning project by [Renan Bomtempo](https://github.com/renanbomtempo) exploring the engineering and mathematics of rendering and simulation tools: the software architecture, the numerics and the computer graphics behind interactive and scientific applications.

It is a set of open-source projects built to understand how these systems work, one small working step at a time.

## Projects

- **[Nodens](https://github.com/eldritch-codex/nodens)**: a C++23 application framework built on modules. An app is a stack of layers on top of an interactive loop, with a thread-safe event bus, a multi-threaded job system, cross-platform windows and input (GLFW), logging (spdlog), an immediate-mode GUI (Dear ImGui and ImPlot) and Tracy profiling built in.
- **[Nyar](https://github.com/eldritch-codex/nyar)**: a real-time Vulkan renderer, built as a separate module for Nodens. It starts from the Khronos "Drawing a triangle" tutorial and is being refactored, step by step, into a clean rendering API that Nodens applications import.
- **Armitage**: a source-grounded research and coding agent toolkit. It keeps a coding agent honest: every factual claim has to point to your code, your Zotero library or its own memory, or it is cut or marked unverified. (Private preview.)

## Sources

The books, papers and documentation behind the projects are listed in the public [EldritchCodex Zotero library](https://www.zotero.org/groups/6489354/eldritchcodex).

## More

Documentation and project pages: **[eldritchcodex.com](https://eldritchcodex.com)**

---

> "For beyond the veil of our limited understanding there lies an arcane ballet of unseen dimensions."
