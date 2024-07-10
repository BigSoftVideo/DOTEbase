## How to setup a DOTEspace

Watch [video tutorial](https://www.youtube.com/watch?v=TMZhcpxemcU) on YouTube.

Any number of DOTEspaces can be created using the DOTEspaces panel.
Each DOTEspace is assigned one or more Watch Folders in which DOTE Projects and Transcripts are scanned and loaded as a snapshot into _DOTEbase_.
Instead of creating a relational database containing all the Projects, Media, Transcripts, Clips, Tags etc in one place, the information is stored locally in each Project using transparent data structures.
This allows users to move their Projects, Media and Transcripts around without losing their Clips, Tags etc.
It decouples the Clips, Tags, etc from _DOTEbase_ and thus allows other software to access this data freely and easily (on the same computer with access granted) and support Clips, Tags, etc.

### Creating a new DOTEspace

_DOTEbase_ automatically scans all Watch Folders in all DOTEspaces for updates.
This is called crawling because _DOTEbase_ must look in all files, folders and subfolders in every watch folder.
This is necessary so that any changes found in the Watch Folders can be incorporated into the current snapshot.
If required, the user can manually start the crawl using the button at the top of the DOTEspace panel.

[![DOTE clipping](images/dotespace/create-dotespace.png)](images/dotespace/create-dotespace.png)

More than one Watch Folder is allowed in any DOTEspace so that users can keep their DOTE projects/transcripts in multiple locations and on external mapped drives.
Initially, all of the _DOTE_ projects/transcripts under each watch folder (including subfolders) are included in the relevant DOTEspace.
Individual projects and transcripts can be removed once the DOTEspace is scanned by toggling them off in the DOTEspace viewer.

[![DOTE clipping](images/dotespace/watch-folders.png)](images/dotespace/watch-folders.png)

It is important to appreciate the [scope of a DOTEspace](scope.md) in _DOTEbase_.

Because _DOTEbase_ scans watch folders that can be distributed across your file system, sometimes a drive or folder is not currently accessible.
_DOTEbase_ keeps a record (cache) of the last known folders/files and their location.
In the DOTEspace panel, Projects and Transcripts that have been found in watch folders can have different statuses (colour-coded), namely found/scanned, not found, inaccessible...

In the DOTEspace panel, Media and Transcript Clips can have different statuses (icons), namely original, copy or not found.

### Deleting a DOTEspace

When a DOTEspace is selected in the DOTEspace panel, it can be deleted using the `Delete Current DOTEspace` button.
The DOTEspace will be removed from the panel, including its watch folders.
The DOTEspace configuration is not recoverable.
Note that the data stored in those watch folders is NOT deleted, just the pointers to watch folders in the named DOTEspace.

### Status of objects in the DOTEspace panel

When a DOTEspace is created and a watch folder(s) added, then all Projects and Transcripts found in the watch folder(s) are listed.
Each Project and Transcript can be be toggled AVAILABLE/UNAVAILABLE.
This means that the Project and/or Transcript (and the associated clips) are no longer available to the _DOTEbase_ engine, eg. they are not listed, or listed as unavailable, in Collections Browser, Collection Viewer, Search, Tag Manager and Canvas.

When a Project and/or Transcript is viewed using the :eye: icon, then it becomes ACTIVE.
This means that the Project and/or Transcript (and associated clips) are viewable (peekable) in the Transcript panel, the Clips Viewer and the Media Clips Organiser.
They are viewable even if the Project and/or Transcript is toggled unavailable.

When multiple DOTEspaces, Projects and/or Transcripts are clicked using <kbd>SHIFT</kbd> or <kbd>CTRL</kbd> on Windows (<kbd>SHIFT</kbd> or <kbd>OPTION</kbd> on Mac), then they become a SELECTED group.
This means that the DOTEspaces, Projects and/or Transcripts in the selected group can be included in the scope of the Clips Viewer, Search, Canvas and Tag Manager (selected DOTEspace only).

### Actions available in the DOTEspace panel

The actions below are available for specific objects in the DOTEspace tree.

#### DOTEspace

- `Right click`
    - Rename or Edit Details
    - Add Watch Folder
    - Delete
    - Export
- Icon
    - Rename
    - Add Watch Folder

#### Watch-folder

- `Right click`
    - Open Folder Location
    - Remove Watch Folder
    - Create New Project (in same Watch Folder)
- Icon
    - Remove Watch Folder

#### Project

Projects are usually created and managed in _DOTE_, but certain actions can be launched from _DOTEbase_.

- `Right click`
    - Open
    - Open Folder Location
    - Rename Project
    - Delete Project
    - Create New Transcript (in current Project)
- Icon
    - View

#### Transcript

Transcripts are contained in Projects and they are usually created and edited in _DOTE_, but certain actions can be launched from _DOTEbase_.

- `Right click`
    - Open
    - Open Folder Location
    - Rename Transcript
    - Delete Transcript
- Icon
    - View

#### Clip

[Transcript Clips](transcript-clip.md) can be created and edited in _DOTEbase_ and _DOTE_, but [Media Clips](media-clip.md) can only be created and edited in _DOTEbase_.

- `Right click`
    - View
- Icon
    - View

### Notes

NOTE that DOTEspaces are not encrypted on your computer.
_DOTEbase_ stores all data and meta-data in human readable form in files on your computer.
If you wish to encrypt the data, then use software or hardware encryption on the relevant drives/folders as required.

NOTE that nothing is uploaded to the cloud by _DOTE_ or _DOTEbase_.
The only data stored is on your computer in the drives and folders you specify and the application folder.
