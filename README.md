# project_index
    -   [2021](#section)
        -   [Applescript](#applescript)
        -   [CGI](#cgi)
        -   [Chrome Extension](#chrome-extension)
        -   [Coagulate TK](#coagulate-tk)
        -   [ffplay](#ffplay)
        -   [Greasemonkey](#greasemonkey)
        -   [Linux kernel buildroot](#linux-kernel-buildroot)
        -   [Pandoc](#pandoc)
        -   [R](#r)
        -   [WebGL](#webgl)
        -   [XEmacs](#xemacs)
## 2021

### Applescript
    vi ~/computers.git/mac/bin/osascript_javascript_mail.sh

### CGI
    cd /usr/lib/cgi-bin
    vi find.sh

### Chrome Extension
    cd /Volumes/git/github/chrome_extension/close_yurled/
    vi alarm.js
    vi content.js

### Coagulate TK
    cd /media/sarnobat/unmirrored/src.git/tcltk/coagulate_tk
    vi coagulate.videos.tk

### ffplay
    vi ~/bin/ffplay_atletico_unathorized.sh

### Greasemonkey
    cd /Volumes/git/src.git/javascript/greasemonkey_tampermonkey_userscripts
    vi mailboxforwarding.user.js

### Linux kernel buildroot
    cd /media/sarnobat/unmirrored/trash/buildroot-2021.12/docker-buildroot

### Pandoc

    cd ~/sarnobat.git/www/portraits/handbook/
    images/rohidekar_handbook/ -type f \
        | sort  \
        | perl -pe 's{^(.*)}{<img src="$1"><br>}g' \
        | tee index_auto.html  \
        | pandoc --from html --to latex \
        | tee ~/sarnobat.git/tex/rohidekar_handbook_auto.tex

### R
    cd /Volumes/git/src.git/r/11_mint_spending_csv
    vi aggregate.r
    
    vi ~/bin/csvsql_example.sh
    cat ~/sarnobat.git/HSBC/full_history_from_mint/2021-10_all_transactions_since_beginning.csv  | head | csvsql --query "select [Date],[Description],[Amount] from stdin"

### WebGL
    cd ~/src.git/javascript/webgl/helloworld

### XEmacs
    vi /home/sarnobat/computers.git/antec/.xemacs

