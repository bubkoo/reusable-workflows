# reusable-workflows

- [semantic-release](semantic-release)
- [release-github-action](#release-github-action)

## semantic-release
```yml
uses: bubkoo/reusable-workflows/workflows/semantic-release.yml@master
secrets:
  app-id: ${{ secrets.APP_ID }}
  private-key: ${{ secrets.PRIVATE_KEY }}
  npm-token: ${{ secrets.NPM_TOKEN }}
```

## release-github-action