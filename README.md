# [Mautic](https://www.mautic.org/) Pull Request Tester

Mautic Pull Request Tester is an app, which will let you test simple pull requests from the [GitHub](https://www.github.com/mautic/mautic/pulls/) repository for Mautic.  

## How to use it

1. Download this repo, or copy the contents of the `tester.php` file into a new file.
2. Unzip downloaded package somewhere on your computer.
3. Upload the unzipped tester.php to the folder on your server where your existing Mautic instance is installed.
4. Go to the URL where your Mautic runs and add `/tester.php` behind the last slash. Example: `https://www.mautic.myweb.com/tester.php`.

Require `git` installed on your server, but not a git repository (https://gist.github.com/derhuerst/1b15ff4652a867391f03)

#### Applying a PR
1. Add a PR to your Mautic instance by entering the number for a pull request.
2. Click Apply PR. 

#### Removing a PR
1. Remove a PR from your Mautic instance by entering the same number you applied previously.
2. Click Remove PR.


*Example:*
`3343` will test https://www.github.com/mautic/mautic/pull/3343

#### Do not use in production environment.

