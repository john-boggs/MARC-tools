# MARC-tools

ripmarc: Converts a MARC file to human-readable (and easily editable)
         text format. Because this text format uses a vertical bar as the
         subfield delimiter, vertical bars in the record are represented
         by {vbar}. Records begin with LDR and end with EOR. Works as a
         pipe

mendmarc: Converts a ripmarc-format text file and converts it to true
          MARC. Works as a pipe

countmarc: Counts the number of records in a MARC file.

splitmarc: Splits a MARC file into multiple files with a uniform
           number of MARC records in each file. The command splitmarc
           with no parameters returns a usage message.
