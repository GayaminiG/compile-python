# compile-python

# complie python from scratch in virtul env
'sudo apt-get install build-essential gdb lcov libbz2-dev libffi-dev libgdbm-dev liblzma-dev libncurses5-dev libreadline-dev libsqlite3-dev libssl-dev tk-dev uuid-dev zlib1g-dev'

# import python

'wget https://www.python.org/ftp/python/3.13.2/Python-3.13.2.tgz'

# unzip

'wget https://www.python.org/ftp/python/3.13.2/Python-3.13.2.tgz'


# using all core that we have
make -j 4

# new python
alias python="/usr/local/bin/python3.13"

# source venv 
source ~/.venv/bin/activate