## о чем надо говорить на git-туториале

* git clone --bare
* git rebase -i
* git add -p
* git status | grep deleted | awk '{print $3}' | xargs git rm -f
* git read-tree
* git cherry-pick
* git config --global push.default tracking
* git bisect
* `(git diff; git diff --cached) | vim -` и git commit -v

### best practices

* если проект большой и в 1 репе N компонентов -- то в одной ветке нельзя работать над 2+ компонентами
* git clone --bare + много чекаутов для разных веток —-- лучше чем git stash
* нельзя использовать git add . или -[Aa] :)
* `.gitignore` для платформы
* в фич-ветке история коммитов может отличаться до мержа
* git submodules — говно
* gitflow — не говно, рассказать про стратегии бранчевания

### git + java

* ant -- не серьёзно
* maven
* sbt / scala -- TODO
* leiningen / clojure
* submodules

### git vs cvs/svn

* децентрализованность
* у гита нет частичных чекаутов
* мерж - это не больно, а очень даже приятно

### ништяки

* https://github.com/robbyrussell/oh-my-zsh
