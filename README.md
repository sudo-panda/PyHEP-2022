# PyHEP-2022 - Using C++ From Numba, Fast and Automatic

## Setup

To setup this notebook:

1) Create a virtual environment
	```bash
	python3 -m venv .venv
	. .venv/bin/activate
	```

2) Install requirements:
	```bash
	pip install -r requirements.txt
	```
	
3) Install ROOT with PyHEP branch:
	```bash
	git clone -b pyhep --single-branch --depth=1 https://github.com/sudo-panda/root.git
	mkdir builddir installdir
	cd builddir
	cmake -DCMAKE_INSTALL_PREFIX=../installdir ../root
	cmake --build . --target install
	cd ..
	source installdir/bin/thisroot.sh
	```
	
4) Done! You can now run the examples in the notebook.
	
	
