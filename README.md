# strabon-pins

Public image host for **Strabon Social** Pinterest pins.

Pinterest's bulk-upload CSV requires a public `Media URL` for every pin, so the
generated pin images live here and are served from
`https://raw.githubusercontent.com/koseogu/strabon-pins/main/`.

## Do not delete or rewrite any image in this repo

Live Pinterest pins point at these URLs **forever**. Deleting a file, renaming
it, or replacing its contents turns a live pin blank. Adding new files is always
safe; removing or changing existing ones is not.

The repo is public on purpose: Pinterest's crawler fetches these files without
logging in, so a private repo would return 404 to it.

No credentials belong here. Tokens live in `C:\Strabon\social\.env`, which is
gitignored and outside this repo.
