
<!-- README.md is generated from README.Rmd. Please edit that file -->

# sys-admin-cheatsheet

<!-- badges: start -->

<!-- badges: end -->

Because sometimes you just need a quick reminder of that incantation to
get things done.

This is a cheetsheat for RStudio Team system administration.

View the deployed version at
<https://colorado.rstudio.com/rsc/rstudio-team-sysadmin-cheatsheet/>

![](thumbnail.png)

## Git backed deployment to RStudio Connect

The file `sys-admin-cheatsheet.Rmd` is deployed automatically to RStudio
Connect using [git-backed
deployment](https://docs.rstudio.com/connect/user/git-backed.html). This
happens with every commit to the master branch on github.

To update the manifest file (for example if you add images or other file
dependencies) run:

``` r
rsconnect::writeManifest(appPrimaryDoc = "sys-admin-cheatsheet.Rmd")
```
