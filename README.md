# bookmarks
collect all bookmarks and interesting links

### RxJS
* [Docs](http://reactivex.io/rxjs/)
* [Marble Diagrams](http://rxmarbles.com/)
* [Marble Tests](https://github.com/ReactiveX/rxjs/blob/master/doc/writing-marble-tests.md)

### React/ReactNative
* [You Might Not Need Redux](https://medium.com/@dan_abramov/you-might-not-need-redux-be46360cf367)
* [A maintainable project structure for React/Redux](https://hackernoon.com/my-journey-toward-a-maintainable-project-structure-for-react-redux-b05dfd999b5)
* [React State vs. Redux State: When and Why?](https://spin.atomicobject.com/2017/06/07/react-state-vs-redux-state/)


### Github
 * [Markdown-Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) 
 * reset everything locally `git reset  --hard <last good SHA>`
 * `git add .` then `git commit -m  "my commit message"` and `git push`
 * `git config --global url."https://".insteadOf git://`
 
 * Undo the commit but keep all changes staged => `git reset --soft HEAD~;`
 * Undo the commit and unstage the changes => `git reset HEAD~;`
 * Undo the commit and lose all changes => `git reset --hard HEAD~;`
 
 To cherry-pick all the commits from commit A to commit B (where A is older than B), run:
 * `git cherry-pick A^..B`
 
 If you want to ignore A itself, run:
 * `git cherry-pick A..B`

Delete tag:
`git push --delete origin v1.0`


### Useful commands
 * update oh-my-zsh: ```source ~/.zshrc```
 * mssing id: `ssh-add ~/.ssh/id_rsa `
 
### Angular
 * CLI downgrade: 
 ```
 npm uninstall -g @angular/cli
 npm install -g @angular/cli@1.7.4 
 ```
 
 ### Python
 `python -m SimpleHTTPServer 4200`
 
 ### Python3
 `python3 -m http.server 4200`
 
 
