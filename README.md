# Emile Avoscan

**Systems Architect | High-Assurance Software Engineer | RHCSA (RHEL 10)**

I specialize in the development of deterministic, production-hardened middleware and the governance of mission-critical infrastructure. With over half a decade of development experience, my work focuses on the intersection of **Formal Verification**, **Low-Level Systems Programming**, and **Industrial Edge IoT**.

I don't aim to build software that just works; I aim to build software that is mathematically incapable of failing in ways that compromise system integrity—regardless of the operating system.

### Core Engineering Pillars

* **Transactional Systems**: Architecting state-convergence engines (like `lvq`) that treat Linux storage changes as formally verified, mathematically proven transactions.
* **Linux Sovereignty**: Expert in RHEL-based ecosystems and building reproducible, secure OS environments from a minimal base (like `SoulmateOS`). I actively work on a minimal Fedora environment with LUKS2 encryption with TPM + PIN enabled, SELinux enforcing, strict I/O devices control with USBGuard, and snapper for rollback capabilities.
* **OS-Agnostic Kernel Governance**: While my home is Linux, I actively write process governors that interface directly with the Windows API (`ntdll`, `kernel32`) to hijack, suspend, and stabilize proprietary binaries on chaotic factory floors.
* **Industrial Edge IoT**: Reverse-engineering undocumented hardware APIs to build multithreaded, zero-latency telemetry dashboards and ETL pipelines for SMT manufacturing.

### Technical Proficiencies

* **Languages**: Language-agnostic. Currently specializing in Rust (High-Assurance) and Python (ETL/Concurrency), alongside Bash and AHK (Win32 API). Legacy fluency in full-stack JavaScript.   
* **Infrastructure & Orchestration**: Kubernetes, Ansible, Infrastructure as Code (IaC), and Distributed Systems Architecture (focusing on declarative, config-as-code deployments).
* **High-Assurance QA**: Formal verification (`Kani`), property-based testing, and high-velocity fuzzing.

### Operating Systems

* **Linux:** **RHCSA (RHEL 10).** I specialize in architecting highly secure, deterministic environments within the Red Hat ecosystem (RHEL, AlmaLinux, Fedora). Rather than just "administering" servers, I focus on bare-metal engineering: writing custom `systemd` units for daemon orchestration, enforcing Mandatory Access Controls via custom SELinux policies, and building mathematically proven storage engines around LVM2. While I am comfortable navigating Debian, Arch, or OpenSUSE (and wrangling AppArmor when necessary), my architectural methodology relies on the strict, predictable stability of RHEL derivatives.
* **Windows:** My Windows experience goes beyond standard system administration. I interface directly with the OS kernel and Win32 API (`ntdll`, `kernel32`) to hijack process memory handles, suspend race-condition-prone legacy binaries, and programmatically enforce session state persistence across restricted factory-floor terminals.

### Certifications & Trajectories


* [![RHCSA](https://img.shields.io/badge/Red_Hat-Certified_System_Administrator-cc0000?style=flat&logo=redhat&logoColor=white)](https://www.credly.com/badges/0007b5a1-8ed0-4987-848c-aeba50981482/public_url)
* **In-Progress**: **RHCE** (Ansible Automation), **CKA** (Kubernetes Administrator)
* **Programs & Trajectories:** Alumnus of the WithYouWithMe Cyber & Tech Program. Autodidact RHCSA, having independently mastered the Red Hat ecosystem through rigorous self-study, local VM lab environments with the official Red Hat `Virtualization Host` group install, which uses `qemu` and `virsh`, and official documentation.

### Connect

I am driven by the philosophy that high-risk operations should be boringly reliable. If you are solving complex systems problems at the edge, in the kernel, or at the hardware level, let's talk.

**Email**: [avoscanemile@gmail.com](mailto:avoscanemile@gmail.com)
