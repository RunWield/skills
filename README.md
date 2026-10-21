# RunWield Skills

Portable planning, guidance, and code review skills for coding agents. Install them in any project without installing
RunWield or cloning its application repository.

```sh
npx skills@latest add RunWield/skills
```

| Skill                       | Purpose                                                                        |
| --------------------------- | ------------------------------------------------------------------------------ |
| [ideator](ideator/SKILL.md) | Explore an idea and shape product requirements.                                |
| [guide](guide/SKILL.md)     | Discuss a project and develop a direction before implementation.               |
| [review](review/SKILL.md)   | Review changes against project standards, intended behavior, and test quality. |

## Maintenance

This repository is checked out at `skills/` inside [RunWield Core](https://github.com/RunWield/runwield).
Edit the portable skills here. Core maintains the source-to-skill review baseline and validation script.
See [Core's maintenance guide](https://github.com/RunWield/runwield/blob/main/docs/skills-maintenance.md).

Guide and Ideator adapt Core Agent definitions for arbitrary projects. Review is maintained independently. Changes to
an Agent definition need deliberate adaptation: portable skills describe capabilities without requiring RunWield's
product names, tools, or workflow machinery.

## License

[MIT](LICENSE). Copyright (c) 2026 Carlos Ravelo.
