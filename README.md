# my_alias
my alias config
```
#system personalise
alias droot="cd ~/../.."
alias cls="clear"
alias dir="ls -alF"
alias update="sudo apt-get update"
alias upgrade="sudo apt-get upgrade"
alias etchosts="sudo nano /etc/hosts"
alias hibernate="sudo systemctl hibernate"
alias rmrf="rm -rf "

#laravel and php
alias laravel="~/.config/composer/vendor/bin/laravel"
alias pas="php artisan serve"
alias pa="php artisan "
alias pclear="php artisan cache:clear && php artisan config:clear && php artisan route:clear"
alias pcache="php artisan route:cache && php artisan config:cache"
alias c="composer"
alias cu="composer update"
alias cr="composer require"
alias ci="composer install"
alias cda="composer dump-autoload"


#net tools
# IP addresses
alias whatsmyip="curl https://diagnostic.opendns.com/myip ; echo"
alias ipshow="ip addr show"

#network
alias restartnet="sudo service network-manager restart"

#kerio vpn
alias kerioconfig='sudo dpkg-reconfigure kerio-control-vpnclient'
alias kerioreload='sudo /etc/init.d/kerio-kvc reload'
alias keriorestart='sudo /etc/init.d/kerio-kvc restart'
alias keriostart='sudo /etc/init.d/kerio-kvc start'
alias keriostop='sudo /etc/init.d/kerio-kvc stop'

#SYSTEM VPN
alias vpnstart="nmcli con up "
alias vpnstop="nmcli con down "
alias vpnlist="nmcli con | grep -i vpn"


```
