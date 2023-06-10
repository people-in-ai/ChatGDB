# Install Anaconda
bash Anaconda3-2023.03-1-Linux-x86_64.sh 
```
PREFIX=/home/pai/anaconda3
Unpacking payload ...
                                                                                                     
Installing base environment...


Downloading and Extracting Packages


Downloading and Extracting Packages

Preparing transaction: done
Executing transaction: \ 

    Installed package of scikit-learn can be accelerated using scikit-learn-intelex.
    More details are available here: https://intel.github.io/scikit-learn-intelex

    For example:

        $ conda install scikit-learn-intelex
        $ python -m sklearnex my_application.py

    

done
installation finished.
Do you wish the installer to initialize Anaconda3
by running conda init? [yes|no]
[no] >>> yes
no change     /home/pai/anaconda3/condabin/conda
no change     /home/pai/anaconda3/bin/conda
no change     /home/pai/anaconda3/bin/conda-env
no change     /home/pai/anaconda3/bin/activate
no change     /home/pai/anaconda3/bin/deactivate
no change     /home/pai/anaconda3/etc/profile.d/conda.sh
no change     /home/pai/anaconda3/etc/fish/conf.d/conda.fish
no change     /home/pai/anaconda3/shell/condabin/Conda.psm1
no change     /home/pai/anaconda3/shell/condabin/conda-hook.ps1
no change     /home/pai/anaconda3/lib/python3.10/site-packages/xontrib/conda.xsh
no change     /home/pai/anaconda3/etc/profile.d/conda.csh
modified      /home/pai/.bashrc

==> For changes to take effect, close and re-open your current shell. <==

If you'd prefer that conda's base environment not be activated on startup, 
   set the auto_activate_base parameter to false: 

conda config --set auto_activate_base false

Thank you for installing Anaconda3!
```

# Setup Conda Environment

conda create -n py310 python=3.10

conda activate py310

# Install VS Code

sudo snap install code --classic
