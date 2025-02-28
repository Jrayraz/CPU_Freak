# CPU_Freak
CPU Core control GUI 

# Simply edit the Exec and Icon sections found in the desktop file to replace /path/to/cpufreak to the directory of cpu_freak.py and then make it executable and move to /.local/share/applications to put it in your launcher. 

# Dependencies
sudo apt-get install cpufrequtils pipenv -y || true

# Move to CPU Freaks root directory and run following command to initate the GUI
cd /path/of/cpufreak
pipenv install
pipenv run pip install tk psutil Pillow
pipenv run python3 cpu_freak.py
