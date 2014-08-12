mp_tinymce_insertpicture
========================

A plugin for TinyMCE 4 to insert images as Base64 inline with the text.

Features:
 - File size limit (1 mebibyte, can easily be changed).
 - Image size limit (800x600, can easily be changed).
  - Images above the limit are resized.
 - Previews the selected image.
 - Works entirely in JavaScript, no server backend required.

Requires HTML5.

Forked from https://github.com/buddyexpress/bdesk_photo.git. Main differences:
 - Previews the selected image.
 - Validates the image upon file selection instead of after confirmation.
 - Resizes the image if necessary.

Improvement opportunities:
 - No i18n support -- messages are in English, need to be changed in the code for other languages.
 - The same Canvas is currently used for preview and for resizing.
 - Settings (maximum file and image sizes) should be configured by the client.
 
Developed for Ministério Público do Rio Grande do Sul (http://mprs.mp.br).