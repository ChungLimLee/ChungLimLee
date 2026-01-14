# 👋 Hi, I'm Chung Lim Lee

I'm a self-taught developer who builds technically deep, performance-focused JavaScript applications.  
I care about how things actually work — from memory efficiency to input latency to browser quirks — and I build from scratch when existing tools don’t cut it.
I am the founder and maintainer of [Savvy Open](https://savvyopen.com)

---

### [**Web Chat System** – SSE, Portable History, Group Chat, Incremental Updates & Session Control](https://github.com/ChungLimLee/SoChat)

**Overview:**
A secure, real-time web chat system built from scratch using PHP, JavaScript, HTML, and MySQL. Designed to demonstrate advanced features that typical frameworks don’t provide by default.

**Key Features:**

* **Real-time communication:** Uses Server-Sent Events (SSE) for live messaging.
* **User-specific history:** All chat histories are portable across devices.
* **Incremental updates:** After the initial load, only new messages are sent from the server to minimize data transfer.
* **Single-session enforcement:** Automatically disconnects older connections when a user logs in elsewhere.
* **Group chat support:** Users can create and join group chats.
* **Security-focused:** Secure session management, password hashing (client + server), and SQL injection protection.

**Highlights:**

* Fully functional system within ~50 KB of code.
* Minimal dependencies; no frameworks used to maintain fine-grained control.
* Live-tested over 2 years on multiple devices.

---

## 🚀 [SoGloper 0.8.0-alpha](https://github.com/ChungLimLee/so-gloper-react)

A **unified React library** for state, logic, and dataflow — all in one, with minimal boilerplate.

**Why it’s unique:**

* **Dual Modes:** Relax (simple) & Control (advanced, IDE-friendly)
* **Dynamic State Creation:** `createGloper` for programmatic, flexible state
* **Uniform Namespaces** with conflict detection
* **Built-in Persistence:** IndexedDB & LocalStorage
* **Lazy Loading:** initialize heavy states only on first use
* **Auto Immutable Updates** & React 18+ concurrency support

Build scalable, maintainable React apps faster — without juggling multiple libraries.

---

### 🎮 [SO Othello – Unlimited Endgame Puzzle](https://github.com/ChungLimLee/soOthello)
A fully interactive Othello app in JS with unlimited endgame puzzles, study mode, puzzle sharing via link, and perfect-play solving.

- Generates **solvable endgame puzzles** from any board with 12 or more empty squares.
- Three versions of board representations:
  - A currently published version uses **1D-array** with unique optimized move generations.
  - A custom **bitboard** implementation enables compact binary operations, achieving up to **10× faster performance** than the 1D array.
  - A novel, self-developed **SO-board** that **outperforms** bitboards in certain metrics and shows potential for even greater overall speed.
- Allows **puzzle sharing via link** to LinkedIn, X (Twitter), WhatsApp, and Facebook — so users can easily share, discuss, and revisit specific puzzle states.
- Supports **undo/redo**, win/draw/loss outcome classification, and best-move exploration.
- Self-published and accepted by [https://worldothello.org.](https://www.worldothello.org/news/435/open-book-of-othello)

> ⚙️ Not just a game — a tool for strategy study and perfect-play exploration.

---

### 🗄️ [soStorage.js – LocalStorage-Like API Using IndexedDB](https://github.com/ChungLimLee/soStorage.js)
A tiny, zero-dependency JavaScript library that provides a **localStorage-like API**, backed by **IndexedDB** for modern browser storage.

- Use it just like `localStorage`, but with full support for:
  - **Structured data types** (objects, arrays, numbers, etc.)
  - **Larger data sizes**
  - **Callbacks, Promises, and async/await**
- Completely offline, ~5KB, and built for modern browser environments.
- Designed to simplify IndexedDB’s powerful storage model without sacrificing flexibility.

> 🧩 Ideal for apps that outgrow `localStorage` but want simplicity without a full library.

---

## 🧭 My Approach

I aim to build software that’s **easy to use**, even when the logic underneath is complex. I create **outside-the-box solutions** that are practical, minimal, and easy to understand.

> Many problems don’t need complex abstractions — just the **right idea matched with the right structure**.

I value correctness, clarity, and depth over frameworks and trends — and I'm most interested in projects where **technical thinking meets real user benefit**.

---

## 📫 Reach Me

- 💬 **Email**: [Chung_L_Lee@hotmail.com](mailto:Chung_L_Lee@hotmail.com)
- 🌐 **IT Website**: [ChungLimLee.com/computer-services](https://chunglimlee.weeblysite.com/computer-services)
- 🏢 **Project Website**: [SavvyOpen.com](https://savvyopen.com)
- 💼 **LinkedIn**: [Chung-Lim-Lee](https://ca.linkedin.com/in/chung-lim-lee)

Thanks for visiting.
