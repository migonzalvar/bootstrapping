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

    gem install --user-install sass


    sudo dnf copr enable carlwgeorge/ripgrep
    sudo dnf install ripgrep

Gestión de multiples versiones
==============================

Usar pyenv, nodenv y phpenv.

Fuentes
=======

Para IDE: `Fira Code <https://github.com/tonsky/FiraCode>`_

Para terminal: `Inconsolata <http://www.levien.com/type/myfonts/inconsolata.html>`_


Funciones
=========

.. code::

    function killport() {
        lsof -i tcp:"$@" | awk 'NR!=1 {print $2}' | xargs kill ;
    }

    function whiteboard () {
        convert $1 -morphology Convolve DoG:15,100,0 -negate -normalize -blur 0x1 -channel RBG -level 60%,91%,0.1 $2
    }


IntelliJ
========

Para resolver el problema de cierre de *pop ups* en modo **sloppy focus**:

  1. In IntelliJ open settings Registry (Ctrl+Shift+A and look for "Registry...")
  2. Find "allow.dialog.based.popups" and disable it

Gestión de memoria
==================

- earlyoom

Otro software externo
=====================

- Fortinetclient
