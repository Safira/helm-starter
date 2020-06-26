## Usage

```sh
git clone https://github.com/safira/helm-starter.git $HOME/Library/helm/starters/safira
helm create -p safira .helm
```

## Test run

`helm upgrade --install --dry-run --debug test .`

## secrets

Example on how to map k8s secrets to environment variables can found in `template/deployment.yaml`. Available keys can be found with `kubectl describe secret pulumi`.