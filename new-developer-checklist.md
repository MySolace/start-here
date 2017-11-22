
## Gmail

If you don't already have one, create a Gmail (Google) Account

> https://accounts.google.com/signup

### Why?

Your email address says a lot about you.
read: http://theoatmeal.com/comics/email_address
or http://www.telegraph.co.uk/technology/news/10605176/What-does-your-email-address-say-about-you.html

Gmail is the best ("free") email service (we are aware of).
They take security seriously and have *many* great features
(like search, filters and threaded messages).

### Tip for Choosing a Gmail Address
Hundreds of millions of people have gmail accounts
(most simply to use the Google/Android Play Store)
as a result it can be hard to get your name as your gmail address.
e.g. Andrew.Smith@gmail.com is taken. So, consider adding an initial

Make sure you use a ***strong*** password. If someone can guess (or "crack")
your password they will gain access to *everything* else. not good... :hankey:


## Twitter

~~While~~ having a twitter account is ~~not~~ essential, it helps you
to stay up to date with news/updates in your chosen field. https://twitter.com/

Even if you don't become a Twitter "Power User", its good to follow
what's going on in your the world of web/app development.

### Chosing a good Twitter "Handle"

> "All of the *good* names are taken..."

Not true.

Sure, *many* short, single word or personal names are taken,
but there are still *plenty* of two-word or "_invented_" names
you can pick from. *Get creative* with keeping your handle as short as possible.
while making it easy to remember/type.

### Follow

Decide what you want to be good at (_known for_) and _follow_ all
the people who are already doing (_good_) work in that area.

Follow people you know in "real world" so you can keep in touch.

### Favourite :heart:

*Favourite* the tweets you find useful/interesting/insightful/informative,
this serves multiple purposes:  
(a) bookmark content so you can return to it later.  
(b) the author of the tweet/content knows it was useful so they will make more!
(c) your followers can see what you find like-worthy.

### Re-Tweet :recycle:

If you think a post someone has shared is good re-tweet it!
This has *many* positive effects:  
(a) the person who posted the content will
get *positive reenforcement* (*i.e. they will make more content*),
(b) the content author might follow you back (*if they don't already*)  
(c) if you consistently re-tweet useful content you will become known
for relevance in that area and more people will follow/re-tweet you!

[![dan_abramov_retweeted](https://cloud.githubusercontent.com/assets/194400/12523324/0ee0ac2c-c14e-11e5-9e6c-de4717fa474c.png)](https://twitter.com/dwylhq/status/687703493264732160)

> https://twitter.com/dwylhq/status/687703493264732160

<br />

## GitHub

Github.com is where people share the projects/code they are working on,
discover what others are building and collaborate on cool things!

There are other _alternatives_ for sharing code in a team,
but GitHub has become the gathering place for the Open Source community.

### Register

If you don't already have a GitHub account, [get one today](https://github.com/dwyl/github-reference#how-to-sign-up)!
(_try and match the username to the one you picked on Twitter for consistency_)

> https://github.com/

### Complete Your Profile

Add some detail to your profile so you are less "_generic_".

Especially the new "bio" section which lets you link
to various places and add a bit of text describing yourself.

#### Gravatar

GitHub (and other services) use Gravatar to manage your **avatar image**.

> https://gravatar.com

### Follow People!

If you find someone _interesting_ on GitHub, follow them!

> You can spot a non-coder (*or ex-coder*) a mile away by how _few_
people they follow on GitHub.

### Star Projects!

Star the repositories (project) you find _interesting/promising_,
both so you can return to them later and to _encourage_ the
authors to _continue_ in their quest!

### Contribute!

The easiest way to contribute to a project/repository is to read through
the documentation (`README.md`) and if you _spot an improvement_, _**create an issue**_!


### Set Up SSH Keys for GitHub

ssh-keygen -t rsa -C "edwardcodes@gmail.com"

#### New to Command Line?

Do not be intimidated by the command line.
Asking a computer to perform tasks by typing words instead of
clicking on buttons.  
If you are *completely* new to using the Command Line <br /> watch:
https://www.youtube.com/watch?v=KP0b0iaZiWk (Git For The Intimidated) <br />
and: https://www.youtube.com/watch?v=U8GBXvdmHT4 (The Basics of Git and GitHub)

#### Never used Terminal before?

Learn how to use the **Terminal**:

> [Build Podcast - Terminal](http://vimeo.com/43649618)

Learn more about Unix (the Operating System of *most* Servers)
read: http://www.unixmages.com/ufbm.pdf

## StackOverflow / StackExchange

StackOverflow is where technology people ask & answer questions.
Create an account and explore.

> https://stackoverflow.com/users/signup

Once you have registered, try _answering_ people's questions:
http://stackoverflow.com/?tab=interesting

When you get stuck on _anything_

_Asking_ and _Answering_ questions on StackOverflow is an _easy_
way of demonstrating your knowledge.

> If you have trouble getting your first few points on "SO", don't worry
you aren't alone, get in touch and we will give you some pointers.  
See: https://medium.com/@johnslegers/the-decline-of-stack-overflow-7cb69faa575d


<br />

# *Optional* (*Recommended*)

## Trello

Even though we use GitHub to manage our issue backlog, Trello is widely used by developers.
It is one of the easiest, most versatile (and "**free**") project/task
tracking tools. Take the tour, register and try it!

Use your Google account to sign up.

> https://trello.com/tour

## Linux

Most people use Windows but every developer should know how to use a **Linux OS**. There are dozens of Linux versions but the most suggested for beginners is _Ubuntu._ It's free and open source.
>https://www.ubuntu.com

## Quora

More *subjective* (opinion-based) than StackOverflow, Quora lets
you ask *specific* people in the industry a question.

Again, use your gmail to register/sign-in

> http://www.quora.com/


## JQuery

While we don't tend to use JQuery for *new* projects @dwyl
(see: http://youmightnotneedjquery.com ),
JQuery is still used on 65% of websites, so if you ever have
to work on an _existing_ project, you will almost _inevitably_
come across it.
JavaScript & jQuery Tutorial for Beginners:
https://youtu.be/VRnQOcVclS8


## Developer Setup

### Install System Packages

#### Fedora / CentOS 7

* CentOS only - use yum instead of dnf.

* Install Packages

  ```bash
  sudo dnf -y group install "C Development Tools and Libraries"  # For unf Gem and noi4r Gem
  sudo dnf -y install git-all                                    # Git and components
  sudo dnf -y install memcached                                  # Memcached for the session store
  sudo dnf -y install postgresql-devel postgresql-server         # PostgreSQL Database server and to build 'pg' Gem
  sudo dnf -y install bzip2 libffi-devel readline-devel          # For rbenv install 2.3.1 (might not be needed with other Ruby setups)
  sudo dnf -y install libxml2-devel libxslt-devel patch          # For Nokogiri Gem
  sudo dnf -y install sqlite-devel                               # For sqlite3 Gem
  sudo dnf -y install nodejs                                     # For ExecJS Gem, bower, npm, yarn, webpack.. - needs at least 6.0.0
  sudo dnf -y install libcurl-devel                              # For Curb
  rpm -q --whatprovides npm || sudo dnf -y install npm           # For CentOS 7, Fedora 23 and older
  sudo dnf -y install openssl-devel                              # For rubygems
  sudo dnf -y install cmake                                      # For rugged Gem
  sudo dnf -y install openscap                                   # Optional, for openscap Gem for container SSA
  ```

* Enable Memcached

  ```bash
  sudo systemctl enable memcached
  sudo systemctl start memcached
  ```

* Configure PostgreSQL
  * Required PostgreSQL version is 9.4, 9.5
    * See [here](developer_setup/postgresql_software_collection.md) how to install
      it in Linux distributions like CentOS 7, using _SoftwareCollections.org_.
    * Or follow the directions [here](https://www.postgresql.org/download/linux/redhat/#yum)
      to install it from the PostgreSQL Global Development Group repositories.

  ```bash
  sudo postgresql-setup initdb
  sudo grep -q '^local\s' /var/lib/pgsql/data/pg_hba.conf || echo "local all all trust" | sudo tee -a /var/lib/pgsql/data/pg_hba.conf
  sudo sed -i.bak 's/\(^local\s*\w*\s*\w*\s*\)\(peer$\)/\1trust/' /var/lib/pgsql/data/pg_hba.conf
  sudo systemctl enable postgresql
  sudo systemctl start postgresql
  sudo -u postgres psql -c "CREATE ROLE root SUPERUSER LOGIN PASSWORD 'smartvm'"
  # This command can return with a "could not change directory to" error, but you can ignore it
  ```

#### Ubuntu / Debian

* Install Packages

  ```bash
  sudo apt install git                              # Git and components
  sudo apt install memcached                        # Memcached for the session store
  sudo apt install postgresql libpq-dev             # PostgreSQL Database server and to build 'pg' Gem
  sudo apt install bzip2 libffi-dev libreadline-dev # For rbenv install 2.3.1 (might not be needed with other Ruby setups)
  sudo apt install libxml2-dev libxslt-dev patch    # For Nokogiri Gem
  sudo apt install libsqlite-dev libsqlite3-dev     # For sqlite3 Gem
  sudo apt install nodejs nodejs-legacy npm         # For ExecJS Gem, bower, npm, yarn, webpack.. - needs at least 6.0.0
  sudo apt install g++                              # For unf Gem
  sudo apt install libcurl4-gnutls-dev              # For Curb
  sudo apt install cmake                            # For rugged Gem
  sudo apt install libgit2-dev pkg-config libtool
  sudo apt install libssl-dev                       # for puma < 3.7.0
  ```

  If your node version is less than 6.0 (debian currently has 4), you can either install it from the `experimental` repo:

  ```bash
  echo 'deb http://ftp.debian.org/debian/ experimental main non-free contrib' | sudo tee /etc/apt/sources.list.d/experimental.list
  sudo apt update
  sudo apt install nodejs nodejs-legacy npm
  ```

  Alternatively, you can use [nvm](https://github.com/creationix/nvm) to install a node version locally (similar to `rbenv`).

* Ubuntu fix for failing Bundler

  ```bash
  sudo apt remove libssl-dev
  wget http://ftp.cz.debian.org/debian/pool/main/o/openssl1.0/libssl1.0-dev_1.0.2l-2_amd64.deb
  wget http://ftp.cz.debian.org/debian/pool/main/o/openssl1.0/libssl1.0.2_1.0.2l-2_amd64.deb
  sudo dpkg -i libssl1.0-dev_1.0.2l-2_amd64.deb libssl1.0.2_1.0.2l-2_amd64.deb
  ```

* Enable Memcached

  ```bash
  sudo systemctl enable memcached
  sudo systemctl start memcached
  ```

* Configure PostgreSQL

  ```bash
  sudo grep -q '^local\s' /etc/postgresql/9.5/main/pg_hba.conf || echo "local all all trust" | sudo tee -a /etc/postgresql/9.5/main/pg_hba.conf
  sudo sed -i.bak 's/\(^local\s*\w*\s*\w*\s*\)\(peer$\)/\1trust/' /etc/postgresql/9.5/main/pg_hba.conf
  sudo systemctl restart postgresql
  sudo su postgres -c "psql -c \"CREATE ROLE root SUPERUSER LOGIN PASSWORD 'smartvm'\""
  ```

#### Mac

* Install [Homebrew](http://brew.sh/)

  If you do not have Homebrew installed, go to the Homebrew website and install it.

* Install Packages

  ```bash
  brew install git
  brew install pkg-config
  brew install memcached
  brew install postgresql
  brew install cmake
  brew install node
  brew install yarn
  ```

  If your node version is less than 6, you may need to `brew upgrade node` and `brew link node`.

* Configure and start PostgreSQL
  * Required PostgreSQL version is 9.4, 9.5

  ```bash
  # Enable PostgreSQL on boot
  mkdir -p ~/Library/LaunchAgents
  ln -sfv /usr/local/opt/postgresql/*.plist ~/Library/LaunchAgents
  launchctl load -w ~/Library/LaunchAgents/homebrew.mxcl.postgresql.plist
  # Create the ManageIQ superuser
  psql -d postgres -c "CREATE ROLE root SUPERUSER LOGIN PASSWORD 'smartvm'"
  ```

* Start memcached

  ```bash
  # Enable Memcached on boot
  ln -sfv /usr/local/opt/memcached/homebrew.mxcl.memcached.plist ~/Library/LaunchAgents
  launchctl load -w ~/Library/LaunchAgents/homebrew.mxcl.memcached.plist
  ```

### Install Ruby and Bundler

* Use a Ruby version manager
  * [chruby](https://github.com/postmodern/chruby) and [ruby-install](https://github.com/postmodern/ruby-install)
  * [rvm](http://rvm.io/)
  * [rbenv](https://github.com/rbenv/rbenv)
* Required Minimum Ruby version is 2.3.1+
* Required Minimum Bundler version is 1.8.7+

### Setup Git and Github

* The most reliable authentication mechanism for git uses SSH keys.
  * [SSH Key Setup](https://help.github.com/articles/generating-ssh-keys) Set up a SSH keypair for authentication.  Note: If you enter a passphrase, you will be prompted every time you authenticate with it.
* Github account setup [Account Settings](https://github.com/settings).
  * [Profile](https://github.com/settings/profile): Fill in your personal information, such as your name.
  * [Profile](https://github.com/settings/profile): Optionally set up an avatar at gravatar.com.  When you set up your gravatar, be sure to have an entry for the addresses you plan to use with git / Github.
  * [Emails](https://github.com/settings/emails): Enter your e-mail address and verify it, click the Verify button and follow the instructions.
  * [Notification Center](https://github.com/settings/notifications) / Notification Email / Custom Routing: Change the email address associated with ManageIQ if desired.
  * If you are a member of the ManageIQ organization:
    * Go to [the Members page](https://github.com/ManageIQ?tab=members).
      * Verify you are listed.
      * Optionally click Publicize Membership.
* Fork ManageIQ/manageiq:
  * Go to [ManageIQ/manageiq](https://github.com/ManageIQ/manageiq)
  * Click the Fork button and choose "Fork to \<yourname\>"
* Git configuration and default settings.

  ```bash
  git config --global user.name "Joe Smith"
  git config --global user.email joe.smith@example.com
  git config --global --bool pull.rebase true
  git config --global push.default simple
  ```

  If you need to use git with other email addresses, you can set the local user.email from within the clone using:

  ```bash
  git config user.name "Joe Smith"
  git config user.email joe.smith@example.com
  ```

### Clone the Code

```bash
git clone git@github.com:JoeSmith/manageiq.git # Use "-o my_fork" if you don't want the remote to be named origin
cd manageiq
git remote add upstream git@github.com:ManageIQ/manageiq.git
git fetch upstream
```

You can add other remotes at any time to collaborate with others by running:

```bash
git remote add other_user git@github.com:OtherUser/manageiq.git
git fetch other_user
```

### Javascripty things

  Make sure your node version is at least 6.0.0. If not, you can use [nvm](https://github.com/creationix/nvm) to install a node version locally (similar to `rbenv`).

* Install the _Bower_ package manager

  ```bash
  sudo npm install -g bower
  ```

* Install the _Yarn_ package manager

  Follow [official instructions](https://yarnpkg.com/lang/en/docs/install/#linux-tab) or

  ```bash
  sudo npm install -g yarn
  ```

* Install the _Gulp_ and _Webpack_ build system

  ```bash
  sudo npm install -g gulp-cli
  sudo npm install -g webpack
  ```

### Get the Rails environment up and running

```bash
bin/setup                  # Installs dependencies, config, prepares database, etc
bundle exec rake evm:start # Starts the ManageIQ EVM Application in the background
```

* You can now access the application at `http://localhost:3000`. The default username is `admin` with password `smartvm`.
* There is also a minimal mode available to start the application with fewer services and workers for faster startup or
targeted end-user testing. See the [minimal mode guide](developer_setup/minimal_mode.md) for details.
* As an alternative to minimal mode, individual workers can also be started using [Foreman](https://ddollar.github.io/foreman/)
  * See the [Foreman guide](developer_setup/foreman.md) for details.
* To run the test suites, see [the guide on that topic](developer_setup/running_test_suites.md).

### Update dependencies and migrate db

* You can update ruby and javascript dependencies as well as run migrations using one command

```bash
bin/update                # Updates dependencies using bundler and bower, runs migrations, prepares test db.
```

For provider, UI or other plugin development, see [the guide on that topic](developer_setup/plugins.md).

#### Some troubleshooting notes

* First login fails

Make sure you have memcached running. If not stop the server with `bundle exec rake evm:stop`,
start memcached and retry.

* `bin/setup fails` while trying to load the gem 'sprockets/es6'

If this happens check the log for
`ExecJS::RuntimeUnavailable: Could not find a JavaScript runtime` a few lines down.
When this message is present, then the you need to install `node.js` and re-try

* `bin/setup` fails while trying to install the 'nokogiri' gem

If this happens, you may be missing developer tools in your OS X. Try to install them with
`xcode-select --install` and re-try.

* `bin/setup` fails to install the 'sys-proctable' gem, or installs the wrong version.

If this happens it may be a Bundler issue. Try running `bundle config specific_platform true`
and re-try.

* Can't install any gems during bundle install

```
# install all dependencies to a local path
bundle install --path vendor/bundle
```

* Can't install `nokogiri-1.7.2` on a Mac

```
# install dependencies
brew install pkgconfig
brew install libxml2

# test the gem can be compiled with the right libxml2
export PKG_CONFIG_PATH=/usr/local/opt/libxml2/lib/pkgconfig
gem install nokogiri -v 1.7.2 -- --use-system-libraries

# configure bundle to do so
bundle config build.nokogiri --use-system-libraries --with-xml2-include=$(brew --prefix libxml2)/include/libxml2
```

* Can't install `sys-proctable` on a Mac - a package missing even after bundle install succeeded

```
bundle config specific_platform true
bundle install
```

* If everything is hosed after an OSX upgrade

Install xcode developer tools

```xcode-select --install```

Uninstall existing ruby version with your version manager
Reinstall rubies with version manager
