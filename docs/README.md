### How is the Wiki Updated?
This repository's [Github Wiki](https://github.com/opensearch-project/opensearch-build/wiki) utilizes the [github-wiki-action](https://github.com/Andrew-Chen-Wang/github-wiki-action) workflow. This workflow mirrors the [docs](https://github.com/opensearch-project/opensearch-build/tree/main/docs) folder within OpenSearch-Build onto the Wiki.

With this workflow, OpenSearch-Build documentation can be organized within the Wiki tab, while maintaining the ability for contributors to submit reviewable documentation updates in the form of pull requests.

### Submit a change to the Wiki
To submit a documentation update, update the markdown files within the `docs` folder accordingly, or create new files using the naming convention specified by the [workflow](https://github.com/Andrew-Chen-Wang/github-wiki-action) .

To test your changes, you can create a fork of Opensearch-Build. Commiting and pushing changes to the docs folder of your fork's main branch will run the workflow and update the fork's Wiki page.

Finally, create a pull request containing the changes. Adding a link to your fork's Wiki page within the pull request will help reviewers understand your changes.
