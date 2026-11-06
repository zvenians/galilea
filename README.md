# Galilea — The First Repository

**An early project marker for the GMAHK Galilea Balikpapan digital ecosystem.**

This repository records the beginning of a church technology initiative in 2023. It is intentionally preserved as a historical reference rather than presented as a deployable application. The maintained software now lives in separate repositories, each with its own documentation, release process, and operational responsibility.

[Congregation website](https://gmahk-galilea.vercel.app/) · [Digital archive](https://drive-galilea.vercel.app/) · [Board administration](https://majelis-galilea.vercel.app/)

---

## Background

The initial goal was straightforward: make congregational information easier to access, reduce manual administrative work, and give ministry teams a more reliable place to maintain records. Over time, those needs developed into different products. Keeping them separate avoids coupling public content delivery, internal administration, and long-term media storage.

| Project | Responsibility | Source |
| --- | --- | --- |
| **GMAHK Galilea** | Public schedules, worship resources, congregation news, and presentation tools | [Website repository](https://github.com/zvenians/gmahk-galilea) |
| **Galilea Digital Archive** | Sabbath-organized documents, media browsing, uploads, and archive management | [Archive repository](https://github.com/zvenians/gmahk-galilea-digital-archive) |
| **Majelis Galilea** | Board meetings, programs, financial records, and official correspondence | [Administration repository](https://github.com/zvenians/majelis-galilea) |

These are distinct applications. Their live behavior and technical requirements should be verified in their own repositories.

## Repository contents

```text
galilea/
├── README.md                  Historical overview and project directory
└── .github/
    └── CONTRIBUTING.md        Guidance for documentation updates
```

There is **no application source, package manifest, test suite, or deployment configuration** in this repository. Cloning it will not produce a runnable church website.

## Where to start

**For members and visitors:** open the [congregation website](https://gmahk-galilea.vercel.app/) for current worship resources and public information.

**For media and ministry teams:** use the [digital archive](https://drive-galilea.vercel.app/) to browse the managed church media collection.

**For authorized board members:** visit the [administrative portal](https://majelis-galilea.vercel.app/) and follow its access procedures.

**For contributors:** choose the relevant maintained repository, read its README, and open changes against that project. Avoid creating parallel application implementations here.

## Maintenance policy

- Retain the original repository identity and historical context.
- Keep links to maintained projects accurate.
- Make documentation changes on a branch and describe them in a pull request.
- Do not report build, performance, uptime, or security results for this repository: there is no executable application to measure.
- Respect the individual projects' data access rules and deployment controls.

## Related work

The three maintained church applications share an institutional context but not a single release lifecycle. A change to one project is not evidence that another project has been updated.

---

**Status:** Historical reference · **Maintainer:** [@zvenians](https://github.com/zvenians) · **Origin:** Balikpapan, Indonesia
