## Useful tips and pointers

Here you will find ideas and solutions to specific tasks that you might wish to accomplish with _DOTEbase_.

- [Important things to note](#tip1)
- [What _DOTEbase_ is...](#tip2)
- [What _DOTEbase_ isn't...](#tip3)
- [How can I use _DOTEbase_ to support my qualitative analytical practices](#tip4)
- [How do I setup my audio-visual media and transcripts for use in _DOTEbase_](#tip8)
- [How do I backup my DOTEspace?](#tip5)
- [How do I add a whole tier with media clips to the Canvas?](#tip6)
- [What to do if you run out of devices when activating your paid license?](#tip7)
- [How to determine which objects are being tracked live in different tools?]() (#tip9)
- [How to track authorship of clips?]() (#tip10)
- [Why add transcript clips in _DOTEbase_ and not in _DOTE_?]() (#tip11)

### Important things to note? <a id='tip1'></a>

- _DOTEbase_ looks for projects and transcripts created with _DOTE_.
- A DOTEspace is the central organising unit
- Transcrips cannot be edited in _DOTEbase_.
Use the [Transcript Editor](https://bigsoftvideo.github.io/DOTE/howto.html) in _DOTE_ instead.
- Media cannot be added in _DOTEbase_.
Use the [Media Manager](https://bigsoftvideo.github.io/DOTE/media.html) in _DOTE_ instead.
- Projects cannot be created in _DOTEbase_.
Use _DOTE_ instead to [manage Projects](https://bigsoftvideo.github.io/DOTE/projects.html).
- _DOTEbase_ stores a local cache of the watch folders in every [DOTEspace](dotespace.md).
The [DOTEspace Crawler](glossary.md#crawl) searches all watch folders and updates the cache at startup and when changes are detected.
- Changes made to a DOTEspace, clip or collection are immediate and irreversible.
There is no undo mechanism.
The exception is the [Canvas](canvas.md), which has undo/redo functionality.
- [Transcript Clips](transcript-clip.md) added in _DOTE_ to any Transcript in a watch folder will be detected by the [DOTEspace Crawler](glossary.md#crawl) when the Transcript is saved.
- All data and meta-data used by _DOTEbase_ is unencrypted.
Use your own software/hardware encryption.
- All data and meta-data is local to the computer.
Nothing is uploaded to the web or cloud.

### What _DOTEbase_ is... <a id='tip2'></a>

- It is a tool to support qualitative analysis.
- It is a set of flexible, assembled spaces consisting of locally distributed media and transcripts.
- It is a tool that supports commenting on clips of media and transcript.
- It is a tool that uses data and meta-data that is transparent and non-proprietary.

### What _DOTEbase_ isn't... <a id='tip3'></a>

- It is NOT a tool for quantitative analysis.
- It is NOT a closed database.
- It is NOT a web tool.
- It is NOT a cloud-based tool.
- It is NOT a miracle that uses AI to do analysis for you!

### How can I use _DOTEbase_ to support my qualitative analytical practices <a id='tip4'></a>

There are lots of ways to use _DOTEbase_ to support what you do and also to encourage you to try new methods of doing qualitative analysis.
See [our list](use-cases.md) that outlines some of them.
We are always open to new uses of DOTEbase or ideas for new tools.
Let us know by [email](email:dote@ikl.aau.dk) or on one of the _DOTEbase_ channels on our [Discord server](https://discord.gg/8BmuHP7xh4).

### How do I setup my audio-visual media and transcripts for use in _DOTEbase_ <a id='tip8'></a>

It is important to remember that _DOTEbase_ feeds off of individual projects created in _DOTE_.
One cannot add audio-visual files and text transcripts that are not already prepared with _DOTE_.
The reason is that there isn't any relevant metadata in a file or document on its own.
Hence, one must at a minimum [create a project with a blank transcript in DOTE](https://bigsoftvideo.github.io/DOTE/projects.html) in one of the [watch folders](dotespace.md) that are tracked by a DOTEspace.
New Projects and Transcripts can be created at any time; as long as they are in one of the watch folders, _DOTEbase_ will find them and add them to the relevant DOTEspaces.
Media can be added and more Transcripts can be added to that _DOTE_ Project or edited; _DOTEbase_ will track all the changes.

### How do I backup my DOTEspace? <a id='tip5'></a>

There is no dedicated autobackup system yet in _DOTEbase_, but you can manually archive the whole DOTEspace as follows:
- Select `FILE/EXPORT` from the menu bar to [export the DOTEspace](export.md).
- Select the DOTEspace you wish to archive from the drop-down list.
- Select all checkpoints, autobackups, colllections data, Canvas data, clips etc.
- Export to a safe location on your file system. Give it a clear name with a date + time stamp.
- Then you can safely import the archive at a later point.

### How do I add a whole tier with media clips to the Canvas? <a id='tip6'></a>

One can Send individual Clips to the [Canvas](canvas.md), but there is also a way to send a whole [Tier](media-clips-organiser.md) of [Media Clips](media-clip.md) to the Canvas.
- Open the [Media Clips Organiser](media-clips-organiser.md).
- Right click on a designated Tier.
- Select `Send Tier to Canvas`.
- Open the Canvas for that DOTEspace.
- All the clips in that Tier will be listed next to the Canvas and can be dragged and dropped.

### What to do if you run out of devices when activating your paid license? <a id='tip7'></a>

If you have no more devices available on your license, then you may have to deactivate some of the devices for _DOTE_ and/or _DOTEbase_.
_DOTE_ and _DOTEbase_ share the same license, and each uses one device per installation. Thus, installing both uses two devices from your quota.
See [License Activation](license-activation.md) for more help.

### How to determine which objects are being tracked live in different tools? <a id='tip9'></a>

There is an indirect way to get some idea of what clips or tags are being tracked live by _DOTEbase_.
If one makes a Project and/or Transcript unavailable in the [DOTEspace](dotespace.md) panel, then this will directly and immediately change what is displayed in [Tag Manager](tags.md), [Collections Browser](collections-browser.md), [Collection Viewer](collection-viewer.md), [Search](search.md) and [Canvas](canvas.md).
Thus, one can determine visually which clips attached to a Project and/or Transcript are relevant to Tags, Collections, Searches or a Canvas with a specific [scope](scope.md).

### How to track authorship of clips? <a id='tip10'></a>

_DOTEbase_ does not support natively an authorship meta-data structure, but users can create their own using a user-defined field (UDF) when creating or editing a clip.
If a user-defined field is created with `Name` set as "@author" and `Value` as the name or initials of the author and this is done consistently, then one can [Search](search.md) for this value of the named UDF to find all [Clips](clips.md) authored by `Value`.
For example, a UDF with `Name`: "@author" and `Value`: "Jane Smith" would be searchable by selecting a UDF Search Target and searching for "@author" AND with a UDF criteria "Jane Smith" to narrow down.
Just searching for "@author" would return all clips by all authors.

### Why add transcript clips in _DOTEbase_ and not in _DOTE_? <a id='tip11'></a>

One can add [Transcript Clips](transcript-clip.md) in _DOTE_, but there are more sophisticated tools for managing and organising [Tags](tags.md) and [Colour Swatches](colour-manager.md) in _DOTEbase_.
