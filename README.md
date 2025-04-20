# Game At Crit

This is the website for gameatcrit.com.

There are two branches:
* main - the live site
* dev - for development

Each branch is connected to a DigitalOcean App Platform static site. All commits to `main` will be pushed to the main site, `https://gameatcrit.com/`.  All commits to `dev` will be pushed to the dev site, `https://dev.gameatcrit.com/`.

## Workflow
All changes should be committed to the dev branch, which will trigger a new deploy of the dev site. The changes can then be evaluated in real browsers by real human beings to confirm things look right.

When pending changes are approved, the dev branch can be merged to main. The dev branch *should not* be deleted.

If you need or want access to this repo, just ask!
