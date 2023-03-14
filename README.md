# Pull Request Version

Checks and updates the version of the Pull Request.

## Usage

```yaml

- name: PR Version Check
    uses: clockwork-marketing-uk/actions-pull-request-version@1.0.0
    with:
    github-token: ${{ inputs.github-token }}
    github-user: ${{ inputs.github-user }}
    pull-request-ref: ${{ inputs.branch-ref }}

```
