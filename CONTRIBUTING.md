# Contribution Guidelines

Thanks for helping. This list only includes real, public skills, and every image must be honest.

## Adding a skill

1. Add an entry to `skills.json` (`name`, `repo`, `path` if the skill lives in a subfolder, `category`, `desc`).
2. The repo must be public and the skill must have a `SKILL.md`, or be clearly an agent skill or skill collection.
3. Run `node scripts/build.mjs --refresh`. It checks the repo and the `SKILL.md` path and regenerates `README.md` and `docs/index.html`. Do not edit those two files by hand.
4. Run `npx awesome-lint` and open a pull request.

## Adding a screenshot

- Best: run the skill yourself and screenshot the real output. Put it in `docs/assets/gallery/` and say how it was made in `imageCredit`.
- Or: hotlink an image from the skill's own repo, and credit it with its license in `imageCredit`. Do not copy files from repos whose license does not allow it.
- No mockups, AI-imagined outputs or images of a different tool.
- Keep files under 500 KB.

## Descriptions

Start with a capital letter, end with a period, and say what the skill produces. No marketing language.

## License

By contributing you agree your contribution is released under [CC0](LICENSE).
