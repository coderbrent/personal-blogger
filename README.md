# personal-blogger
a blogging tool I am building that I will incorporate as a feature into my personally branded website to showcase my abilities as a developer.

# Project Name: Personal Blog

Due Date: Open Ended (Personal Project)

Objective: Create a blogging application that can be accessed from an administrative “editor” panel that allows the writer to create an article, submit and store it to firebase so that it persists after a session is finished on my personal developer site.

# Dependencies: 

    Front End
* Bootstrap v4 (page layout/responsive structure)
* Moment.js (time stamping for blogs)
* FontAwesome (ui/ux icons)
* Google Fonts (typography)
* Materialize

    Back End
* Firebase (data storage for blog entries and user accounts)


Layout sketches are available in my Evernote account.

# Administrative Panel Features

* Blog title input (1 line text input) -> takes and stores an ID blogTitle into Firebase as a "blog title" collection
* Blog editor field (multiple field text input) -> takes and stores an ID blogArticle into Firebase as a "blog article" collection
* Save button -> only saves the blog to firebase... does not publish it (aka display it on the view page).
* Submission button -> pushes the contained text from the blog fields into firebase.
* Edit Past Blogs -> lists a collection of past blogs, which when moused over, asks the user if they'd like to "edit this blog?". If user clicks the blog, user will be prompted that not saving the existing blog (if there is one started) may cause it to be deleted. proceed anyway? (if yes, display the selected blog in the editor, else, return back and allow the user to "save" the blog.

# Challenges
