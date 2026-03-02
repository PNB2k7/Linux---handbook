		NAVIGATION
pwd : Print working directory

ls : Show list 
-> ls -la : Show all (contain hidden file or permissions)

cd : Change directory


		MANIPULATION	
NOTE: All of below commands can use with PIPE(|) mindset. This means output of a command can be input of other command.

#Creating & Deleting
mkdir : Create folders

touch : Create files

rm    : Delete files
rm -d : Delete empty folder
rm -r : Delete all 

#Reading
cat   : Show all content in file into TERMINAL

less  : Open in interactive mode (can rolling, search)

head  : Show only 10 line in file -> This can be use to check header in coding

tail  : Show only last 10 line in file -> This can be use to check note about bug in file log

#Managing
cp    : Copy to a new file (base file still exists)

mv    : Move to new location or change file's name

#Searching

find  : search location of file by name, size, date
	# find . -name "*.cpp" (Search all file C++ in current folder)

grep  : search in file
	# grep "int main" main.cpp (Find line which has "int main" in file main.cpp)
	
		Data workflow & Scripting
#Redirection 
>     : overwrite 
>>    : insert in tail

#Piping(|): A OUTPUT OF THAT COMMAND CAN BE INPUT OF OTHERS COMMAND


