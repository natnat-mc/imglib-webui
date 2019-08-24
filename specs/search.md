# Search specification
The search functionality is present it three forms, and is used and available across the interface.

## Tag/album search
The tag/album search is a simple input widget that finds and autocompletes (with a drop-down ui) tags or albums, based on the first characters. It is primarily used embedded in other widgets. A version exists that allows creation with default values.

## Simplified search bar
The simplified search bar is a search bar with the following options: 
- NSFW flag (defaults to no)
- Mode selection: [image](image.md) (default), [album](album.md) or [tag](tag.md)
- Tag autocompletion and confirmation (using the tag search) (defaults to AND mode but can be changed in the [settings](settings.md))
- Search mode: query (default) or exact match
- More options, leading to the advanced search page

## Advanced search page
The advanced search page is a page allowing for all possible searches that can be processed by the server. It is centered around a text input used for either exact match or query matching (default), and a resource type selector (defaulting to image). It has the following options: 
- before/after (image)
- color (tag)
- tag combo (image, album) (allows for AND list, OR list and NOT list)
- nsfw flag (image, album, tag) (defaults to no)
- min/max image count (album, tag) (defaults to >=1)
- min/max album count (tag)
