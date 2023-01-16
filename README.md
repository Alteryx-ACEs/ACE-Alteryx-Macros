# ACE-Alteryx-Macros
Alteryx macros built by Alteryx ACEs. This initial repository will act more like a macro folder to map in Designer. Later, we can assemble an ACE macro pack with an installer.


## Contributing macros

1. [Fork this project][fork] to your account.
2. [Create a branch][branch] for the change you intend to make.
3. Make your changes to your fork. Please limit your changes to one macro modification per pull request. Adding multiple new files at once is fine.
4. [Send a pull request][pr] from your fork’s branch to our `main` branch.

Using the web-based interface to make changes is fine too, and will help you
by automatically forking the project and prompting to send a pull request too.

[fork]: https://help.github.com/articles/fork-a-repo/
[branch]: https://help.github.com/articles/creating-and-deleting-branches-within-your-repository
[pr]: https://help.github.com/articles/using-pull-requests/


## Workflow guidelines

- Please use underscores in your filename.
- Please make sure your macros are well-documented. 
- Please provide a description in workflow metadata. 
- For any internal supporting macros, please preface the filename with the parent macro's name. That way, they will alphabetically appear next to each other. Change the file extension to ``.yxmcsupporting`` or ``.yxmcbatch``
- The current .gitignore ignores ``.yxdb`` files. If your macro truly needs a ``.yxdb`` file, you can update the .gitignore in your fork.


Please feel free to suggest other changes for contribution, documentation, and more. This is all a first draft.
