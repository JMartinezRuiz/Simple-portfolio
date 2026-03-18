cd /ruta/a/Python-3.12.13
ls -la
ls -l configure
chmod +x configure
./configure --prefix=$HOME/python3.12
make -j$(nproc)
make altinstall
$HOME/python3.12/bin/python3.12 --version
$HOME/python3.12/bin/python3.12 -c "import ssl, bz2, lzma, sqlite3, ctypes; print('ok')"
$HOME/python3.12/bin/pip3.12 --version
echo 'export PATH=$HOME/python3.12/bin:$PATH' >> ~/.bashrc
source ~/.bashrc
python3.12 --version
pip3.12 --version



cd /ruta/a/Python-3.12.13

ls -la

ls -l configure

chmod +x configure

./configure --prefix=$HOME/python3.12

make -j$(nproc)

make altinstall

$HOME/python3.12/bin/python3.12 --version

$HOME/python3.12/bin/python3.12 -c "import ssl, bz2, lzma, sqlite3, ctypes; print('ok')"

$HOME/python3.12/bin/pip3.12 --version

$HOME/python3.12/bin/python3.12 -m ensurepip --upgrade

$HOME/python3.12/bin/python3.12 -m pip --version

echo 'export PATH=$HOME/python3.12/bin:$PATH' >> ~/.bashrc

source ~/.bashrc

which python3.12

python3.12 --version

pip3.12 --version
