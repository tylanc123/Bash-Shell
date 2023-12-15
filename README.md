# File Permissions in Bash Shell


## Project Description

The research team within our organization encountered issues with file permissions within the project directory, necessitating adjustments to ensure appropriate authorization levels. The objective was to enhance system security by aligning permissions accurately.

## Actions Taken

### Check File and Directory Details
![Check file and directory details](https://github.com/tylanc123/Bash-Shell/assets/153654738/54ebf1eb-761a-4f85-ad65-9e8d4e1691b7)

#### Describe Permissions String

File name: `project_k.txt`  
- User: Read, Write  
- Group: Read, Write  
- Other: Read, Write
  
![Describe the permissions string](https://github.com/tylanc123/Bash-Shell/assets/153654738/c02d8eb3-be71-40dc-b1cc-f08b019e342f)

### Change File Permissions

File: `project_k.txt`  
- Removed write permissions for other

![Change file permissions](https://github.com/tylanc123/Bash-Shell/assets/153654738/35b4f909-21e5-4923-a20c-08e432bc606c)
  

### Change File Permissions on a Hidden File

Hidden File: `project_x.txt`  
- Removed write permissions from user and group  
- Added Read permissions to "group"

![Change file permissions on a hidden file](https://github.com/tylanc123/Bash-Shell/assets/153654738/f7967532-9117-4075-8290-724bc1892874)




### Change Directory Permissions

- Removed execute permissions from the "drafts" directory

![Change directory permissions](https://github.com/tylanc123/Bash-Shell/assets/153654738/08f529c6-4295-4ef8-b51e-c5e3f6b95c2c)

## Summary

To achieve the desired authorization levels, the following actions were taken:

1. **Checking Permissions**: Utilized `ls -la` command to inspect current permissions.
2. **File Permissions Modification**: Employed `chmod` command to adjust file permissions.
3. **Directory Permissions Alteration**: Utilized `chmod` to modify directory permissions, removing execute permissions where necessary.

























