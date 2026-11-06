# Ziad Khedr - Portfolio

Personal portfolio: [ziadwael.vercel.app](https://ziadwael.vercel.app).

A buildless HTML/CSS/JavaScript site with English and Egyptian Arabic, right-to-left layout, saved language/theme preferences, project case studies, and a downloadable PDF CV.

## Content

- Featured: SheetPilot AI, a solo Meta AI Hackathon MVP.
- Personal demonstrations: computer-store RAG, lead qualification, restaurant ordering, and marketing campaign planning.
- Additional projects: the collaborative AI Research Assistant and an Arabic lead-intake workflow.
- Four services linked to relevant projects, skills demonstrated by those projects, and education/training.

All project status labels describe personal work, prototypes, or a team collaboration. No project is presented as a paid client deployment. English proficiency and GPA are intentionally preserved from the prior portfolio.

## Project evidence

The SheetPilot screenshots were captured from the actual application using sample electronics data. The agent-workspace screenshot shows a guided business review; no AI was used for that pictured run. The application separately supports the official Meta Model API, as described in its source repository. Screenshots are not a live embedded app.

- [SheetPilot source and demo guide](https://github.com/ZiadKhedr/SheetPilot-AI)
- [Research Assistant source and contribution breakdown](https://github.com/ZiadKhedr/Ai-Research-Bot)

The research project credits Ziad for search, scraping, tool routing, orchestration, and the Gradio UI. Question generation, summarization, comparison, and report generation belong to the collaborator, as recorded in that project's README.

Other project walkthrough links open an email request; they do not pretend that a hosted demo or public repository exists.

## Editing

Serve this directory with any static host; there is no build step. `index.html` holds the markup, CSS, and behavior. Visible translated strings use stable `data-i18n` keys and an embedded translations dictionary, so project ordering does not determine translations. Keep English markup and the corresponding dictionary entries consistent when editing.

Assets are stored under `assets/`, including the portrait, two genuine app screenshots, and `Ziad_Khedr_CV.pdf`. No API key or backend service is required for this portfolio.

## Validation - November 6, 2026

Validated section/project order, seven project cards, four services, unchanged English/GPA, unique IDs, all local assets and internal anchors, external-link protections, all 159 translation keys, language switching after card reordering, saved preferences, clipboard success/failure feedback, and inline JavaScript syntax with jsdom. No runtime errors were reported by that check.

The CV is one page, contains searchable text and clickable links, and was rendered to an image for visual inspection. The page includes responsive CSS, but real-browser desktop/mobile visual verification and a new demo recording were blocked by the current environment's browser/network restrictions. No successful browser layout check is claimed.
