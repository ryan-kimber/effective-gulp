Effective Gulp Seed
===================

This project is intended to demonstrate a strategy for managing complexity in projects that are built with or use Gulp.js.

When Gulp.js was first becoming popular, it was such a vast improvement over the Grunt build system that many web projects were using that it seems few teams gave much thought to how they could organize their gulp tasks to handle the growing number of things they'd be trying to accomplish inside of their build process (like deployment, for example). 

This seed project demonstrates how gulp-tasks can be relatively easily broken out into separate, modular files, while maintaining interdependencies and improving the supportability of your build process. For kicks, we've also included loading build variables and properties from a local .json file, so that builds can be customized easily, without having to wade into the gulp scripts themselves. This also allows the project to be committed to a repository, while keeping usernames and passwords, or things like AWS keys and secrets out of the repository.


