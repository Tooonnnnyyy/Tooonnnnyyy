# Publishing this profile

GitHub displays `/README.md` from a public repository whose name exactly matches the username:

```text
Tooonnnnyyy/Tooonnnnyyy
```

The GitHub CLI token currently available on this Mac is invalid, so this folder is a local draft.
When GitHub access is available:

```bash
cd /Users/bjt/github-profile-readme
git init -b main
git add README.md SETUP.md
git commit -m "docs: add GitHub profile README"
git remote add origin https://github.com/Tooonnnnyyy/Tooonnnnyyy.git
git push -u origin main
```

If the repository already exists, use `git clone` instead of `git init` and review its existing
README before replacing content. Do not add tokens, private email addresses, or analytics scripts.
