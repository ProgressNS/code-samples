# Contributing a NativeScript Code Sample

Interested in contributing your own sample app? Awesome! 👍

Before you submit anything, here are some guidelines we'd like you to follow:

 - [Code of Conduct](#coc)
 - [Signing the CLA](#cla)
 - [Submission Guidelines](#submit)

## <a name="coc"></a> Code of Conduct

Please be aware of, and follow, our official [Code of Conduct](https://github.com/NativeScript/codeofconduct).

## <a name="cla"></a> Signing the CLA

Please sign our [Contributor License Agreement][http://www.nativescript.org/cla] (CLA) before sending pull requests. For any code changes to be accepted, the CLA must be signed. It's easy, we promise! 😀

## <a name="submit"></a> Submission Guidelines

// TODO: append some Playground-specific guidelines in here!!!

Before you submit your pull request consider the following guidelines:

* Please sign our [Contributor License Agreement (CLA)](http://www.nativescript.org/cla) before sending pull requests. We cannot accept code without this. 🙀 
* Make your changes in a new git branch:

     ```shell
     git checkout -b my-fix-branch master
     ```

* Create your patch
* Avoid checking in files that shouldn't be tracked (e.g `node_modules`, `platforms`, or compiled .ipa/.apk binaries). We recommend using a [gitignore](https://help.github.com/articles/ignoring-files/) for this.
* Commit your changes using a descriptive commit message.

     ```shell
     git commit -a
     ```
  Note: the optional commit `-a` command line option will automatically "add" and "rm" edited files.

* Push your branch to GitHub:

    ```shell
    git push origin my-fix-branch
    ```

* In GitHub, send a pull request to `code-samples:master`.

That's it! Thank you for your contribution! 🤗

### After Pull Request is Merged

After your pull request is merged, you can safely delete your branch and pull the changes from the main (upstream) repository:

* Delete the remote branch on GitHub either through the GitHub web UI or your local shell as follows:

    ```shell
    git push origin --delete my-fix-branch
    ```

* Check out the master branch:

    ```shell
    git checkout master -f
    ```

* Delete the local branch:

    ```shell
    git branch -D my-fix-branch
    ```

* Update your master with the latest upstream version:

    ```shell
    git pull --ff upstream master
    ```