##List of plugins used in TinyMCE

1. advlist - Create styled number and bulleted lists.
eg:
tinymce.init({
    selector: 'textarea',  // change this value according to your html
    plugins: 'advlist',
    advlist_bullet_styles: 'square'  // only include square bullets in list
});

2. autolink - Automatically creates hyper-link when user types valid URL.

3. lists - Allows to add bulletes/numbered list.

4. link - Add hyperlinks to content. 

5. image - Inserts image in TinyMCE.
eg:
plugins: 'image',
menubar: 'insert',
toolbar: 'image',
image_list: [
    {title: 'My image 1', value: 'https://www.example.com/my1.gif'},
    {title: 'My image 2', value: 'http://www.moxiecode.com/my2.gif'}
]

6. charmap - Insert special characters in editor.

7. print - Print the content in editor.

8. preview - Shows pop-up of current content in read-only format.

9. anchor - Inserts anchor/bookmarks.

10. searchreplace - Find and Replace.

11. visualblocks - Allows user to see block level elements such as a para.

12. code - Allows user to edit the HTML code. 

13. fullscreen - Zoom up to the whole-screen.

14. insertdatetime - Inserts current date/time.

15. media - Add HTML5 audio/video elements.

16. table - Table editing features.

17. paste - This plugin filters/cleanups content pasted from Word. (Upgrade to PowerPaste?) 

18. help - Shows help dialog.

19. wordcount - Show word count in status bar.    
