# bashrc

# proxy environment variables:
export HTTP_PROXY="http://user:password@proxy:port"
export HTTPS_PROXY="http://user:password@proxy:port"
export http_proxy="http://user:password@proxy:port"
export https_proxy="http://user:password@proxy:port"

export PATH=$PATH:~/bin/

# modify prompt:
PS1='\[\e[1;34m\]\W \[\e[0;31m\]\$\[\e[1;32m\] '
trap 'printf "\e[0m" "$_"' DEBUG
