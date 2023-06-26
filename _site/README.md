# coastsincrisis.github.io
This is the site repository for _Coasts in Crisis_, a digital art exhibit that features pieces produced during the 2017 hurricane season in the Caribbean islands of St. Croix, the Florida Keys, and Puerto Rico.

It's currently under production. We're migrating the project from Drupal 9, still reachable at coastsincrisis.net.

# BACKUP 2
2023-06-25. This is the backup made after finding the solution to the live reload issue. I'll work with this file structure from now on and it will replace the previous one. Now, the site lives in the main directory, which will also be the git repo's root. 

### issues
1. `--livereload` 2023-06-25. There's something in my computer that's not allowing the plugin to work. I tried editing the _config.yml, the gemfile, reinstalling ruby in a conda environment, as well as jekyll and other gem files. Several attempts at troubleshooting why the auto regeneration wasn't working also proved unsuccessful, but using `--force_polling` instead.
