# AppImageRecipes
My AppImage recipes. Most are for programs I wasn't able to run on Arch Linux due to old dependencies (Ted is pretty much abandonware, for example, having not seen an update since 2012) or due to segfaults (the fact I can run these AppImages rule out glibc, though, unlike Loki Software's old games).

I haven't tried to commit them to pkg2appimage's upstream due to them not having AppStream data and/or skipping some dependencies.

# Ted (Ted-RTF.yml)

A replacement for Wordpad. Hasn't seen an update since 2012, though, so it uses Precise Pangolin's repos (dunno how long they'll be up since it's been a long while since Precise's been out of ESM, so get it while you can!)

# WinFF

Interface for FFMPEG, alternative to Handbrake. FFMPEG is skipped to save filesize, and so I don't have to cookup a way to have its config file point to the ever changing name of the AppDir.

# Impressive

PDF presentation with smooth transitions (like Okular's Ctrl+Shift+P mode, but prettier). It segfaults on Arch's version of Python and co. for some reason. So I tried it as an experiment on bundling Python in an AppImage.

# Edge-DEV

The edge.yml inside pkg2appimage's github, but with trusty's repo. Extraced .deb traces/breakpoints in my machine, but works fine as an AppImage.

# Slack

Discord clone.

# sK1

Inkscape alternative.
