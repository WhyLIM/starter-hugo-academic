# Academic Site

This is my personal resume site create by [*Hugo Academic Theme*](https://github.com/wowchemy/starter-hugo-academic) template.

For local edit, please install:

- Git
- GO
- Hugo
- NodeJS

On Windows, *Scoop* is convenient to install these tools:

```bash
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
iwr -useb get.scoop.sh | iex

scoop install git go nodejs

# since this is a old version, don't use the latest version of hugo. Hugo 0.111.3 works by my test
scoop install hugo-extended@0.111.3
```

Then run `hugo server -D` in the project directory.

Some useful quick links:

- 👉 [**Get Started**](https://wowchemy.com/hugo-themes/)
- 📚 [View the **documentation**](https://wowchemy.com/docs/)
- ⬇️ **Automatically import your publications from BibTeX** with the [Hugo Academic CLI](https://github.com/wowchemy/hugo-academic-cli)
- ⬆️ **Updating?** View the [Update Guide](https://wowchemy.com/docs/hugo-tutorials/update/) and [Release Notes](https://github.com/wowchemy/wowchemy-hugo-themes/releases)

