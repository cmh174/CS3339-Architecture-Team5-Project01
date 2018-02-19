# CS3339-Architecture-Team5-Project01
# Its project for architecture, Trying to figure out git.

   print('Hello World')# for testing perposes
   with open('test_bin.txt') as file: # should read the file till eof
   #file = open('test_bin.txt','r')#code to open and read availabel data.
   decode = []#empty List/Array
      for line in file: # for every line in the txt file print a line readability purposes
                        # also add the data in the read in line. 

         decode.append(line) # adding the data in the current txt file to the array 

         print decode # these two snippets are for testing to make sure every line is being read.

   file.close()
