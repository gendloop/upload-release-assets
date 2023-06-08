# upload-release-assets

## Usage

```yaml
- name: upload-release-assets
      uses: gendloop/upload-release-assets@main
      with:
        releaseTag: 'v1.2.3'
        githubToken: ${{ secrets.GITHUB_TOKEN }}
        files: |
          ./upload/*.zip
        overrideExistingArtefact: true
```



## References

1. [echapmanFromBunnings/upload-release-assets](https://github.com/echapmanFromBunnings/upload-release-assets) 