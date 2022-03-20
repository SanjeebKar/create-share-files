# create-share-files
 
 Statements: 
                        1. Create a text file
                        2.Ensure any user can read and write it 
                        3.Compress the file using tar or zip
                        
 Solutions:
                        1. vi newfile
                        2. chmod a+rw newfile
                        3. tar -czf newfile.tgz newfile
                           ls -lh newfile.tgz
                      
