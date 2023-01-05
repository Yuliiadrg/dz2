
User@DESKTOP-G9EJUC9 MINGW64 ~/OneDrive/Рабочий стол
$ git config --global user.name “YuliiaDr”

User@DESKTOP-G9EJUC9 MINGW64 ~/OneDrive/Рабочий стол
$ git config --global user.name
“YuliiaDr”

User@DESKTOP-G9EJUC9 MINGW64 ~/OneDrive/Рабочий стол
$ git config --global user.email yudragomaretskaya@email.com

User@DESKTOP-G9EJUC9 MINGW64 ~/OneDrive/Рабочий стол
$ git config --global user.email
yudragomaretskaya@email.com

User@DESKTOP-G9EJUC9 MINGW64 ~/OneDrive/Рабочий стол
$ cd D:/

User@DESKTOP-G9EJUC9 MINGW64 /d
$ ls
'$RECYCLE.BIN'/                   Merchant-Of-Mars.jpg          msdownld.tmp/
'CV Yuliia Dragomaretskaya.pdf'   Photoshoots/                  programms/
 Downloads/                      'Smart Goals.pdf'              web/
'English for me'/                'System Volume Information'/   Фотоальбом/
 HEALTH/                         'University CHNU'/

User@DESKTOP-G9EJUC9 MINGW64 /d
$ cd web/

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ ls
 Airbnb.xml  'Sublime Text 3'/  'WebStorm 2021.1.2'/   fonts/
 Git/         Tag/               beetrootAcademy/      images/

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cd beetrootAcademy/

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ git clone https://github.com/Yuliiadrg/dz2.git
Cloning into 'dz2'...
warning: You appear to have cloned an empty repository.

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ git commit -m "CloneInMyRepo"
fatal: not a git repository (or any of the parent directories): .git

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ ls
dz1/  dz2/  dz3/  projectTest/

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cd dz2

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ touch app/{style.css,script.js,index.html}
touch: cannot touch 'app/style.css': No such file or directory
touch: cannot touch 'app/script.js': No such file or directory
touch: cannot touch 'app/index.html': No such file or directory

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ ls

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ touch index.html

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ ls
index.html

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ touch style.css

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ touch script.js

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ mkdir pages

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ mkdir fonts

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ mkdir images

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ ls
fonts/  images/  index.html  pages/  script.js  style.css

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ cd ../

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ ls
dz1/  dz2/  dz3/  projectTest/

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cd../
bash: cd../: No such file or directory

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cd ../

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ ls
 Airbnb.xml     LONDON-EYE.jpg     Tag/
 Git/           Open_Sans.zip     'WebStorm 2021.1.2'/
 IMG_9734.JPG  'Sublime Text 3'/   beetrootAcademy/

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cp LONDON-EYE.jpg dz2/images
cp: cannot create regular file 'dz2/images': No such file or directory

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cp LONDON-EYE.jpg dz2/images/beetrootAcademy
cp: cannot create regular file 'dz2/images/beetrootAcademy': No such file or directory

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ ls
 Airbnb.xml     'Sublime Text 3'/      beetrootAcademy/
 Git/            Tag/                  kiev.JPG
 Open_Sans.zip  'WebStorm 2021.1.2'/   london.jpg

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cp london.jpg beetrootAcademy/

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cp kiev.JPG beetrootAcademy/dz
dz1/ dz2/ dz3/

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cp kiev.JPG beetrootAcademy/dz2/images

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ ls
 Airbnb.xml     'Sublime Text 3'/      beetrootAcademy/
 Git/            Tag/                  kiev.JPG
 Open_Sans.zip  'WebStorm 2021.1.2'/   london.jpg

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cd beetrootAcademy/

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ ls
dz1/  dz2/  dz3/  london.jpg  projectTest/

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cp london.jpg dz2/images

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cd ../

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ ls
 Airbnb.xml     'Sublime Text 3'/      beetrootAcademy/
 Git/            Tag/                  kiev.JPG
 Open_Sans.zip  'WebStorm 2021.1.2'/   london.jpg

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cp Open_Sans.zip beetrootAcademy/dz2/fonts

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cd beetrootAcademy

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cd ../

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ ls
 Airbnb.xml      Philosopher.zip   'WebStorm 2021.1.2'/   london.jpg
 Git/           'Sublime Text 3'/   beetrootAcademy/
 Open_Sans.zip   Tag/               kiev.JPG

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cp Philosopher.zip beetrootAcademy/dz2/fonts

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cd beetrootAcademy/

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ ls
dz1/  dz2/  dz3/  london.jpg  projectTest/

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cd dz2

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ ls
fonts/  images/  index.html  pages/  script.js  style.css

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ git add .

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   fonts/Open_Sans.zip
        new file:   fonts/Philosopher.zip
        new file:   images/kiev.JPG
        new file:   images/london.jpg
        new file:   index.html
        new file:   script.js
        new file:   style.css


User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ cd ../

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cd dz2

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ git commit -m "addAllFilesWithoutOneMoreFont"
[main (root-commit) 8350f0b] addAllFilesWithoutOneMoreFont
 7 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fonts/Open_Sans.zip
 create mode 100644 fonts/Philosopher.zip
 create mode 100644 images/kiev.JPG
 create mode 100644 images/london.jpg
 create mode 100644 index.html
 create mode 100644 script.js
 create mode 100644 style.css

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ cd ../

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy
$ cd ../

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ ls
 Airbnb.xml       Open_Sans.zip      Tag/                  kiev.JPG
 Git/             Philosopher.zip   'WebStorm 2021.1.2'/   london.jpg
 Montserrat.zip  'Sublime Text 3'/   beetrootAcademy/

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cp Montserrat.zip beetrootAcademy/dz2/fonts/

User@DESKTOP-G9EJUC9 MINGW64 /d/web
$ cd beetrootAcademy/dz2

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ cd fonts/

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2/fonts (main)
$ ls
Montserrat.zip  Open_Sans.zip  Philosopher.zip

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2/fonts (main)
$ cd ../

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ ls
fonts/  images/  index.html  pages/  script.js  style.css

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ git add .

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ git status
On branch main
Your branch is based on 'origin/main', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   fonts/Montserrat.zip


User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ git commit -m "implementationAllFiles"
[main 59dd11c] implementationAllFiles
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 fonts/Montserrat.zip

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ git push origin main
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (13/13), 8.68 MiB | 160.00 KiB/s, done.
Total 13 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Yuliiadrg/dz2.git
 * [new branch]      main -> main

User@DESKTOP-G9EJUC9 MINGW64 /d/web/beetrootAcademy/dz2 (main)
$ history
    1  CV cd..
    2  BeetrootAcademy/CV cd...
    3  git cofig --global user.name "username"
    4  git config --global user.name "YuliiaDr"
    5  git congig --global user.email yudragomaretskaya@gmail.com
    6  git --help
    7  c
    8  git config --global user.name
    9  git config --global user.email
   10  git config --global user.email yudragomaretskaya@gmail.com
   11  git config --global user.email
   12  git config --global user.name "Yuliia"
   13  git config --global user.name
   14  ls
   15  ls
   16  cd ./
   17  cd ../
   18  ls
   19  ls
   20  cd ./
   21  cd ../
   22  ls
   23  cd Документы/
   24  ls
   25  mkdir projects
   26  ls
   27  cd projects/
   28  ls
   29  git -v
   30  ls
   31  git clone https://github.com/Yuliiadrg/testRepo.git
   32  ls
   33  cd testRepo/
   34  ls
   35  cd -
   36  ls
   37  cd d:/
   38  ls
   39  cd WEB/
   40  ls
   41  cd Beetroot/
   42  ls
   43  ls
   44  mkdir projectTest
   45  ls
   46  cd projectTest/
   47  git clone  https://github.com/Yuliiadrg/testRepo.git
   48  ls
   49  cd testRepo/
   50  git add .
   51  history
   52  ls
   53  cd :/D
   54  LS
   55  ls
   56  cd../
   57  ls
   58  ls
   59  cd Этот\ компьютер.lnk
   60  ls
   61  ls
   62  cd Documents.lnk
   63  ls
   64  git config --global user.name "YuliiaDr"
   65  git config --global user.name
   66  git config --global user.email "yudragomaretskaya@gmail.com"
   67  git config --global user.email
   68  ls
   69  cd d:/
   70  ls
   71  cd web/
   72  ls
   73  cd beetrootAcademy/
   74  ls
   75  mkdir dz2
   76  cd dz2
   77  git config --global user.name “YuliiaDr”
   78  git config --global user.name
   79  git config --global user.email yudragomaretskaya@email.com
   80  git config --global user.email
   81  cd D:/
   82  ls
   83  cd web/
   84  ls
   85  cd beetrootAcademy/
   86  git clone https://github.com/Yuliiadrg/dz2.git
   87  git commit -m "CloneInMyRepo"
   88  ls
   89  cd dz2
   90  touch app/{style.css,script.js,index.html}
   91  ls
   92  touch index.html
   93  ls
   94  touch style.css
   95  touch script.js
   96  mkdir pages
   97  mkdir fonts
   98  mkdir images
   99  ls
  100  cd ../
  101  ls
  102  cd../
  103  cd ../
  104  ls
  105  cp LONDON-EYE.jpg dz2/images
  106  cp LONDON-EYE.jpg dz2/images/beetrootAcademy
  107  ls
  108  cp london.jpg beetrootAcademy/
  109  cp kiev.JPG beetrootAcademy/dz2/images
  110  ls
  111  cd beetrootAcademy/
  112  ls
  113  cp london.jpg dz2/images
  114  cd ../
  115  ls
  116  cp Open_Sans.zip beetrootAcademy/dz2/fonts
  117  cd beetrootAcademy
  118  cd ../
  119  ls
  120  cp Philosopher.zip beetrootAcademy/dz2/fonts
  121  cd beetrootAcademy/
  122  ls
  123  cd dz2
  124  ls
  125  git add .
  126  git status
  127  cd ../
  128  cd dz2
  129  git commit -m "addAllFilesWithoutOneMoreFont"
  130  cd ../
  131  cd ../
  132  ls
  133  cp Montserrat.zip beetrootAcademy/dz2/fonts/
  134  cd beetrootAcademy/dz2
  135  cd fonts/
  136  ls
  137  cd ../
  138  ls
  139  git add .
  140  git status
  141  git commit -m "implementationAllFiles"
  142  git push origin main
  143  history
