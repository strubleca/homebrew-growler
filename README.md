# homebrew-growler
Casks that used to be, in my little container.

See [homebrew](http://brew.sh) and [homebrew cask](https://caskroom.github.io) for details on the parent projects.

Feel free to tap this and use as desired. Updates may be infrequent.

# Casks

## r-vendor

The `r-vendor` cask installs the official R for OS X distribution from the [R Project](https://www.r-project.org/). This cask was removed from homebrew cask in favor of the homebrew formula during the integration of cask into the core homebrew project. Background on the migration can be found in issues [#14384](https://github.com/caskroom/homebrew-cask/issues/14384) and [#15603](https://github.com/caskroom/homebrew-cask/issues/15603). Reasons for resurrecting this cask are discussed in [#23584](https://github.com/caskroom/homebrew-cask/pull/23584).

As an R user since 2003 on Mac, Linux, and Windows, I highly recommend pre-built distributions from the R community for most users. For Mac and Windows, pre-built R package binaries are installed by default. This reduces the number of dependencies to install and having to work through complex compilation issues. Getting support from the R community is also easier with the official builds. A disadvantage of the cask is that it installs distributions of Tcl/Tk and Ghostscript that may stomp on those built by homebrew.

The source build of R through homebrew works well, but does create more management overhead. Until the R formula changes, R package installations are all installed from source and users may need to track down additional homebrew formulae to install for dependencies.  This is an experience consistent with source Python or Ruby installations from homebrew. I have found, though, that installing R packages from source can be trickier than those for other languages.

Both the cask and formula are viable options for R users on the Mac. Choose the one that seems to suit your needs best.



