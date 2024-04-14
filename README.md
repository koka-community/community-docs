# Community Documentation
Documentation for the Community (Guidelines, Rules, Organization, Licensing)

## Guidelines

### Creating a new package
- Use the Template repository to create new packages.
- Add a subdirectory with the same name as the package name, and put your code in that subdirectory
(e.g. if the package is called `std` inside your repository there should be a folder called `std` with all your code for the package).
  - Rationale for this is so that you can have test scripts, documentation, and other files in the root of the repository and that the package include path includes the package name.
- Replace the template code with your content.
- Add your name to the authors file when contributing.
- Add the repository to the `koka-community` repository as a submodule, and the corresponding include path to the compiler flags in the `.vscode/settings.json` in that repository.
- Select 2 people to be reviewers / owners of the repository, so that they can share the responsibility to help merge PRs and review code. This way hopefully no one is waiting forever for a single person to be available.

### Pull Requests and Merging
- Get a review from at least one other person before merging. Owners can get an exception to this rule, so they can publish fixes, without being hassled by procedure. If no one reviews your PR within a few days, contact @TimWhiting.

- Be responsive to requests for review if you are an owner of a repository. Within a week ideally.

- Use squash and merge. This keeps the history clean and makes it easier to revert changes if needed.

### Issues
- Use issues to track not only bugs, but also feature requests, and other maintainance tasks.
- Try to assign the issue to someone, so that it is clear who to follow up with.
- Be respectful and constructive in your comments.
- Don't pester someone to fix an issue, contribute a fix instead!
- Assign issues to some sort of deadline, `needs-more-discussion`, or `you-want-you-fix` milestone, so that it is clear to users and maintainers what the priority of the issue is.
- If there are more issues than you can handle, consider marking more issues as `help-wanted` or `good-first-issue` to attract more contributors. Or request that the community assign an additional maintainer to help.

## Rules 
- Be nice, kind, and respectful to each other
- Help each other out
- Ask questions
- Contribute
- Don't be afraid of making mistakes, correct them as quick as possible.
- Scripts should be written in Koka not any other scripting language
- Other languages should be kept to a minimum (other than interfacing with C, JS, WASM), but those should be kept to a minimum as well. Exceptions are made on a repository by repository basis.
- Static websites should first consider using madoko - an extended Markdown format with lots of extra features. (see https://github.com/koka-community/koka-docs for an example, and http://madoko.org/reference.html for the madoko reference).


## Organization
- The community is a group effort. If you see something that needs to be done, do it! Don't wait for someone else to do it.
- The community is a place for learning and sharing. Be respectful and constructive in your comments.
- @TimWhiting, @mccraigmccraig are the current community leaders with full access to the community settings in case you need help with anything.

## Licensing
- All code in the community repository is licensed under the MIT license, unless otherwise specified.