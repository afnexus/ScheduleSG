# Welcome! #

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

If you're unsure about anything, just ask -- or submit the issue or pull request anyway. The worst that can happen is you'll be politely asked to change something. We love all friendly contributions.

If you have any questions, feel free to contact [Jonathan](https://github.com/voyager163).

## How to contribute

When you have an idea for contribution open an *issue*!

## Git guidance

Consistent with the practices suggested in this playbook, please follow the
specifics regarding git as described in this section.

### Branch naming convention

In this repo, we use the following branch naming conventions:

| Branch Type | Pattern | Example |
| - | - | - |
| Feature | feat/\<short description> | feat/reorganize-scm-section |
| Bug Fix | fix/\<short description> | bug/correct-grammar-myfile.md |
| Documentation| docs/\<short description> | docs/update-new-readme.md |
| Style | style/\<short description> | style/correct-style-myfile.md |
| Refactor | refactor/\<short description> | refactor/change-myfile.md |
| Perf | perf/\<short description> | perf/brand-new-myfile.md |
| Test | test/\<short description> | test/new-myfile.md |
| Chore | chore/\<short description> | chore/correct-myfile.md |

> **Note:**
>
> * Please, do not use personal branches. Work should refer back to a
feature/bug fix in the backlog.
> * Mind the capitalization of the branch prefix (feature, fix). Tools that
display branches as a hierarchy are typically case sensitive, and will display
different hierarchies for the same words with different capitalization.

### Linting

If you use VSCode as your preferred editor, please install the [markdownlint
extension](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
and ensure that all rules are followed. This will help ensure consistency in the
look and feel of the documentation in this repo.

You can find information about other linters, general writing guidelines and code review check lists for Markdown in the [Markdown code review recipe](code-reviews/recipes/Markdown.md).

### Example Directory Hierarchy

The following illustrates how the directory structure could be organized.

```plaintext
- /continuous-integration
    - README.md (Conceptual)
    - /e2e-testing-in-ci
        - README.md
    - /static-code-analysis
        - README.md
    - /recipes
        - /azure-devops
            - versioning-ci-builds-in-azure-devops.md
            - sonar-qube-integration.md
            - ci-pipeline-for-dotnet-core.md
            - ci-pipeline-for-python.md
        - /jenkins
```

## Legal Notices

Privacy information can be found at <https://privacy.swiftoffice.org/>

Republic of Singapore Air Force and any contributors reserve all others rights, whether under their
respective copyrights, patents, or trademarks, whether by implication, estoppel or otherwise.
