Get PyInstaller working with Dropbox Python SDK
===============================================

1. Download and install Python (tested with python 2.7)
2. Enable python PATH component during python installation
3. Open command line (cmd.exe)
4. Install dropbox sdk with: pip install dropbox
5. Install pyinstaller (tested on PyInstaller 3.2.1) with: pip install pyinstaller
6. Create executable with: pyinstaller dropbox_client.py
7. Check subfolder dist/dropbox_client for result (that folder will be renamed sync and used by innosetup)
