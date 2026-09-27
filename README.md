# IT Study Materials

A shared collection of browser-based study guides, flashcards, quizzes, command references, and guided labs for Brandon Stevenson and colleagues.

## Start here

1. Download and extract this folder, or clone the repository containing it.
2. Open **`index.html`** in your web browser to browse the collection.
3. Choose a topic and open a study tool. You can also open any individual `.html` file directly.

The included HTML files contain their own study content and application scripts. No package installation, build step, account, or backend is required to open them. Several tools request Google Fonts; without internet access, the browser uses fallback fonts. External reference links and actual vendor lab environments require connectivity.

GitHub file links let you locate and download the source files. To use the interactive quizzes and flashcards, open the downloaded HTML in your browser.

## Study catalog

| Topic | Study material | Contents |
| --- | --- | --- |
| Azure | [Azure Fundamentals Flashcards](./azure/az-900-azure-fundamentals-flashcards.html) | Standalone flip-card deck covering cloud concepts, Azure services, identity, costs, and governance. |
| Azure | [Azure Fundamentals Study Guide](./azure/az-900-azure-fundamentals-study-guide.html) | Three-domain guide with service comparisons, exam tips, and a separate question-and-answer flashcard deck. |
| Networking | [CCNA Fundamentals Quiz 1](./networking/ccna-network-fundamentals-quiz-01.html) | 30 questions on networking models, addressing, switching, and core protocols, with answer explanations. |
| Networking | [CCNA Fundamentals Quiz 2: Scenarios](./networking/ccna-network-fundamentals-quiz-02-scenarios.html) | 30 questions emphasizing troubleshooting tickets, subnetting, connectivity, and protocol selection. |
| Networking | [CCNA Guided Troubleshooting: 4 Scenarios](./networking/ccna-guided-troubleshooting-lab-04-scenarios.html) | Introductory decision-based cases: single-user connectivity, branch outage, DNS failure, and duplex mismatch. |
| Networking | [CCNA Guided Troubleshooting: 20 Scenarios](./networking/ccna-guided-troubleshooting-lab-20-scenarios.html) | Expanded decision-based cases covering DHCP, VLANs, Wi-Fi, port security, loops, ACLs, time synchronization, and more. |
| Networking | [Cisco IOS Commands & Theory Reference](./networking/ccna-cisco-ios-commands-and-theory-reference.html) | 20 sections of configuration examples, protocol explanations, verification commands, hardening, and operations practices. |
| Networking | [CCNA Complete Study Guide, Labs & Practice Exams](./networking/ccna-complete-study-guide-labs-and-practice-exams.html) | Six-domain study tool with an eight-week plan, lab walkthroughs, subnet trainer, quizzes, mock exams, flashcards, and glossary. |
| Cloud Architecture | [Azure Cloud Systems Design](./cloud-architecture/azure-cloud-systems-design-study-guide.html) | Azure-focused beginner-to-intermediate architecture guide with AWS comparisons, design patterns, reliability, security, cost, and three design exercises. |
| It Administration | [IT Administration Glossary & Flashcards](./it-administration/it-administration-glossary-and-flashcards.html) | Searchable terms across networking, identity, servers, storage, security, cloud, endpoints, email, and operations, plus a responsibilities checklist. |
| Endpoint Management | [MD-102 Endpoint Administrator Field Guide](./endpoint-management/md-102-endpoint-administrator-field-guide.html) | Windows deployment, Autopilot, Intune, Entra identity, compliance, updates, endpoint protection, and application management. |
| Network Security | [Palo Alto NGFW / PAN-OS Study Guide & Labs](./network-security/palo-alto-ngfw-pan-os-study-guide-and-labs.html) | 24-section reference covering firewall fundamentals, policy and NAT, App-ID, User-ID, VPNs, HA, Panorama, automation, practice questions, and lab exercises. |

## Suggested starting points

- **General IT refresher:** Start with the IT Administration Glossary & Flashcards.
- **Azure fundamentals:** Read the AZ-900 guide, then use the standalone flashcard deck.
- **Networking:** Use the complete CCNA guide for structured study and the IOS reference for command lookup. Follow with Quiz 1, Quiz 2, and the guided troubleshooting scenarios.
- **Endpoint administration:** Use the MD-102 field guide for Windows deployment, Intune, identity, and device management.
- **Cloud architecture:** Work through the cloud systems design guide and its design exercises.
- **Firewall administration:** Use the Palo Alto NGFW / PAN-OS guide for firewall concepts, configuration examples, and lab preparation.

## Using the tools together

The four-scenario troubleshooting lab is a shorter starting point. The 20-scenario edition revisits those core cases and adds more situations. Both are included intentionally. The two CCNA quizzes are separate practice sets, and the AZ-900 study guide and standalone flashcards are separate review resources.

Guided troubleshooting pages are interactive decision exercises, not live network emulators. Configuration lab instructions may require separate equipment, software, or vendor access.

## Progress and sharing

Some tools save topic completion or theme preferences in your browser. Others keep quiz state only for the current page session. There is no shared login, central score database, or synchronization between colleagues. Clearing browser data or changing browsers can reset locally stored progress.

## Content maintenance

This packaging update organizes and renames the original 12 HTML files; their page content and scripts are unchanged. It is not a technical accuracy audit or a verification against current exam objectives. Exam names, weights, prices, product features, and portal paths in the guides should be checked against current vendor documentation before relying on them.

When suggesting a correction, include the filename, section or question, proposed change, and supporting vendor reference. Use configuration examples in an appropriate lab and adapt them to the exact device and release.

## Filename conventions

Filenames use lowercase words separated by hyphens, with a topic or certification prefix and a description of the material. Quiz numbers and scenario counts distinguish similar tools. See [RENAMED-FILES.md](./RENAMED-FILES.md) for the original-to-new mapping.
