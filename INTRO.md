# Structure of UNIX 

user{
    shell{
        utility{
            kernal{
                hrdware{

                }
            }
        }
    }
}

# commands
* pwd : present working dir 
* mkdir : create directory
* ls : 
* cd : 
* cal : current calander 
* echo : print the content after echo 
* vi <filename> : opens the file in the vim editor 
* cc <filename> : to compile the file 
* ./a.out : to run the file 

# attributes 
* -a : all
* ls -l : permissions granted (read/write/exe) with time and other details 

# vi editor 
* :q - to exit 
* :wq - to save and exit
* echo "to print"

# cat 
* cat > <filename>
enter the data
ctrl + d to save and exit

# AWK script

* awk '{print}' <filename>  : prints all data from filename
* awk '/<fieldname>/{print}' <filename> : prints only the line from the file whos  /fieldname/ is specified
* awk 'BEGIN { ... program here}'

# Shell
* Bourne Shell 
    - .sh extension
    - chmod 755 <filename> : to change permissions to executable 
    - ./<filename.extension> : to execute the file 