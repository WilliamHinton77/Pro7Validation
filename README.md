# Pro7Validation
Validation setup for Pro7
Pro7Validation is used to validate files in the ThisWeek directory (Files that are only needed for this week).
It does the following validations:
⦁	Check for .pro files in the ThisWeek directory, they should not be in this directory.
⦁	Check Calendar for todays entries, for example: we expect a 10:55 entry, warn if there is an entry during the service time.
⦁	Check for .proBundle files in the ThisWeek directory, do they have a corresponding .pro file in one of the libraries.
⦁	Check for .pptx files in the ThisWeek directory, do they have a corresponding .pro in a library or an mp4 or directory in the ThisWeek directory
⦁	Check for stray files (pptx or proBundle) in the ThisWeek subdirectories
Some of the options can overridden thru the command line or the cfg file.
From a command prompt run the following command to see the current values and possible options:
Pro7Validation -i -h
