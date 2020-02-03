<p align="center">
  <img src="https://avatars0.githubusercontent.com/u/44036562?s=100&v=4"/> 
</p>
https://lolo4633.github.io/starter-workflows
## Starter Workflows

<img src="https://d3vv6lp55qjaqc.cloudfront.net/items/353A3p3Y2x3c2t2N0c01/Image%202019-08-27%20at%203.25.07%20PM.png" max-width="75%"/>
https://lolo4633.github.io/starter-workflows
These are the workflow files for helping people get started with GitHub Actions. 
https://lolo4633.github.io/starter-workflows
**Directory structure:**
* [ci](ci): solutions for Continuous Integration
* [automation](automation): solutions for automating workflows.
* [icons](icons): svg icons for the relevant template
https://lolo4633.github.io/starter-workflows
Each workflow must be written in YAML and have a `.yml` extension. They also need a corresponding `.properties.json` file that contains extra metadata about the workflow (this is displayed in the GitHub.com UI).
https://lolo4633.github.io/starter-workflows
For example: `ci/python-django.yml` and `ci/python-django.properties.json`.
https://lolo4633.github.io/starter-workflows
**Valid properties:**
* `name`: the name shown in onboarding
* `description`: the description shown in onboarding
* `iconName`: the icon name in the relevant folder, for example `django` should have an icon `icons/django.svg`. Only SVG is supported at this time
* `categories`: the categories that it will be shown under
https://lolo4633.github.io/starter-workflows
