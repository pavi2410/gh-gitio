> ⚠️ [Git.io no longer accepts new URLs](https://github.blog/changelog/2022-01-11-git-io-no-longer-accepts-new-urls/). Time to say goodbye! 

---

# gh-gitio
gh extension to generate short git.io URLs for GitHub sites

### Install
```sh
gh extension install pavi2410/gh-gitio
```
Requires `bash`, `curl`. As such, it doesn't work on Windows, although you can use `curl.exe` on Windows.

### Usage
```sh
gh gitio <Long URL> <short code>
```

This generates a URL of the form `git.io/<short code>` (Look for the `Location` header in the output ;)
