# Asset and icon register

This static site intentionally avoids third-party runtime requests. The register
records the provenance and treatment of the visual assets used in the page.

| Asset or family | Local path / treatment | Source and usage note |
| --- | --- | --- |
| AA monogram | `assets/aa-mark.svg` | Original site-owner mark created for this publication; reused as the favicon and 404 identity. |
| Portraits and social card | `assets/avatar*`, `assets/headshot*`, `assets/og-card.png` | Site-owner supplied imagery; served locally. |
| AWS and Microsoft certification badges | `assets/badges/` | Existing badge files retained as credential evidence; verify through the linked Credly profile. |
| Service cards | `service-*` symbols in `index.html` | Eight original neutral outline concepts (architecture, foundation, security, migration, platform, AI, FinOps, observability). They are not vendor marks. |
| AWS architecture diagram nodes | `assets/diagram/aws/*.svg` | Exact SVGs from AWS's current Q2 2026 Architecture Icon package, retrieved 2026-08-13 from the official [AWS Architecture Icons page](https://aws.amazon.com/architecture/icons/) and its [Icon-package_04302026.zip](https://d1.awsstatic.com/onedam/marketing-channels/website/aws/en_US/architecture/approved/architecture-icons/Icon-package_04302026.4705b90f5aa45b019271a2699e9ce9b97b941ee1.zip). Files preserve the supplied geometry and colours; used only beside matching service labels across the public and professional case-study diagrams. The retained set includes the Application Load Balancer resource icon; unused CloudTrail and Transit Gateway files remain omitted. |
| Azure VNet diagram node | `assets/diagram/azure-vnet.svg` | Exact SVG from Microsoft's public Azure Architecture icon package V24, retrieved 2026-08-13 from the official [Azure architecture icons guidance](https://learn.microsoft.com/en-us/azure/architecture/icons/) and [Azure_Public_Service_Icons_V24.zip](https://arch-center.azureedge.net/icons/Azure_Public_Service_Icons_V24.zip). |
| Selected organisations | Milestone and LEGO local marks; text fallbacks for the remaining organisations | Milestone Systems and LEGO use the genuine first-party assets listed below. NVIDIA, Agillic, Knowit, SimpleSite, King’s College, and Sana Technology remain polished text fallbacks because a defensible public source or permission record is not stored here. |
| Diagram/tool vendor marks | `assets/toolkit/*.svg` | Exact public first-party or owner-maintained downloads retained and used in diagrams; the Technical Toolkit grid itself retains its original inline visual treatment. Direct sources: [Kubernetes SVG](https://raw.githubusercontent.com/kubernetes/kubernetes/master/logo/logo.svg), [GitHub Primer mark](https://raw.githubusercontent.com/primer/octicons/main/icons/mark-github-24.svg), [GitHub Actions mark](https://github.githubassets.com/images/modules/site/features/actions-icon-actions.svg), [Helm CNCF artwork](https://raw.githubusercontent.com/cncf/artwork/main/projects/helm/icon/color/helm-icon-color.svg), [Argo CNCF artwork](https://raw.githubusercontent.com/cncf/artwork/main/projects/argo/icon/color/argo-icon-color.svg), and HashiCorp's [Terraform marketing logo package](https://registry.npmjs.org/@hashicorp/mktg-logos/-/mktg-logos-0.0.0-canary-20230505183203.tgz). Retrieved 2026-08-13; GitHub's mark is from MIT-licensed Primer Octicons, Helm/Argo are CNCF artwork, and HashiCorp package terms/brand guidance remain applicable. |
| Milestone Systems and LEGO marks | `assets/organisations/milestone.svg`, `assets/organisations/lego.svg` | Exact first-party downloads. Direct sources: [Milestone logo](https://www.milestonesys.com/Static/Img/Global/logo.svg) and [LEGO RGB SVG](https://www.lego.com/cdn/cs/aboutus/assets/blt06799f014ed2650e/LEGO_logo_RGB.svg). Retrieved 2026-08-13; LEGO’s media page says its logo is an editorial/media asset and its usage guidance must be respected. |
| Remaining technical toolkit and diagram-only tools | Text labels with neutral glyphs in `index.html` | Text-first treatment remains for AWS/Azure products not represented by a node asset and tools such as GitLab CI, Sysdig, and PagerDuty where a defensible local source was not established. This avoids inaccurate approximations of third-party trademarks. |
| Fonts | `fonts/` | Self-hosted Lato and DejaVu Sans Mono files already present in the repository. |

## Usage rules

- Do not distort, recolour, redraw, or present a conceptual icon as an official
  vendor or organisation mark.
- Keep any future official logo in a local asset file and add its exact source,
  retrieval date, licence or permission basis, and allowed treatment here.
- Prefer a polished text fallback when a genuine public asset cannot be verified.
- Keep runtime requests dependency-free: all site assets must remain local.
