# prettier-format-script
This script uses Prettier to format every file within a specified root folder, with the option to exclude specific files and folders from being formatted. <br>
When executed, the script provides feedback through the terminal, including information about which files are being formatted and any issues encountered during the process.

## Preview
![image](https://github.com/user-attachments/assets/16c93cd2-2da8-4553-a053-78145f1082e5)

*using a root folder name the script can't find:*
![image](https://github.com/user-attachments/assets/639fd900-d289-4c23-a5e3-ef3f08aab442)




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

**Note:** Make sure you're running the script from the correct directory where `format.js` is located.
