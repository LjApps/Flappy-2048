## Contributing
changes and improvements are more than welcome!
feel free to fork and open a pull request..

follow the house rules to have a bigger chance of
your contribution being merged :)

## House rules
based on rules from the original 2048 repository,<br />
except that changes in `master` is merged with `gh-pages`<br />
so any change in either original branch are blended in the<br />
derivative AuthenticFlappy-2048 `gh-pages` branch..
### How to make changes
Please make your changes in a specifically made branch and request to pull on `gh-pages`

 - To make changes, create a new branch based on `gh-pages`.
 If you can, please make sure the game fully works before sending the PR,
 as that will help speed up the process.
 - If you want to pull changes from UPSTREAM 2048 (original)
 get the new files / fresh changes from `master`
 (do not pull changes from upstream 2048 `gh-pages` unless strictly necessary),
 then create a Pull Request to the branch: AuthenticFlappy-2048 `gh-pages`.<br />
 `gh-pages` is different from master in that it contains sharing features, analytics and other things that have no direct bearing with the game. `master` is the "pure" version of the game in UPSTREAM 2048 (original).
 - If you want to modify the CSS, please edit the SCSS files present in `style/`: `main.scss` and others. Don't edit the `main.css`, because it's supposed to be generated.  
 In order to compile your SCSS modifications, you need to use the `sass` gem (install it by running `gem install sass` once Ruby is installed).  
 To run SASS, simply use the following command:  
 `sass --watch style/main.scss`  
 SASS will automatically recompile your css when changed.
 - `Rakefile`�contains some tasks that help during development. Feel free to add useful tasks if needed.
 - Please use 2-space indentation when editing the JavaScript. A `.jshintrc` file is present, which will help your code to follow the guidelines if you install and run `jshint`.
 - Please test your modification thouroughly before submitting your Pull Request.

### Changes that are welcome
 - Bug fixes
 - Compatibility improvements
 - "Under the hood" enhancements
 - Small changes that don't have an impact on the core gameplay

### Changes that might not be accepted
We have to be conservative with the core game. This means that some modifications won't be merged, or will have to be evaluated carefully before being merged:

 - Undo/redo features
 - Save/reload features
 - Changes to how the tiles look or their contents
 - Changes to the layout
 - Changes to the grid size
