# Dlib Compiled Wheels for Python 3.7, 3.8, 3.9 (Windows 10 x64)

After spending a lot of time searching for precompiled Dlib binaries, I decided to compile them myself for Python 3.7, 3.8, and 3.9 on Windows 10 (x64). Follow the instructions below to install the necessary Dlib version.

## Instructions

1. **Download the .whl file you need** from this repository.

2. **Copy the downloaded file** into the root folder of your Python distribution.

3. **Open a command prompt** in your root Python folder. For example:
   ```bash
   cd C:\python37
   ```

4. **Install Dlib using pip** by running the appropriate command for your Python version:

   ### Python 3.7:
   ```bash
   python -m pip install dlib-19.22.99-cp37-cp37-win_amd64.whl
   ```

   ### Python 3.8:
   ```bash
   python -m pip install dlib-19.22.99-cp38-cp38-win_amd64.whl
   ```

   ### Python 3.9:
   ```bash
   python -m pip install dlib-19.22.99-cp39-cp39-win_amd64.whl
   ```

And that's it! Dlib should now be installed and ready to use.
