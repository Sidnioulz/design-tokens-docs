# design-tokens-docs
A DTCG design tokens to HTML documentation transformer

## What's going on here!?

This project is in its infancy. It aims to be a collaborative FOSS tool to convert design token JSON files to HTML documentation. The idea is to then use this tool to produce token doc for Storybook users, but also to harness collaboration from other tool makers (like Handoff or Backlight) and design system engineers who have built such documentation for their orgs.

Folks who are interested in participating and with a track record of FOSS contribution and relevant experience (Storybook, documentation projects like Vitepress, 11ty, Starlight, Design Systems engineers, DTCG contributors, etc.) are all welcome to join and define with us what such documentation should look like, and what options the tool should have. The idea is to run async discussions on features, architecture and input/output formats, and then to get to work.

https://github.com/sidnioulz expects to do most of the dev work themselves but want to give folks who care about this topic a chance to have their needs heard and addressed. This project is invite-only. Folks who were invited are welcome and encouraged to invite others too. Folks who work on closed-source commercial token documentation tools are not welcome on this project.

## Overall architecture (imagined, subject to change)

![Diagram of the imagined data pipeline for this project; Starting from design tools and common token management tools; which all lead to JSON token files being produced; optionally, Style Dictionary and Terrazzo can augment these files with platform-specific knowledge, and custom metadata can be provided; the doc tool parses this input, maps it to documentation pages, and then generates those pages with a templating tool into MDX, HTML, MD, Astro; doc tools then consume the most relevant page format.](https://github.com/user-attachments/assets/087a8a08-267e-4f1f-aef4-c93bb18ab392)

## Where to start?

* Look up [open issues](https://github.com/Sidnioulz/design-tokens-docs/issues) and/or the associated [GitHub project](https://github.com/users/Sidnioulz/projects/4) (with extra drafts, needs an invite)
* Discuss, debate, contradict, propose, showcase: share your expertise
* Propose your own topics in issues, discussions, etc.
* Once consensus is reached on an issue, help prioritise it using the RICE framework
* If you have time to contribute, and once this project is sufficiently well scaffolded, pick up an issue that's ready to dev and get going

## Code of Conduct

https://www.contributor-covenant.org/version/2/1/code_of_conduct/

## License

GNU Affero GPL v3 until decided otherwise by contributors.
