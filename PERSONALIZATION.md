# Personalization notes

This repository is Junteng Liu's academic homepage, based on Academic Pages. Personal content was populated from saved memory, not from a fresh institutional profile or publication search.

## Content locations

- `_config.yml`: site identity, author sidebar, social links, and project-site URL settings.
- `_pages/about.md`: homepage.
- `_pages/research.md`, `_pages/publications.html`, `_pages/cv.md`, `_pages/contact.md`: primary pages.
- `_includes/personal-*.md`: shared education, experience, expertise, and contact content.
- `_data/personal_publications.yml`: six publications; `_includes/personal-publications.html` renders the list.
- `_data/navigation.yml`: primary navigation.

The repository owner is `boobccubski`, while the academic GitHub profile in memory is `Vicent0205`. Both identifiers are intentionally retained in their respective roles.

## Information not available in memory

No specific programming languages, frameworks, proficiency levels, portrait, CV PDF, DOI, arXiv identifier, or exact publication/code URLs were available. These were not fabricated. The skills section lists recorded research areas without claiming specific technical proficiencies. Add confirmed technical skills to `_includes/personal-skills.md`.

Memory listed the PhD as 2024–Present and the MINIMAX internship as February 2025–Present. These dates were carried over without independent verification. The time-sensitive description 'first-year' was omitted. Publication years and venues are the saved versions, not newly checked publication statuses.

Template example collections and demo pages are retained in the repository but excluded from the published site. No sample portrait or placeholder external profiles are used.

## Build and deployment

The configured project URL is `https://boobccubski.github.io/LJT-Homepage/`. This is configuration, not confirmation that GitHub Pages is enabled or deployed.

To test locally with Ruby/Bundler installed:

```sh
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

No local build or live deployment was performed during personalization. The original template license remains in `LICENSE`.
