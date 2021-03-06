Setting up Your Development Environment
=======================================

Let's get the hands dirty by doing some setup. We will explain what you have done later. Just feel free to try it out for now :)

Download and Install Virtual Box and Ubuntu Linux
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Download and install `Virtual Box <https://www.virtualbox.org/>`_.
#. Download and add `Ubuntu 64 Bit Virtual Box image <http://www.osboxes.org/ubuntu/>`_ into your Virtual Box. Latest version is recommended. Please refer to the web site for user name and password.

Install Kivy, Git, and PIP
~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Start the Ubuntu. Input the username and password obtained in the last step to login. Right click desktop and choose open terminal.
#. In the terminal, run the following command:

.. code::

  sudo apt-get upgrade
  sudo apt-get install python-kivy
  sudo apt-get install git
  sudo apt-get install python-pip

Intall Pycharm IDE
~~~~~~~~~~~~~~~~~~

#. In your Ubuntu. Open Firefox. And download `Pycharm Commnity Edition for Linux <https://www.jetbrains.com/pycharm/download/#section=linux>`_
#. By default, it would be saved at ~/Downloads.
#. Open terminal again. Type the following:

.. code::

  cd ~/Downloads
  tar xvzf pycharm*.tar.gz
  rm pycharm*.tar.gz
  mv pycharm* ~/pycharm

Running PyCharm
~~~~~~~~~~~~~~~

#. Open terminal.
#. Run Pycharm in terminal by:

.. code::

  ~/pycharm/bin/pycharm.sh

If PyCharm asked for Key binding / mappings, choose Eclipse for the sake of this course.

In the next section. You will learn about what you have just setup.
