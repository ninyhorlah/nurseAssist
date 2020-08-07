# Nurse Assist Project

Please read all instructions carefully as pull requests will be carefully accessed before being merged

### Folder Structure

The project consists of the main pages and also an asset folder at the root directory. 

In the assets folder, we have an images folder where all images should be sent to, there is a js folder containing js files for each page, there is also a fonts folder which contains our custom fonts and most importantly, we have a
SASS folder and a CSS folder. All files in the SASS folder compiles to one single minified css file which is located inside the CSS folder and all the scss file should go into the PAGES folder. The CSS folder and it's content SHOULD NEVER be touched or edited. 

Also, the following settings must be done

1. Download "Live sass compiler" vs code extension and activate it if you have not.
2. Go to your vs code settings -> Extensions -> Live sass compiler
3. Then under the heading "Live sass compile Config" you'll see an underlined option "Edit in settings.json", click it.
4. At the very bottom, you should see a set of setting like

    {
        formats: "compressed",
        extension name: ".min.css",
        savepath: "assets/css"
    }
  ],
  liveSassCompile.settings.generateMap: false,
  liveSassCompile.settings.autoprefix: []  

  please make sure your own settings are the exact same thing before doing anything.
5. Save these settings and then at the bottom of VS Code, you'll see an option called 'watch sass', click i and your sass ll be automatically compiled into our general css file while your write.

### Contribution guide

1. Fork the repository
2. Clone and then open it up on your code editor
3. Open terminal and set upsream branch: ```git remote add upstream https://github.com/Nurse-Assist/nurseAssist-project.git```
4. Pull upstream ```git pull upstream develop```
5. Create a new branch for the task your are doing eg: ```git checkout -b home-page```
6. After making changes, do ```git add .```
7. Commit your changes with a descriptive commit message```git commit -m "commit message"```
8. To make sure there are no conflicts: ```git pull upstream develop```
9. Push changes to your new branch: ```git push origin your-current-branch-name```
10. Create a pull request to the develop branch