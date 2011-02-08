!SLIDE bullets incremental
# Let's get started #

* Bookmark me: [http://cheat.errtheblog.com/s/git](http://cheat.errtheblog.com/s/git)
* Print me: [http://bit.ly/id98qP](http://bit.ly/id98qP)

!SLIDE commandline
# Introduce yourself to Git #
    $ git config --global user.name "George Bashi"
    $ git config --global user.email "jamil@georgebashi.com"

!SLIDE bullets smaller
# Grab a repo to play with #
* `git clone https://github.com/georgebashi/git-workshop.git`
* ![url](url.png)

!SLIDE commandline incremental

    $ git clone https://github.com/georgebashi/git-workshop.git
    Cloning into git-workshop...
    remote: Counting objects: 19, done.
    remote: Compressing objects: 100% (17/17), done.
    remote: Total 19 (delta 5), reused 0 (delta 0)
    Unpacking objects: 100% (19/19), done.
    
    $ cd git-workshop
    
    $ ls
    Gemfile      README.md    config.ru    get-started  what
    Gemfile.lock about-me     differences  showoff.json why
    
    $ gem install bundler --no-rdoc --no-ri
    Successfully installed bundler-1.0.10
    1 gem installed
    
    $ bundle install
    Using bluecloth (2.0.10)
    ...
    ...
    Your bundle is complete! ...
    
    # edit away!
