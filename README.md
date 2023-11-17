# Pull Request Version

Checks and updates the version of the Pull Request.

## Usage

```yaml

- name: PR Version Check
    uses: clockwork-marketing-uk/actions-pull-request-version@1.2.1
    with:
      github-token: ${{ secrets.GITHUB_TOKEN }}
      github-user: ${{ github.actor }}
      pull-request-ref: ${{ github.event.pull_request.head.ref }}
      fa-npm-token: ${{ secrets.fa_npm_token }}
      npm_token: ${{ secrets.npm_token }}
      pull-request-base-branch: version-1

```
