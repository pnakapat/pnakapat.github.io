Write a static HTML code according to my requirements.
Style: Minimal, Modern.
Title: Artist Picker
Function of page: Show Thumbnail of images with CheckBox option for each image.
Function named clearOptions(): Uncheck all CheckBox, clear text value of Editable text area.
Function named generateText(): For each checked/uncheck CheckBox, concatenate the "filename (exclude file extension)" of those checked images, seperate by comma and put into Editable TextArea.
Layout from top to bottom of page...
Header text: Artist Picker
Element:Editable text area.
Element:Inline Button with no caption but use "refresh" icon of fontawesome.com. when clicked will execute clearOptions() function.
Element:Inline Button with no caption but use "copy" icon of fontawesome.com. When clicked will copy generated text to clipboard.
From this point downward is area to display images with CheckBox option. The images are all images (png/jpg/jpeg/webp) file store in "./images/artist/" path.
