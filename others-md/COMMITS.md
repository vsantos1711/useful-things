# 📜 Commits patterns

According to the **[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)**, semantic commits are a simple convention for using commit messages. This convention defines a set of rules for creating an explicit commit history, which makes it easier to create automated tools.

These commits will help you and your team to easily understand what changes were made in the code snippet that was committed.

This identification occurs through a word and emoji that identifies whether the committed change is related to code alteration, package updates, documentation, visual changes, tests, and more.

## Type and Description

The semantic commit has the following structural elements (types), which inform the intention of your commit to the code user.

- `feat`- Commits of type feat indicate that your code snippet is including a **new feature** (relates to the MINOR of semantic versioning).

- `fix` - Commits of type fix indicate that your committed code snippet is **fixing a problem** (bug fix) (relates to the PATCH of semantic versioning).

- `docs` - Commits of type docs indicate that there have been **changes in documentation**, such as in your repository's README. (Does not include code changes).

- `test` - Commits of type test are used when **changes are made in tests**, whether creating, altering, or deleting unit tests. (Does not include code changes)

- `build` - Commits of type build are used when modifications are made to **build files and dependencies**.

- `perf` - Commits of type perf are used to identify any code changes related to **performance**.

- `style` - Commits of type style indicate that there have been changes related to **code formatting**, semicolons, trailing spaces, lint... (Does not include code changes).

- `refactor` - Commits of type refactor refer to changes due to **refactoring that do not alter its functionality**, such as a change in the format of how a certain part of the screen is processed, but that maintained the same functionality, or performance improvements due to a code review.

- `chore` - Commits of type chore indicate updates to build tasks, administrator configurations, packages... such as adding a package to gitignore. (Does not include code changes)

- `ci` - Commits of type ci indicate changes related to **continuous integration**.

- `raw` - Commits of type raw indicate changes related to configuration files, data, features, parameters..

- `cleanup` - Commits of type cleanup are used to remove commented-out code, unnecessary snippets, or any other form of cleaning up the source code, aiming to improve its readability and maintainability.

- `remove` - Commits of type remove indicate the deletion of files, directories, or obsolete or unused features, reducing the size and complexity of the project and keeping it more organized.

## Recommendations

- Add a type consistent with the content title.
- We recommend that the first line should have a maximum of 4 words.
- To describe in detail, use the commit description.
- Use an emoji at the beginning of the commit message representing the commit.

## Examples

<table>
  <thead>
    <tr>
      <th>Git Command</th>
      <th>Result on GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m ":tada: Initial commit"</code>
      </td>
      <td>🎉 Initial commit</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":books: docs: Update README"</code>
      </td>
      <td>📚 docs: Update README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bug: fix: Infinite loop at line 50"</code>
      </td>
      <td>🐛 fix: Infinite loop at line 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":sparkles: feat: Login page"</code>
      </td>
      <td>✨ feat: Login page</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bricks: ci: Modify Dockerfile"</code>
      </td>
      <td>🧱 ci: Modify Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":recycle: refactor: Switch to arrow functions"</code>
      </td>
      <td>♻️ refactor: Switch to arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":zap: perf: Improve response time"</code>
      </td>
      <td>⚡ perf: Improve response time</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":boom: fix: Revert inefficient changes"</code>
      </td>
      <td>💥 fix: Revert inefficient changes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":lipstick: feat: Form CSS styling"</code>
      </td>
      <td>💄 feat: Form CSS styling</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":test_tube: test: Create new test"</code>
      </td>
      <td>🧪 test: Create new test</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":bulb: docs: Comments on LoremIpsum( ) function"</code>
      </td>
      <td>💡 docs: Comments on LoremIpsum( ) function</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":card_file_box: raw: RAW Data of year yyyy"</code>
      </td>
      <td>🗃️ raw: RAW Data of year yyyy</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":broom: cleanup: Remove commented-out blocks and unused variables in form validation function"</code>
      </td>
      <td>🧹 cleanup: Remove commented-out blocks and unused variables in form validation function</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m ":wastebasket: remove: Remove unused files to maintain organization and continuous updating"</code>
      </td>
      <td>🗑️ remove: Remove unused files to maintain organization and continuous updating</td>
    </tr>
  </tbody>
</table>
