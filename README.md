# PrependText2File

## Alfred 2 workflow for prepending text to a file

## Contact
Script & terrible placeholder icon by:  
Chad Stovern  
<help@chadstovern.com>  
<http://www.digitalnomad.im>

## Script Logic
- Creates a to the second timestamped backup under /tmp
- Verifies the backup is good via md5 matching before proceeding
- Overwrites the original file with the input you provide
- Appends the contents of the backup to the original — thus giving you prepend behavior!  =)

## Installation Instructions

- double click the workflow file to install
- edit the keyword input to your liking
- edit the embedded bash script line that defines your target text file to prepend to (NO RELATIVE PATHS); look for this section:

	#############################
	## SET YOUR TEXT FILE HERE ##
	#############################
	original="/Users/username/Dropbox/yourfile.txt"

### Optional Notification Support

- if you'd like desktop notifications install terminal-notifier here: https://github.com/alloy/terminal-notifier/downloads ***NOT*** the ruby gem install

## Usage

- activate alfred and type in your keyword
- after your keyword type the exact text you want to prepend to your file
- press enter to prepend

## Pro Tips

- install the plugin more than once and choose a different keyword to create shortcuts to prepend to multiple files
- change the name of the workflow AND the keyword title for each file you install it for

example keywords:  ppideas ppprojects ppblog
