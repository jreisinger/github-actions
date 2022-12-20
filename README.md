# github-actions
Reusable [workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows) for GitHub actions. This
makes it easier to maintain GitHub actions across projects. Stolen from [pete911](https://github.com/pete911/github-actions).

## go
`jreisinger/github-actions/.github/workflows/go.yml@main` runs unit tests, go vet and trivy scan.

### inputs
| input        | default | description |
|--------------|---------|-------------|
| go-version   | 1.19.4  | go version  |
