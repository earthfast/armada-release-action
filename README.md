# Armada Release Action

A GitHub Action for preparing releases to be published on the Armada network.

## Usage

See [action.yml](action.yml)

```yaml
steps:
- uses: armada-network/armada-release-action@v1
  with:
    build_dir: build|dist|out|...
    bundle_name: your-project-${{ github.ref_name }}
    github_token: ${{ secrets.GITHUB_TOKEN }}
```
