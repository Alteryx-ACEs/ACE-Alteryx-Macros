# ACE-Alteryx-Macros
Alteryx macros built by Alteryx ACEs. This initial repository will act more like a macro folder to map in Designer. Later, we can assemble an ACE macro pack with an installer.


## Contributing macros

1. [Fork this project][fork] to your account.
2. Make your changes to your fork. If you're new to Github, [Github Desktop][gd] makes it easy to create and sync changes. You'll want to [clone][clone gd] your fork to access it from your local device. 
   Please limit your changes to modification of one macro per pull request. Adding multiple new files at once is fine.
3. [Send a pull request][pr] from your fork to the `main` branch.
4. Remember to [sync your fork][sync] periodically to access the latest macro updates.

Using the web-based interface to make changes is fine too, and will help you
by automatically forking the project and prompting to send a pull request too.

[fork]: https://help.github.com/articles/fork-a-repo/
[branch]: https://help.github.com/articles/creating-and-deleting-branches-within-your-repository
[pr]: https://help.github.com/articles/using-pull-requests/
[sync]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork
[gd]: https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/overview/getting-started-with-github-desktop
[clone gd]: https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/adding-and-cloning-repositories/cloning-and-forking-repositories-from-github-desktop


## Workflow guidelines

- Please use underscores in your filename.
- Please make sure your macros are well-documented. 
- Please provide a description in workflow metadata. 
- For any internal supporting macros, please preface the filename with the parent macro's name. That way, they will alphabetically appear next to each other. Change the file extension to ``.yxmcsupporting`` or ``.yxmcbatch``
- The current .gitignore ignores ``.yxdb`` files. If your macro truly needs a ``.yxdb`` file, you can update the .gitignore in your fork.


Please feel free to suggest other changes for contribution, documentation, and more. This is all a first draft.
