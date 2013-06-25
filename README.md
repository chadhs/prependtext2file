# PrependText2File
## Alfred 2 workflow for prepending text to a file

## Contact: chadhs@digitalnomad.im
## Credits: script & terrible placeholder icon by Chad Stovern

## Installation Instructions

- double click the workflow file to install
- edit the keyword input to your liking
- edit the embedded bash script line that defines your target text file to append to (NO RELATIVE PATHS); look for this section:

#############################
## SET YOUR TEXT FILE HERE ##
#############################
original="/Users/username/Dropbox/yourfile.txt"

### Optional Notification Support

- if you'd like desktop notifications install terminal-notifier here: https://github.com/alloy/terminal-notifier/downloads ***NOT*** the ruby gem install

## Usage

- activate alfred and type in your keyword
- after your keyword type the exact text you want to append to your file
- press enter to append

## Protips

- install the plugin more than once and choose a different keyword to create shortcuts to append to multiple files

example keywords:  ppideas ppprojects ppblog
