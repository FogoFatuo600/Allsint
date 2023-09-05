# Commands #
## Search data
```
- Name        Search by real names
- Nickname    Search by nicknames
- Email       Search by email
- Number      Search by numbers
- Img         Search by Image
```
### Name
Search by real name, and get the data involving this name.
#### How to use
```
allsint -name <Name>
```
### Nickname
Search by nicknames, and get the data involving this nickname.
#### How to use
```
allsint -nickname <Nickname>
```
### Email
Search by email, and get data involving this email.
#### How to use
```
allsint -email <email@example.com>
```
### Number
Search by number, and get data involving this number.
#### How to use
```
allsint -number <+1 408 000 0000>
```
### Img
Search by image, and get data involving this image.
#### How to use
```
allsint -img <dir/example/img.jpg>
```
## Configure output data
```
- Confile    Configure files
- Confdir    Configure directory
```
### Confile
Configure the files that will save the collected data.
#### How to use
Set which file extension will save the data
```
allsint -confile -t <YourFileExtension>
```
Set which file will save text data
```
allsint -confile -t <YourFileExtension>
```
Set how the data will be saved inside the file
```
allsint -confile -s <dir/example/text.json>
```
### Confdir
Configure the directories where the files will be saved.
#### How to use
Set where the files will be saved
```
allsint -confdir -s <dir/example/text.json>
```
Set a specific file to be saved
```
allsint -confdir -f <dir/example>
```
## Others configures
```
- proxy        Set proxy
```
### Proxy
Set a proxy for data searches
#### How to use 
```
allsint -proxy <dir/example/proxy.txt>
```
