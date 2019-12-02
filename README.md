
# eligible.sh

A neat Bash script to build and install Enlightenment 23 on **Ubuntu Bionic Beaver**.

## Get started

Make sure that the `git` package is installed, then clone this repository (as normal user)*

```bash
git clone https://github.com/batden/eligible.git .eligible
```

That creates a new [hidden folder](https://itsfoss.com/hide-folders-and-show-hidden-files-in-ubuntu-beginner-trick/) named _".eligible"_ in your home directory.

Please copy the file _"eligible.sh"_ from this new folder to the download folder.

Now change to the download folder and make the script executable*

```bash
chmod +x eligible.sh
```

Then issue the following command*

```bash
./eligible.sh
```

On subsequent runs, open Terminal and simply type*

```bash
eligible.sh
```

(Use tab completion: Just type _elig_ and press Tab)

### Update local repository

Be sure to check for updates at least once a week.

In order to do this, change to ~/.eligible and run*

```bash
git pull
```

That's it.

_(*) As normal user == as currently logged in user, do not prepend sudo to the command._

Mind the cows! :cow2: :cow2: :cow2:
