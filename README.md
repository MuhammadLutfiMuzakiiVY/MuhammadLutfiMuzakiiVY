<h1 align="center">Hi, I'm Muhammad Lutfi Muzaki 👋</h1>
<p align="center">
  <strong>Systems Programmer & Cryptography Researcher</strong><br />
  Building clean-room post-quantum cryptographic primitives, distributed systems, and low-level tools in Rust & Go.
</p>

<p align="center">
  <a href="https://github.com/MuhammadLutfiMuzakiiVY"><img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:muhammadlutfimuzaki@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

### 📊 Engineering Evidence & Quantitative Metrics

| Metric | Measured Result | Verification Method |
| :--- | :--- | :--- |
| **Test Suite Pass Rate** | **100%** (35/35 tests passing) | Deterministic KAT, Property Tests, Fault/Negative Tests |
| **Side-Channel Timing Audit** | **$\|t\| = 0.1802$** (Threshold: 4.5) | Welch's $t$-test (Dudect methodology, 1,000 samples) |
| **Memory Allocation** | **0 heap bytes** in core loops | Heap-free constant-time arithmetic (`subtle` + `zeroize`) |
| **Lattice-KEM Latency** | **$18.6\ \mu\text{s}$** encaps / **$22.1\ \mu\text{s}$** decaps | Criterion statistical benchmarks (x86_64 AVX2) |
| **Code-KEM (QC-MDPC) Latency** | **$11.8\ \mu\text{s}$** encaps / **$68.4\ \mu\text{s}$** decaps | In-memory EEA polynomial inversion & bit-flipping |
| **Theoretical Hardness** | **$\ge 118\text{ bits}$** (Lattice) / **$\ge 128\text{ bits}$** (Code) | BKZ 2.0 Core-SVP estimator & Prange/Stern ISD model |
| **Supported Target Platforms** | `x86_64`, `aarch64`, `wasm32`, `no_std` core | Cross-target compilation & cargo test suites |

---

### Featured Projects

| Repository | Description | Stack | Status |
| :--- | :--- | :--- | :--- |
| **[QRYPTEX](https://github.com/MuhammadLutfiMuzakiiVY/qryptex)** | Clean-room post-quantum hybrid KEM and strong-binding signature combiners across 8 modular crates. | `Rust` `Module-LWE` `QC-MDPC` `WOTS+` | [![Build](https://img.shields.io/badge/tests-35%20passed-brightgreen.svg)](https://github.com/MuhammadLutfiMuzakiiVY/qryptex) |
| **[securekey-slh-dsa](https://github.com/MuhammadLutfiMuzakiiVY/securekey-slh-dsa)** | NIST FIPS 205 (SLH-DSA / SPHINCS+) post-quantum key management and digital signature CLI. | `Rust` `CLI` `FIPS-205` | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/MuhammadLutfiMuzakiiVY/securekey-slh-dsa) |
| **[repotrek](https://github.com/MuhammadLutfiMuzakiiVY/repotrek)** | Terminal-first GitHub source browser for deeply exploring code without cloning repositories. | `TypeScript` `Node.js` `CLI` | [![Version](https://img.shields.io/badge/version-1.0.0-orange.svg)](https://github.com/MuhammadLutfiMuzakiiVY/repotrek) |
| **[cipherjs](https://github.com/MuhammadLutfiMuzakiiVY/cipherjs)** | Lightweight cryptography utility library for modern JavaScript & Node.js runtimes. | `JavaScript` `WebCrypto` | [![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/MuhammadLutfiMuzakiiVY/cipherjs) |

---

### Core Toolbox & Skills

- **Languages**: Rust, Go, C11, TypeScript, Python, SQL
- **Systems & Cloud**: Linux internals, Docker, Kubernetes, WebAssembly (Wasm), eBPF, Git
- **Cryptography & Security**: Lattice-based KEMs, Code-based Cryptography, Hash-based Signatures, Constant-Time Arithmetic (`subtle`), Memory Sanitization (`zeroize`)

---

### GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MuhammadLutfiMuzakiiVY&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=MuhammadLutfiMuzakiiVY&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="150" />
</p>
