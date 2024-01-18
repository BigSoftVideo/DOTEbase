## Glossary of key terms in _DOTEbase_

A familiarity with _DOTE_ is not essential when annotating and tagging audio-visual media in _DOTEbase_ workspaces, but other functionality is dependent on a working knowledge of _DOTE_ projects and transcripts.
See our [online help guide for _DOTE_](https://bigsoftvideo.github.io/DOTE/), which has more information on getting started with _DOTE_.

Below is a list of key terms in alphabetical order with short definitions and links to relevant help pages for more information.

### Active Media <a id='active-media'></a>

When a media file or a transcript in a _DOTEspace_ are selected for display, then the media becomes active and is displayed in the [Media Player](#media-player) panel.

### Active Transcript <a id='active-transcript'></a>

When a [Transcript panel](#transcript-panel) is set as Active, then when a new [Transcript](#transcript) is viewed that Transcript is displayed in the active transcript panel.
Multiple transcript panels can be open at the same time, so one needs to select which one is currently Active.
As a result, the others are unactivated.

### Annotation <a id='annotation'></a>

An Annotation is a plain text note called a [Comment](#comment) about a specific [Clip](#clip).

### Canvas <a id='canvas'></a>

A Canvas is a visual representation of states and relationships between a variety of objects in and across [DOTEspaces](#dotespace).
For example, representations of [Transcript Clips](#transcript-clip), [Media Clips](#media-clip), [Tags](#tag), [Clip Collections](#clip-collection), etc. can be dragged and dropped onto the independent Canvas.
Relationships between objects can be constructed using a basic set of icons, arrowheads, lines and borders.

### Clip <a id='clip'></a>

A Clip is a shorter segment of a media file or an excerpt from a [_DOTE_ transcript](#dote-transcript).
We call the first a _Media Clip_.
It saves the IN and OUT points of a segment in an audio or video file imported into a [_DOTE_ project](#dote-project) that is in a [Watch Folder](#watch-folder) in a [DOTEspace](#dotespace).
The second we call a _Transcript Clip_.
It saves the starting character/line and ending character/line in a transcript file imported into a [_DOTE_ project](#dote-project) that is in a [Watch Folder](#watch-folder) in a [DOTEspace](#dotespace).

### Clip Collection <a id='clip-collection'></a>

A Clip Collection is a set of of [Clips](#clip) across one or more [DOTEspaces](#dotespace).

### Collection Viewer <a id='collection-viewer.md'></a>

A Collection Viewer is an ordered list of [Clips](#clip) in each [Clip Collection](#clip-collection). 

### Collections Browser <a id='collections-browser.md'></a>

A Collections Browser is an ordered list of all current [Clip Collections](#clip-collection).

### Comment <a id='comment'></a>

A Comment is a text field attached to [Clips](#clip).

### Crawl <a id='crawl'></a>

A Crawl is a background process that maintains the integrity of all current [DOTEspaces](#dotespace) by scanning all the [Watch Folders](#watch-folder).
Because [DOTE projects](#dote-project) can be stored on media that go offline, or projects and [transcripts](#dote-transcript) can be created or renamed, the _DOTEbase_ has to be check regularly to keep everything up-to-date.
It can also be initiated manually.

### DOTE Project <a id='dote-project'></a>

A DOTE Project is a container created using our _DOTE_ software.
It consists of all temporally synchronised media files and all [Transcripts](#dote-transcript) associated with one continuous event.

### DOTE Transcript <a id='dote-transcript'></a>

A DOTE Transcript is a transcript created using our _DOTE_ software.
It is a specific textual object that is contained within a [DOTE Project](#dote-project).

### DOTEspace  <a id='workspace'></a>

A DOTEspace is a workspace for working on thematically organised sets of DOTE projects and transcripts that are distributed across your file system.

### Export <a id='export'></a>

A single DOTEspace can be Exported in order to archive or share that DOTEspace with someone else.

See [Import](#import).

### Import <a id='import'></a>

A single DOTEspace can be imported into _DOTEbase_.
To do so, a DOTEspace has to [Exported](#export) from _DOTEbase_ into a `.dotebase` file, which can be shared or archived.

### License <a id='license'></a>

A License is an encrypted file that is used to authenticate the user of _DOTEbase_ (as a purchaser of _DOTE_).
Without a valid license, _DOTEbase_ cannot be used.

### Line number <a id='line-number'></a>

Line Numbers are inherited from _DOTE_.
They are the abstract Line Numbers displayed in _DOTE_'s Transcript Editor.
A temporary, unique number is assigned in ascending order to each and every line.
It is not the same as the line numbering after exporting a transcript into RTF, for example.

### Media Clip <a id='media-clip'></a>

A Media Clip saves the IN and OUT points of a segment in an audio or video file imported into a [_DOTE_ project](#dote-project) that is in a [Watch Folder](#watch-folder) in a [DOTEspace](#dotespace).

Media Clips are also known as M-Clips.

### Media Clips Organiser <a id='media-clips-organiser'></a>

The Media Clips Organiser is a tool to visually arrange and order [Media Clips](#media-clip) created in _DOTEbase_.
M-clips can be assigned to [Tiers](#tier).

### Media Player <a id='video-panel'></a>

The Media Player displays a viewport of the selected or cued media file that matches the _DOTE_ Transcript and/or Project that is currently active.
If selected using the toggle, the video panel can track the original [video-cues](#video-cue) in the referenced _DOTE_ Transcript and Project.
As the media stream plays in the _DOTE_ project, the video and pan/zoom will match that cue.
An alternative view is to take the last SAVED view when using _DOTE_ to view the media in the Project.
And a third alternative is a DOTEbase only saved view of the current video in the current Project.

### Scope<a id='scope'></a>

Different functions in DOTEbase work with different levels of data and meta-data.
They have [Scope](scope.md) in which they operate.
For example, [Search](#search) works over the current DOTEspace, yet the [Media Clips Organiser](#media-clips-organiser) displays Media Clips in the current one Project.

### Search <a id='search'></a>

_DOTEbase_ can search in a DOTEspace for a text string in a variety of data/meta-data.

### Tag <a id='tag'></a>

A Tag is a short, thematic text string that can be assigned to any [Clip](#clip).
Tags are searchable and autocompleteable.

### Tier <a id='tier'></a>

Tiers and subtiers are usually found in transcripts, but in _DOTEbase_ Media Clips can be organised on their own Tiers.
Tiers can be created, renamed and colour coded.
Media Clips can be dragged between Tiers.

### Timecode (or Timestamp) <a id='timecode'></a>

A Timecode is a temporal reference to a specific moment in a playable media file, starting at 0:00:00.0 `[hour:min:sec.tenth_of_sec]`.

### Timeline <a id='timeline'></a>

The Timeline is a linear graphical representation of time passed in a specific [_DOTE_ Transcript](#dote-transcript).

See [Waveform](#waveform).

### Transcript <a id='transcript'></a>

A Transcript is a textual document that represents a transcribed version of an event captured in audio-visual media.
Transcripts are created in DOTE and are viewable in [DOTEspace](#dotespace) if the _DOTE_ Project/Transcript is included in the scope of the DOTEspace watch folder(s).

### Transcript Clip <a id='clips.md#transcript'></a>

A Transcript Clip saves the starting character/line and ending character/line in a transcript file imported into a [_DOTE_ project](#dote-project) that is in a [Watch Folder](#watch-folder) in a [DOTEspace](#dotespace).

Transcript Clips can be assigned a specific shape and line/box colour.

Transcript Clips are also known as T-Clips.

### Transcript panel <a id='transcript-panel'></a>

In a [DOTEspace](#dotespace), a Transcript panel displays any [Transcript](#transcript) document that has been created and edited in _DOTE_.

### Unicode <a id='unicode'></a>

[Unicode](https://home.unicode.org) is a global standard for representing languages, symbols and emojis.

### User-defined Field <a id='user-defined'></a>

A User-defined Field is a special field that a user can define and assign to any [Clip](#clip).
It has a name and a value.
For example, the name could be defined in terms of a phenomenon, and a set of values used that qualify that phenomenon or a boolean value (yes/no) that can record if it is present or not in the Clip.
User-defined Fields are searchable.

### User Interface (UI) <a id='ui'></a>

The [User Interface](ui.md) is the visual (and aural) presentation of the computer application to the user.

### Video-cue <a id='video-cue'></a>

A [Video-cue](cues.md) in _DOTE_ is a unique point on the [Timeline](timeline.md) that indicates that a change in the [Viewport](#viewport) of the video in the  [Media Player](#media-player) is to be performed.
This function automates the presentation of media during [Playback](play.md) in a more cinematic fashion.

### Viewport <a id='viewport'></a>

The Viewport is the rectangular portion of the video that is currently visible in the frame of the [Media Player Panel](#media-player).

### Warnings and Errors <a id='error'></a>

_DOTEbase_ can flag [Warnings and Errors](errors.md) in the use of _DOTEbase_.

### Watch Folder <a id='watch-folder'></a>

One or more Watch Folders are found in a [DOTEspace](#dotespace).
It is an assigned folder on your file system that _DOTEbase_ [watches and crawls](#crawl) to find and log DOTE Projects and their Transcripts.

### Waveform <a id='waveform.md'></a>

In a [Timeline](timeline.md), a Waveform representing the amplitude over time of a selected audio track can be displayed.
This is generated by _DOTE_ when a media file is imported into a [_DOTE_ Project](#dote-project) using _Media Manager_.






###  <a id=''></a>

A  is...
