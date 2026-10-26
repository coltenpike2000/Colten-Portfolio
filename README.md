# Colten-Portfolio

Colten Pike's professional portfolio: defense manufacturing experience, independent software development, robotics simulation, and systems prototypes. The emphasis is on credible evidence for software, cybersecurity, integration/test, and technical mission-support opportunities.

**Reviewed October 26, 2026.** The website is [Index.html](Index.html). It is a static HTML/CSS page with no scripts, build step, analytics, or external asset dependencies.

## View locally

Open `Index.html` directly in a browser, or run `python3 -m http.server 8000` from the repository and visit `http://localhost:8000/Index.html`.

The existing capitalized filename is preserved. A host expecting lowercase `index.html` needs an explicit entry-point setting or a separately reviewed rename. This revision does not enable hosting or certify a live deployment.

## Professional profile

- **Boeing Defense, Space & Security — Munitions Mechanic, St. Charles, Missouri; October 2025–present.** Assembly, production testing, conformance checks using digital instructions and measuring/torque tools, quality issue identification, and safety/ESD practices. Trained 8+ mechanics across 5+ operations and received written recognition for training effectiveness and efficiency.
- **Prior Telamon field installation.** Fiber-optic/low-voltage installation, termination, testing, and troubleshooting on traveling assignments. Employment dates are omitted here because the latest resume and older context conflict; reconcile against employment records before adding them.
- **Completed training:** St. Louis Community College aerospace assembly mechanic training, August 2024, 208 hours in sheet-metal assembly and riveting. This is training, not a degree or external certification.

Professional duties and recognition are based on the owner's account as recorded in the current resume. Internal award and qualification records were not independently reviewed. No cost savings, defect-reduction percentage, supervisory title, or prevention of a field failure is inferred. Employer procedures, configurations, screenshots, internal documents, and detailed manufacturing information are excluded.

## Project status and evidence

No project below is represented as a completed, deployed product. Implemented software components and recorded test baselines do not establish completion of an entire platform.

### Robotics vision and wearable sensing

**Status:** independent shared R&D platform, August 2026–present; simulation and software prototypes, with hardware validation outstanding.

Recorded implementation includes timestamp-aware EKF/PID tracking simulation with Webots integration; a YOLOv8 synthetic-data pipeline; authenticated FastAPI/WSS video and telemetry interfaces; Python/C++17 host/firmware protocols and fault-injection harnesses; Linux/systemd recovery services; viewer software and parametric enclosure fit prototypes.

The current resume records a 1,000-image synthetic dataset audit, 30 GPU training epochs, native C++ execution, ARM compilation/linking, and a shared-platform run with 851 passing tests. These are recorded development results, not independently reproduced results from this audit. The test count belongs to one shared platform, not multiple independently shipped products. Synthetic training does not establish real-world vision accuracy. Compilation does not establish execution on a physical microcontroller. Physical assembly, field performance, and deployment remain unvalidated.

**Evidence available for this review:** October 26, 2026 master resume and its claim-boundary guide. **Public technical evidence in this repository:** none; no source tree, checkpoint, dataset, or raw test report has been published here. This is a status summary, not a reproducible demonstration.

### Oblivion Veil

**Status:** independent C#/Unity software project in development, 2026–present; two-player networking remains a prototype.

Recorded implementation includes NPC perception, persistent memory/state, inventory and progression, local Ollama dialogue integration with structured responses and deterministic permission checks, TCP networking, and versioned JSON persistence. Development used AI assistance; no sole unaided authorship is implied.

The recorded October 14, 2026 baseline contains 498 unique passing NUnit cases. It is a dated result, not a current rerun or test-coverage percentage. Two-computer LAN acceptance remains pending. No shipping, commercial sales, or completed multiplayer acceptance is claimed.

**Evidence available for this review:** current resume and claim-boundary guide. **Public technical evidence in this repository:** none. A private source repository is not linked as publicly accessible evidence.

### Fielddeck

**Status:** independent offline mapping/messaging software prototype, October 2026–present; Raspberry Pi/radio integration planned.

Recorded implementation includes Python/JavaScript, SQLite persistence, waypoints, Meshtastic messaging interfaces, GPX export, duplicate filtering, and track segmentation. A hardware integration plan and parametric OpenSCAD mounting components are recorded.

The current resume records 25 automated tests. This is a recorded baseline, not a fresh test run of the latest build kit. No physical radio deployment, communication range, battery endurance, or seven-day operational capability is established.

**Evidence available for this review:** current resume and claim-boundary guide; a newer build kit exists but was not source-audited in this portfolio review. **Public technical evidence in this repository:** none. No private artifact is presented as a public demonstration.

### Legacy project claims

The original page is preserved in Git history. Its five unsubstantiated project entries are retained on the website as historical concepts with implementation unverified, rather than silently promoted to completed work.

| Earlier entry | Audit finding | Public treatment |
| --- | --- | --- |
| ISR Drone (sub-250g), autonomous telemetry and inference | No supporting build, flight, mass, or inference evidence in this repository | Historical concept; completion unverified |
| Pi SDR Recon Kit, long-duration logger | No supporting source, run log, hardware demonstration, or endurance result | Historical concept; completion unverified |
| RF Sweep Node, multi-antenna monitor | No implementation or measurement evidence linked | Historical concept; completion unverified |
| Zeek/Suricata Lab, PCAP replay and detection | No configurations, PCAP fixtures, commands, or alert results linked | Historical concept; completion unverified |
| Python SDR Logger Tools | No source, tests, or sample outputs linked | Historical concept; completion unverified |

Absence of evidence does not prove these were never built. It means their implementation and completion cannot be established for public claims. The newer R&D platform is not assumed to be the same project as any legacy entry.

## Education and credentials

| Item | Supported status | Treatment |
| --- | --- | --- |
| WGU accelerated BS-to-MS Computer Science | Admitted; target completion 2027, AI/ML master's specialization planned, per current resume | Neither degree is claimed as earned; no active-enrollment date invented |
| CompTIA Security+ | Active preparation; not yet earned | Professional development, separate from earned credentials |
| CompTIA Network+ (previously 2025) | Older profiles repeat the claim; no issuer verification or current credential record reviewed | Removed from earned certifications and skill tags pending verification |
| CompTIA Linux+ | Older in-progress statement; current pursuit not substantiated | Removed rather than re-dated |
| FAA Part 107 | Old Q4 2025 target; no completion evidence reviewed | Removed pending verification |
| Amateur radio Technician | Old summer 2025 target; no current license evidence reviewed | Removed pending verification |
| WGU-associated certifications | Planned through coursework; not earned | Not presented as current certifications |
| Security clearance | Current resume says processing in progress; no grant verified | Public site omits processing details and makes no active-clearance or eligibility claim |

No conclusion about a person's legal clearance eligibility can be established by a portfolio. Employer association, clearance processing, citizenship assumptions, or career goals are not evidence of a granted clearance. No clearance level is inferred.

## Audit and evidence policy

This review compared the original `main` website and title-only README with the owner's current master resume and `Resume_Use_Guide.txt`, both revised October 26, 2026. The guide explicitly states that project counts and training results derive from supplied handoffs/recorded results and were not independently source-audited or re-tested. This revision preserves that limitation. It is an evidence and presentation audit, not a credential verification service or an audit of the separate project source repositories.

The original repository at commit `50fe1536252b5aeba94d34e77ff353f5a3e861f3` contains only `Index.html` and `README.md`. It has no technical project source, test reports, certification records, or resume attachments. This update does not publish the private resume, contact details, project sources, or employer records.

### Publication standard

1. **Completed:** identify the specific finished scope and link reproducible evidence. Do not describe an entire ongoing platform as complete because some components pass tests.
2. **Prototype or simulation:** identify what runs, which environment was used, and what physical or deployment acceptance remains outstanding.
3. **Planned:** describe intent only. When actual intent or progress is unknown, use “implementation unverified” rather than asserting a plan or completion.
4. **Earned credentials:** verify issuer, credential name, award date, and current validity before listing. Publish a verification link only if appropriate; keep private identifiers private.
5. **Professional accomplishments:** preserve accurate titles, dates, and defensible counts. Distinguish the owner's account from independent documentary verification.
6. **Public evidence:** link only accessible, sanitized artifacts. Review project data for secrets, personal information, employer material, and third-party restrictions before publishing. Do not invent public links or upload private source to make a claim appear supported.

### Highest-value next evidence

Publish one sanitized, reproducible project case study before expanding the project list. Include the problem, individual contribution and AI assistance, architecture, implementation status, setup/run commands, a dated source commit, representative output, test command and raw result, limitations, and the next acceptance test. Link it from the relevant website card. This is a recommendation, not a claim that publication is already authorized or completed.

## Maintenance

The original `Index.html` filename and section anchors (`about`, `projects`, `certs`, `skills`) are retained. The visual treatment remains teal-based, with readable cards, mobile layout, keyboard focus states, a skip link, reduced-motion support, and print styles. All project “evidence boundaries” links lead to actual sections in this README; they are documentation links, not source-code demonstrations.

Keep website and README claims aligned. Recheck dated results after substantive implementation changes. Original wording remains recoverable in Git history; no separate project repository or employer material is modified by this revision.
