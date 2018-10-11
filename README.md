# Install Python on CoreOS
Python on CoreOS. works well with ansible.

This script install Active Python 3.6 x86_64 binary to CoreOS.


INSTALL
=======

```
wget -qO- https://raw.githubusercontent.com/opiumozor/Install-Python-on-CoreOs/master/install-python.sh | sudo bash
```

RUNNING
=======

/opt/bin/python will works well.

if you want to run python in anywhere, just make ~/.bashrc file which contains this.
```
export PATH=$PATH:/opt/bin
```

or just run this command
```
cat > ~/.bashrc << EOF
export PATH=\$PATH:/opt/bin
EOF
```
