# iliads_theme
This repository should hopefully make it easier for ILiADS folks to work on the theme for the website.

## Assumptions re: branch structure
- Master should always be safe for production
- There's a branch for each year that contains site-specific colors, etc.
- Developers are welcome to make individual branches for dev work and experimentation
- When changes are ready to go live, they should first be merged into the site-and-year-specific branch, then into master
- If we want, the site can be reverted back to master or to an "iliads_plain" branch in between the end of a conference and the beginning of the next conference cycle
- Master is the default branch in the repo

## To update the theme for a new year/institution:
* Start with `master` branch checked out
* Create a new branch with the year and/or institution name
* Check out the new branch 
* Remove colors/themes from a previous year and replace with the ones for the current design scheme
* NOTE: this is just to add them in as a reference for yourself. You (or someone) will still have to go through and decide where to apply those colors. Hopefully we'll adjust the theme to allow fuller use of color mixins for the future, but we're not there yet.