# Uploader specification
The uploader is available in two modes, but always serves the same purpose: uploading images to the system.

## Simple mode
The simple mode can only upload one image at a time, but it has quite a few options: 
- Setting the tags (with autocompletion and validation), possibly creating them if they don't exist
- Setting the albums (with autocompletion and validation), possibly creating them if they don't exist
- Setting the NSFW flag
- Editing the image in browser (using canvas, if supported) to allow text overlay and cropping
- Setting the name and description
- Chaining into itself, keeping its settings between images
- Support for file picker, drag-and-drop and url (using server as proxy)

## Mass upload mode
The mass upload mode uploads a lot of images at once using the same parameters: same tags, albums and NSFW flag. It then displays a list of uploaded images with the following options: 
- edit tags
- edit albums
- edit name
- edit flag
- edit description
- delete
