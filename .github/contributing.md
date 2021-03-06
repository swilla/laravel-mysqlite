# Contributors
Help is always welcome!

# Found a Bug?
If you find a bug in the source code, you can help us by submitting an [issue][issue]. Even better, you can submit a Pull Request  with a fix.

# Need a Feature?
If you'd like a feature added, submit an [issue][issue] and add the **enhancement** label.  If you have already coded the feature, please still submit the issue, but feel free submit a pull request with the solution.  For standards see the Committing Pull Requests section of this document.

# Want to contribute with code?
Feel free to pick up any of the unassigned outstanding [issues][issue] and work them.  When you're finished, create a pull request and github will give you credit on our [contributors][contributors] page.

# Committing Pull Requests
In order to contribute fork the repository as your own, work on it, and create a pull request to reincorporate to the master branch.
All Pull Requests must meet these requirements before being considered for merge:
1. Tests must pass
    - ./vendor/phpunit/phpunit/phpunit
1. Details of the feature / fix this PR addresses
1. Reference issues addressed by PR. 
1. If resolving an issue, Tag commits with issue number: `git commit -m "#N add a README file to the project."`
1. Include steps to test changes
1. Verify test coverage does not drop below the threshold on master as reported by [coveralls][coveralls]

[github]: https://github.com/spam-n-eggs/laravel-mysqlite
[issue]: https://github.com/spam-n-eggs/laravel-mysqlite/issues
[contributors]: https://github.com/spam-n-eggs/laravel-mysqlite/graphs/contributors
[coveralls]: https://coveralls.io/github/spam-n-eggs/laravel-mysqlite?branch=master
