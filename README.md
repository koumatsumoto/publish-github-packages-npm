# koumatsumoto/publish-github-packages-npm

The GitHub Action to publish npm packages to GitHub Packages registry.

## sample code

```yaml
- uses: koumatsumoto/publish-github-packages-npm@v1
  with:
    auth_token: ${{ secrets.GITHUB_TOKEN }}
    version: 1.0.0
```
