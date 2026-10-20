# Emile Avoscan

### **Infrastructure & Systems Engineer | RHCE (RHEL 10) | Linux, Ansible, Rust & Python | Industrial Edge Systems**

I design, automate, and troubleshoot systems where **correctness, predictability, and observability matter**.

My background spans Linux infrastructure, systems programming, industrial IoT, and automation. With over five years of development experience, I focus on building reliable software that interacts with operating systems, hardware, and potentially destructive system operations.

My engineering philosophy is straightforward:

**Fail loudly. Verify the resulting state. Never report success without evidence.**

I favor explicit invariants, deterministic behavior, minimal dependencies, and systems that remain understandable when something goes wrong.

## Featured Projects

### [lvquick (lvq)](https://github.com/AvoscanEmile/lvq)
**Rust | Linux LVM2 | State Convergence | Safety Verification**

A declarative state-convergence engine for Linux Logical Volume Manager (LVM2), designed to replace fragile sequences of storage commands with explicit, inspectable execution plans.

Key design principles:

- **State-aware planning:** inspect existing storage configuration and determine the operations required to reach a desired state.
- **Conservative execution:** detect unexpected or partially configured states and refuse potentially unsafe transitions.
- **Explicit authorization:** separate planning and verification from privileged execution.
- **Post-execution validation:** examine the resulting system state rather than relying exclusively on command exit codes.
- **Failure transparency:** preserve execution information and make partial transitions visible to the operator.
- **High-assurance testing:** use Kani for targeted arithmetic-safety verification, Proptest for property-based testing, and fuzzing to exercise edge cases.

The project is under active long-term development. Planned work includes operator-directed recovery of interrupted execution plans.

### [Sentinel](https://github.com/AvoscanEmile/sentinel)
**Windows APIs | C | Python | Industrial Automation**

Systems-level tooling developed around industrial software and hardware integration.

My work in industrial environments has included reverse-engineering undocumented hardware interfaces, managing legacy process behavior through Windows APIs, and building concurrent telemetry pipelines for manufacturing equipment.

One independently developed integration recovered approximately **360 hours of annual production capacity** by addressing operational inefficiencies in a manufacturing environment.

### [SoulmateOS](https://github.com/AvoscanEmile/SoulmateOS)
**Linux Hardening | SELinux | Minimal Operating Systems**

A Linux hardening and minimal-system project focused on reproducibility, controlled system behavior, and reducing unnecessary attack surface.

My related Linux security work includes exploring and configuring:

- SELinux mandatory access controls.
- Minimal RHEL-family and Fedora installations.
- LUKS2 disk encryption and TPM-backed authentication.
- USBGuard device authorization policies.
- System snapshots and rollback mechanisms.
- Custom `systemd` services and restrictive service configurations.

## Technical Expertise

| Domain | Technologies and Practices |
|---|---|
| **Linux Infrastructure** | RHEL 10, AlmaLinux, Fedora, systemd, SELinux, LVM2, virtualization |
| **Automation & IaC** | Ansible, YAML, declarative configuration, infrastructure automation |
| **Systems Programming** | Rust, C, Python, Bash, Windows native APIs |
| **Software Assurance** | Kani, Proptest, kani-fuzz, invariant testing, defensive programming |
| **Industrial Systems** | Industrial IoT, hardware API integration, concurrent telemetry, ETL |
| **Networking & Operations** | Linux networking, troubleshooting, monitoring, service management |
| **Additional Experience** | JavaScript development, Kubernetes fundamentals, cloud architecture studies |

## Engineering Principles

**Correctness over apparent success.** An operation is not successful simply because a command exited with code zero. Where possible, the resulting state should be independently verified.

**Explicit failure boundaries.** Unexpected state is a reason to stop and investigate, not permission to improvise destructive recovery actions.

**Automation without unnecessary opacity.** Good automation reduces operational effort while preserving the information necessary to diagnose failures.

**Minimal complexity.** I prefer well-understood primitives, clear interfaces, and maintainable systems over unnecessary abstraction.

**Verification within defined limits.** Formal methods, property-based testing, and fuzzing are valuable tools for establishing specific guarantees. Their scope and assumptions should remain explicit.

## Certifications

- **Red Hat Certified Engineer (RHCE), RHEL 10** — [Verify credential](https://www.credly.com/badges/e9197ef6-f254-4de0-b3d6-54a3b3c5345f/public_url)
- **Red Hat Certified System Administrator (RHCSA), RHEL 10** — [Verify credential](https://www.credly.com/badges/0007b5a1-8ed0-4987-848c-aeba50981482/public_url)

**Currently studying:** AWS Certified Solutions Architect – Associate and HashiCorp Terraform Associate.

**Additional training:** WithYouWithMe Cyber & Tech Program alumnus.

My Linux expertise has been developed through independent study, extensive hands-on lab work, virtualization environments, automation projects, and real-world engineering problems.

## Interests

I'm particularly interested in:

- Linux systems and operating-system security.
- Rust systems programming and software verification.
- Declarative infrastructure and reliable state reconciliation.
- Industrial automation and hardware/software integration.
- Reproducible, locally controlled, and resilient infrastructure.

## Connect

I'm interested in technically demanding engineering work where reliability, transparency, and a deep understanding of system behavior are essential.

If you're working on Linux infrastructure, systems software, security-sensitive tooling, or industrial automation, feel free to reach out.

**[Email](mailto:avoscanemile@gmail.com) · [LinkedIn](https://www.linkedin.com/in/emile-avoscan-510091211)**
