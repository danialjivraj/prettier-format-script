# prettier-format-script
This script uses Prettier to format every file within a specified root folder, with the option to exclude specific files and folders from being formatted. <br>
When executed, the script provides feedback through the terminal, including information about which files are being formatted and any issues encountered during the process.<br>

Prettier will format the following languages:<br>
![image](https://github.com/user-attachments/assets/789a3b96-4018-4121-af93-6518d7740c0f)


## Preview
![image](https://github.com/user-attachments/assets/16c93cd2-2da8-4553-a053-78145f1082e5)

*using a root folder name the script can't find:*
![image](https://github.com/user-attachments/assets/69c29f73-364c-46c8-8dd1-c5f514430271)

## Dependencies
To use the script, add the following to your `package.json`: 
```
  "type": "module",
  "devDependencies": {
    "prettier": "2.8.8"
  }
```

Then, run the following command to install Prettier:
```
npm install 
```

## Running the Script
To run the script, use the command:
```
node .\format.js
```

**Note:** Make sure you're running the script from the correct directory where `format.js` is located.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[Node.js](https://nodejs.org/en/download) is being used to run the command.
