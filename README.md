# Tapes

## Cataloging Methodology

### Metadata
- XML or some other format?
- Embedded?

Still considering metadata options - I'll be looking for standards and best-practices within archival processes (libraries, etc.)

### Collection Notes
- Spreadsheet?

I've started using Google Sheets and will likely convert to Excel so I can have better version-control using git.  Google Sheets is a great option for the working files but I haven't come across an elegant solution for using it with git.

### Collection Images
- Images of both sides of tapes for handwritten labels and tape info

First round of images are finished.  I'll probably get studio images in the Labs at D.C. to be safe (before cutting open cassettes to repair tape).

### Recording Settings
Audio will now be converted to digital using Adobe Audition.  I think the spectral graph may be necessary to get the most quality I can from the tapes.

Noting these recording settings before I forget:

- Sample Rate:  44100Hz
- Channels:  Mono
- Bit Depth:  32 bits

Note to self:

Record between -12db to -6db and normalize to -3db on export.

### git Structure
I'll be updating the git structure in the next few weeks - sorting audio, images, text, etc as well as setting up the `.gitignore` file.  Audio will not be backed up to git; Images might be but it will only be reference quality images.  All archival quality files (and files to be served to an eventual site) will either be stored privately on Google Drive or on a CDN.  Audio files will likely be made public at some point in the future.

**All of this information needs to be stored in a more coherent way but will live in the README until I can sort it more deliberately.**
