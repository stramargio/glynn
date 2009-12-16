Glynn
=====

Glynn offers you a bin to easily send a jekyll powered blog to your host through FTP.

Installation
------------

Glynn comes as a gem. It has no dependencies other than the ruby default libraries.
Install it with gem install.

    gem install glynn --source http://gemcutter.org

That's it ! You now have the Glynn executable on your machine.
Go to your jekyll project, configure the host and distant directory where the files will be sent.
For example, this is my _config.yml file :

    markdown: rdiscount
    pygments: true
    auto: true
    ftp_host: dmathieu.com
    ftp_dir: /web/portfolio

Glynn will connect itself to the host "dmathieu.com" and send every file to the FTP directory /web/portfolio.

Contributing
------------

If you think Glynn is great but can be improved, feel free to contribute.
To do so, you can :

* [Fork](http://help.github.com/forking/) the project
* Do your changes and commit them to your repository
* Test your changes. We won't accept any untested contributions (except if they're not testable).
* Create an [issue](http://github.com/dmathieu/glynn/issues) with a link to your commits.

And that's it! I'll soon take a look at your issue and review your changes.

Author
------------------

Damien MATHIEU :: 42 (AT|CHEZ) dmathieu.com
