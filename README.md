# Odoo-Config-Win
Set of files necessary to run and execute Odoo via debugging and python virtual envs in Visual Studio Code with Windows.

My apologies, this guide is not for Psycharm yet, some tinkering around for an afternoon might do it.

How to get Odoo:
Odoo can be cloned via git scm package to virtually every location of your harddrive.
1. Grab a copy of git scm here:https://git-scm.com/ and install the package for your OS.
2. Get Microsoft Visual Studio Code here: https://code.visualstudio.com/ for your dediacated platform.
3. For Odoo 13, only python over version 3.6 and higher is supported. Get your copy here: www.python.org (good to run 3.7.5 under Windows
4. Open CMD and navigate to cozy location on your HDD and exeute git clone https://github.com/odoo/odoo.git --depth 1 --branch 13.0
5. If you have access to enterprise, create another folder with the name enterprise aside your Odoo installation and clone the enterprise repository into it.

Get Odoo to run:
1. Clone the files from this repository into the folder around the installation folder "Odoo". If you copied Odoo into a folder called C:\odoo-dev\13.0, your installationfolder would be in C:\odoo-dev\13.0\odoo. In this case, please copy the set of files into 13.0 to avoid an overwrite during a fetch operation. Please execute git clone https://github.com/Odoo-Config-Win. Please change the the name of the vscode folder into .vscode, as vscode saves settings there, like where to create a Virtual Env.
2. Save the entire working folder 13.0 as a workspace in Vscode.
3. Try

(T2B)
