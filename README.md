# srishrishti
Sri Shrishti Infotech Company Website

Link to development site https://sriram-kannan.github.io/srishrishti/

# Bootstrap UI Framework Installation (Version Bootstrap v4.0.0)

Mandatory: (bootstrap.css and bootstrap.js files)
1. Goto https://getbootstrap.com/ and click "Download". Goto "Compiled CSS and JS" and click "Download". Extract zip file into local directory.
2. Delete all files in css folder except bootstrap.css (use this during development for debugging as this is more readable instead of bootstrap.min.css which is compressed version to save space).
3. Delete all files in js folder except bootstrap.js (use this during development for debugging as this is more readable instead of bootstrap.min.js which is compressed version to save space). Delete zip file.

Optional: (jquery.js, popper.js (added tooltip function) and fonts.css files)
1. Goto jquery.com and click download jquery. Save link of uncompressed development slim build to local js folder (use this during development for debugging as this is more readable instead of compressed production slim build which is compressed version to save space).
2. Goto popper.js.org and click "Github" which will take you to their github repository. Save link of unpkg popper.js to local js folder (use this during development for debugging as this is more readable/editable instead of unpkg popper.min.js which is compressed version to save space).
3. Goto https://getbootstrap.com/ and click "Documentation". Search for "tooltip". Copy the function and paste to the end of popper.js file.
 4. Goto bootstrapcdn.com and click on "Font Awesome" in top menu section. Copy the link and open the file in a browser. Select all and save as fonts.css in local css folder.
 5. Search for "fonts awesome for bootstrap github" and goto their github repository. Download zip file to local and extract all files. Copy font folder to project and delete other files.

Include above css and js files in html file as needed (Tooltips rely on the 3rd party library Popper.js for positioning. You must include popper.js before bootstrap.js).
