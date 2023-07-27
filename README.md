## AutoFileOrganizer 🗂️<hr>

- This script automatically sorts files into designated directories based on file types, extensions, or other criteria.

## Requirements:
- Python installed

## Usage:
- Clone the repository: 
```
git clone https://github.com/K-Honsu/AutoFileOrganizer.git
```
- cd into directory

- Activate the virtual environment for your project. If you don't have a virtual environment set up, you can create one using the venv module by running the following command:

```
python -m venv myvenv
```

- This will create a new virtual environment in a directory named myvenv.

- Activate the virtual environment by running the following command:

```
source myvenv/bin/activate
```

- Note: If you're on Windows, the command to activate the virtual environment will be slightly different. You can use the following command instead:

```
myvenv\Scripts\activate
```

- Install dependencies: 
```
pip install -r requirements.txt
```

- Run the script: 
```
python automate-directory.py
```


- Congratulations, you have now successfully automated your directory!

## To run the script continuously<hr>
- To ensure that your Python automation script runs continuously, here are a few options to achieve this

1. Run the Script in a Terminal Session (Foreground)
- Open a terminal session and run the Python script manually. The script will continue running in the foreground until you stop it by pressing Ctrl+C. While this method is simple, it requires you to keep the terminal window open, and the script will stop if the terminal session is closed.

2. Run the Script in a Terminal Session (Background)
- ou can run the script in the background by appending an ampersand & at the end of the command. For example:
```
python automate-directory.py &
```
- This will allow the script to run in the background, and you can continue using the terminal for other tasks. However, the script will still stop if you close the terminal session.

3. Use a Cloud Server or Virtual Machine:
- If you want the script to run continuously even when your laptop is powered off, you can consider deploying the script on a cloud server or a virtual machine. Cloud providers like AWS, Google Cloud, or DigitalOcean offer virtual machines that can run your script 24/7.