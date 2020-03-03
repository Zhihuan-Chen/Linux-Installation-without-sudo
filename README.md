# Linux-Installation-without-sudo
This is a guide on how to install softwares in a server without sudo permit 
1. Install python<br/>
  step 1<br/>
  create a folder under your user directory $mkdir $HOME/python<br/>
  step 2<br/>
  change directory to the created file ($cd $HOME/python) and download python tgz file from http://www.python.org/ftp/python/3.7.6/Python-3.7.6.tgz (example version 3.7.6) using $wget https://www.python.org/ftp/python/3.5.1/Python-3.5.1.tgz<br/>
  step 3<br/>
  extract using $tar xf Python-3.7.6.tgz and $cd Python-3.7.6<br/>
  step 4<br/>
  tell the system where you want to install $./configure --prefix=/some/other/directory<br/>
  step 5 <br/>
  $make then $make install  <br/>
  step 6 <br/>
  add environment path $PATH="$HOME/mydir/bin:$PATH" (example you have install in mydir folder) then $export PATH
