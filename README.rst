=============
Bootstrapping
=============

Manualmente:

- Claves ssh
- Configuración ssh

Falta por incluir:

.. code::

    sudo dnf install keepassx

    sudo dnf config-manager --add-repo=http://negativo17.org/repos/fedora-spotify.repo
    sudo dnf install spotify-client

    python3.5 -m pip install --user dotfiles
    git clone git@bitbucket.org:migonzalvar/Dotfiles.git

    python3.5 -m pip install --user --upgrade pip
    python3.5 -m pip install --user --upgrade wheel setuptools
    python2.7 -m pip install --user virtualenvwrapper

    sudo dnf install zsh
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

    python3 -m pip install --user checkoutmanager

    curl --silent --location https://rpm.nodesource.com/setup_6.x | bash -
