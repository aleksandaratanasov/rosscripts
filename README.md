# rosscripts
Contains various useful scripts that are to be used with the Robot Operating System (www.ros.org)

 * Use the command **chmod u+x SCRIPT_FILE** to grant execution rights to the user (a+x can also be applied if you want to grant this right to all users)
 * Add path to script (in my case I store my scripts inside **/home/$USER/scripts/**) to the PATH environment variable in your **.bashrc** by doing **export PATH=$PATH:PATH_TO_SCRIPTS**.

For now following scripts are available and more will be added in the future:
 * rosgoto - this scripts combines the **rospack find** command along with **cd** in order to change to a given package's directory if package exists
