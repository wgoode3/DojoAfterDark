# Dojo After Dark

## Who are we?

- Community of craftsmen and craftswomen

## What do we do?

- Collaborate on projects
- Gain experience in the day to day life as a programmer
- [Autodidacticism](https://en.wikipedia.org/wiki/Autodidacticism)

## Projects

- dojoafterdark.com (`this` community site)
- lost.dojoafterdark.com (lost and found app)
- kitchen.dojoafterdark.com (kitchen inventory app)

## Slack Channel

- #dojo_after_dark

## Links

- [Live Site](https://dojoafterdark.com/)
- [Repo](https://github.com/CBaut/DojoAfterDark)
- [Project Board](https://github.com/CBaut/DojoAfterDark/projects/1)
- Deployed automatically using GitHub and [Zeit](zeit.co).
- [More git](https://github.com/TheCodingDojo/student_md_docs/blob/master/CA-OC/github/cheat_sheet.md)

---

## First timers

- [ ] maintain a page on the community site

## Returning

- [ ] contribute to one of the projects

## How to run the project locally

- open `index.html` using live server

## How to create your own page

- From the terminal `cd` into the folder you want to save the project
- Clone the project `git clone https://github.com/CBaut/DojoAfterDark.git`
- `cd` into the newly created project folder (`ls` or `dir` to view the contents of the current directory)
- Create a new local branch with the following convention `git checkout -b {{first_name}}-{{last_name}}` (replace the contents of `{{}}` including the brackets)
- Create your folder in the project folder using the same convention `{{first_name}}-{{last_name}}`
- Create an `index.html` and a `styles.css` in your folder (optionaly a js file)
- In the top-level index.html, add a link `<a>` to your folder path in the footer section
- In the same file, in head/script, add a new object to 'sites' with your folder path, name, and description (Note: this step may change if JavaScript is refactored out of index.html)
- Stage your changes `git add .`
- Commit your changes `git commit -m "{{commit message}}"`
- Request to be a contributor (ask CBaut to add you to the project by sending your github username)
- Push your local changes to the github repository `git push`
- Create a pull request from your branch to master branch
- Get your code reviewed
- Merge branch into master
- If automated deployment is successful check the [website](https://dojoafterdark.com/)
