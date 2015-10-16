# svn-notes
Subversion (SVN) notes.

## TortoiseSVN

* [AndersDJohnson/TortoiseSVN-extras][extras]

### Diff Viewer

#### WinMerge

* Diff Viewer: `C:\Program Files (x86)\WinMerge\WinMergeU.exe -e -ub -dl %bname -dr %yname %base %mine`
* Merge Tool: `C:\Program Files (x86)\WinMerge\WinMergeU.exe -e -x -ub -dl %bname -dr %yname %base %mine`

#### KDiff

* Diff Viewer: `C:\Program Files\KDiff3\kdiff3.exe %base %mine %theirs -o %merged --L1 Base --L2 Mine --L3 Theirs`
* Merge Tool: `C:\Program Files\KDiff3\kdiff3.exe %base %mine  --L1 Base --L2 Mine`

[extras]: https://github.com/AndersDJohnson/TortoiseSVN-extras
