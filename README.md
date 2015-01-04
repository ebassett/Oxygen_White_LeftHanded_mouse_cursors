Oxygen_White_LeftHanded_mouse_cursors
=====================================

The (X11) mouse cursors (pointers) that come with (among others) openSUSE KDE installations, converted for left-handedness.

# LICENSE NOTE:
  The **real** license for these is the same as the right-handed version that ships with openSUSE/KDE. I have not been able to **definitively** determine what that is, but I **believe** it is the GPL v3 (or greater), so that is what I have said.

# OBSOLESENCE NOTE:
  While trying to determine the license to use, I came across Marcus Haro's published implementation (under the LGPL license) here:
    http://kde-look.org/content/show.php/Oxygen+White+Left+Handed?content=165028
  I have no reason to assume that my version is better than his; and, indeed, his contains substantially more files; and his description at the above link indicates more testing on more platforms.

  **=> You should probably just use the above version rather than this one.**


# INSTALLATION
  If you *really* want to ignore the above warning and use these anyway, you are better off to grab just the tarball and unpack it into either /usr/share/icons/ or ~/.icons/ depending on whether you want them globally available or just for your current user.
  The reason that the tarball is better than fetching all of the loose files is that the former preserves the symlinks, of which there are (by X11 design) *many*; but I think that git[hub] does not naturally preserve symlinks, so you will end up with either a bunch of broken links (and hence cursors) or (more likely) a whole bunch of separate *copies* of the various mouse cursors (which would work, but would be a waste of disk space (not very much, in actuality, but still, it's the principle of the thing) and a maintenance nightmare (not that you probably would actually throw much (any) maintenance at your mouse cursors - but again, it's the principle of the thing)).

