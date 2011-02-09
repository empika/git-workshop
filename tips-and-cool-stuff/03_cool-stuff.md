!SLIDE bullets incremental
# Cool stuff #
* Heroku: git-powered hosting ([http://heroku.com](http://heroku.com))
* Gollum: git-backed wiki ([https://github.com/github/gollum](https://github.com/github/gollum))
* Post-Receive Hooks: make clever things happen when you push
* `git log --graph --all --oneline`

!SLIDE code smaller
    * 36c17a5 source reshaped a bit to play well with a bgsaving thread, still work to do, does not compile.
    *   cb9b35c Merge branch 'unstable' of github.com:antirez/redis-private into unstable
    |\  
    | * 249ad25 BGSAVE work in progress
    | *   5133510 Merge remote branch 'pietern/writev-unstable' into unstable
    | |\  
    | | * 9b1d738 Remove newlines for networking errors
    | | * a2b33f2 Remove glueoutputbuf from redis.conf
    | | * a510cb0 Remove glueoutputbuf option and broken code
    * | | 4489860 TODO updated
    |/ /  
    * | f771dc2 IO performances greatly improved under high writes load
    |/  
    *   6eaad66 Merge branch 'master' into unstable
    |\  
    | *   04a2ade Merge remote branch 'pietern/bench-fix'
    | |\  
    | * | 8ce3926 Fix compiler warnings on Solaris
    | * | 8919161 limits.h is already included from redis.h
    | * | 65b472a Solaris 10 doesn't know AF_LOCAL
    | * | ba55932 Solaris doesn't support -rdynamic
    | * | a1e97d6 Update hiredis to 0.9.2
