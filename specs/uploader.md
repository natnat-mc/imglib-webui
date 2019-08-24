# Uploader specification
The uploader is available in two modes, but always serves the same purpose: uploading images to the system.  
Depending on config, images may or may not inherit the tags of their albums (defaults to no).

## Simple mode
The simple mode can only upload one image at a time, but it has quite a few options: 
- Setting the [tags](tag.md) (with autocompletion and validation), possibly creating them if they don't exist
- Setting the [albums](album.md) (with autocompletion and validation), possibly creating them if they don't exist
- Setting the NSFW flag
- Editing the image in browser (using canvas, if supported) to allow text overlay and cropping
- Setting the name and description
- Chaining into itself, keeping its settings between images
- Support for file picker, drag-and-drop and url (using server as proxy)
- Support for sequential add with one file selection

## Mass upload mode
The mass upload mode uploads a lot of images (using file picker, drag-and-drop or url textarea) at once using the same parameters: same tags, albums and NSFW flag. It then displays a list of uploaded images with the following options: 
- edit tags
- edit albums
- edit name
- edit flag
- edit description
- delete
