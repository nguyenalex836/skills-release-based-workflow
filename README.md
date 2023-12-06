<header>

<!--
  <<< Author notes: Course header >>>
  Read <https://skills.github.com/quickstart> for more information about how to build courses using this template.
  Include a 1280×640 image, course name in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Next to "About", add description & tags; disable releases, packages, & environments.
  Add your open source license, GitHub uses the MIT license.
-->

# Create a release based workflow

_Create a release based workflow that is built on the foundations of the GitHub flow._

</header>

<!--
  <<< Author notes: Step 3 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
-->

## Step 3: Open a release pull request

_Nice work adding a new feature :smile:_

### Release branches and `main`

You should open a pull request between your release branch and main as early as possible. It might be open for a long time, and that's okay.

In general, the pull request description can include:

- A [reference to an issue](https://docs.github.com/en/articles/basic-writing-and-formatting-syntax/#mentioning-people-and-teams) that the pull request addresses.
- A description of the changes proposed in the pull request.
- [@mentions](https://docs.github.com/en/articles/basic-writing-and-formatting-syntax/#mentioning-people-and-teams) of the person or team responsible for reviewing proposed changes.

To expedite the creation of this pull request, I've added a pull request template to the repository. When you create a pull request, default text will automatically be displayed. This should help you identify and fill out all the necessary information. If you don't want to use the template content, just remove the text from the pull request and replace it with your pull request message.

### :keyboard: Activity: Open a release pull request

Let's make a new pull request comparing the `release-v1.0` branch to the `main` branch.

1. Open a **new pull request** with `base: main` and `compare: release-v1.0`.
1. Ensure the title of your pull request is "Release v1.0".
1. Include a detailed pull request body, an example is below:
   ```
   ## Description:
   - Changed page background color to black.
   - Changed game text color to green.
   ```
1. Click **Create pull request**.
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/release-based-workflow) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
