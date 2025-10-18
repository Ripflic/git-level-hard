# <img src="https://gitlab.com/An.On/Install_script/-/blob/main/img/shell-script.png" alt="Script" width="64" height="64" /> Install Script for LINUX

> This project is not actively maintained anymore. New maintainers are welcome.
> 
>  -- Daniele


#### What is it?

Notepadqq is a text editor designed by developers, for developers. 

# <img src="https://gitlab.com/An.On/Install_script/-/blob/main/img/img_01.png" alt="Script" width="757" height="564" />



Добавляйте и меняйте на свои
-----

| Список скриптов       |
|-----------------------|
| update system         |
| delete programm       |
| install code editor   |
| install design        |
| install appimage      |
| install video editor  |
| install jack          |

#### Get the source

    $ git clone --recursive https://github.com/notepadqq/notepadqq.git
    $ cd notepadqq

#### Build

    notepadqq$ ./configure --prefix /usr
    notepadqq$ make

If you encounter errors make sure to have the necessary libraries installed. For Ubuntu you can do that using apt-get:

    sudo apt-get install qttools5-dev-tools qtwebengine5-dev libqt5websockets5-dev libqt5svg5 libqt5svg5-dev libuchardet-dev pkg-config

For CentOS:

    sudo yum install -y qt5-qtbase-devel qt5-qttools-devel qt5-qtwebengine-devel qt5-qtwebsockets-devel qt5-qtsvg-devel uchardet qt5-qtwebchannel-devel pkgconfig

