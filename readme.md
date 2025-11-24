
---

# 🕹️ Revolution JS Game Boy Emulator

**Powered by RJS — Revolution JavaScript**

A Game Boy emulator built with **RJS (Revolution JavaScript)** — a next-generation, compact, high-productivity JavaScript superset.
This repository is released as the **Public Open-Core Edition**, allowing developers to study, fork, and contribute under **MPL 2.0**.

---

## 🚀 Features (Public Edition)

* CPU: LR35902 interpreter (Work-in-Progress)
* WebGL renderer (BG tiles, Window, Sprites)
* VRAM & OAM emulation
* Cartridge loader (*.gb ROM)
* Frame loop system (requestAnimationFrame)
* Instruction tracing & debug logs
* RJS → JavaScript compiled output


---

## 🧠 About RJS (Revolution JavaScript)

RJS is a compact, expressive, and highly productive JavaScript dialect featuring:

* Python-like readability
* Clean DSL-like syntax
* Special operators (`:=`, `::`, `:>`, `:e`, `:~`)
* Zero-runtime overhead
* A custom compiler (closed-source)

This emulator serves as a **showcase project** demonstrating how RJS scales to real systems.


---

# 🧩 Licensing Model (Open-Core)

This project follows an **Open-Core Model**:

### ✔ Public Edition (this GitHub version)

* Licensed under **MPL 2.0**
* You may use, study, modify, fork, and distribute
* If you modify any existing file → the modified version of *that file* must remain MPL-licensed
* New files you create can be licensed however you like

### ✔ Proprietary Editions (reserved by the author)

The author (Peacedeveloper@gmail.com) reservers the right to release advanced, non-open-source editions in the future, including:

* Optimized / JIT versions
* GPU-accelerated pipelines
* Advanced debuggers & visualization tools
* Full RJS development suite
* Commercial / Pro editions

These versions may be proprietary, closed-source, or sold commercially.

This is **fully allowed** under MPL 2.0 and clearly stated here to ensure fairness and transparency. Contributors are *not* affected by proprietary editions; their code remains under MPL in the public layer.

---

# 🙌 Contributing

Contributions are welcome for the Public Edition, especially in:

* CPU accuracy & timing
* PPU timing and rendering
* Audio channel emulation (future)
* Performance improvements
* ROM compatibility
* Testing & debugging
* Documentation

By submitting a pull request:

* You retain copyright to your own code
* You grant the project an MPL license to your contribution
* You acknowledge this project uses an Open-Core model

This keeps everything legally clean and respectful.

---

# 🎯 Project Goals

* Build a clean, readable Game Boy emulator
* Demonstrate real-world usage of RJS
* Create a solid and approachable emulator codebase
* Grow a community-friendly public layer
* Prepare the foundation for future Pro/Advanced editions

---

# ⚡ Running the Emulator


```
npx http-server .
```

Then load any `.gb` ROM and hit **Start**.

---

# 🧙 Author

**Peace Developer**
Creator of **RJS — Revolution JavaScript**
Software Engineer · System Architect · RJS Founder

---

# 📝 License — MPL 2.0

See the `LICENSE` file for full terms.

---