# upload-release-assets

## Usage

```yaml
jobs:
  cmake_and_upload:
    runs-on: windows-2019
    steps:
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
1. [AButler/upload-release-assets](https://github.com/AButler/upload-release-assets) 
1. [xresloader/upload-to-github-release](https://github.com/xresloader/upload-to-github-release) 