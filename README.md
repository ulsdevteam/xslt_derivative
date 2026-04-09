# XSLT Derivative

This module provides a Drupal action for Islandora that applies an XSL Transform to the contents of a media and saves it as a new media on the same node. An example use case is generating a renderable HTML presentation for an XML-based resource.

This module uses the PHP built-in XSLTProcessor, with PHP functions enabled.

## Configuration

When you create an XSLT Derivative action, the XSL file defining the transform is saved as part of the action configuration, and you must specify a file system and path to save it in. You must specify a term that indicates the source XML media, and for the destination media you must specify a term, media type, mime type, file system and path. For the destination path, token replacement from the parent `node`, source `media`, and destination `term` is available.

## Copyright

This software is Copyright (C) 2025 University of Pittsburgh and is available under the MIT license.