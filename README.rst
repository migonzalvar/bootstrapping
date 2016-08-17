
Falta por incluir:

.. code::

    sudo dnf install http://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm http://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm
    sudo dnf install dropbox
    sudo dnf install keepassx
    sudo dnf config-manager --add-repo=http://negativo17.org/repos/fedora-spotify.repo
    sudo dnf install spotify-client
    python3.5 -m pip install --user dotfiles
    python3.5 -m pip install --user --upgrade pip
    python3.5 -m pip install --user --upgrade wheel setuptools
    sudo dnf install zsh
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
    python3 -m pip install --user checkoutmanager
    sudo dnf install hg
    python2.7 -m pip install --user virtualenvwrapper
    sudo dnf install tmux
    sudo dnf install vim
    sudo dnf install ansible
    sudo dnf install python2-dnf
