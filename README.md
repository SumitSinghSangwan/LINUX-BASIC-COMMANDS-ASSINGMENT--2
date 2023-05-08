# LINUX-BASIC-COMMANDS-ASSINGMENT--2

# Assignment Part-3
--->>Playing with files
        1. Create a file like nano file1.txt
            o Edit some data and then save the file
        2. Now we will copy date from file1 to new file2
            o cp file1.txt file2.txt
            o Then see the output of file2.txt, cat file2.txt
            o Please find the screenshot
            
 ![image](https://user-images.githubusercontent.com/132274417/236668562-25575814-db95-4e94-bd39-314deca2d382.png)


            3. Now we will move the file2.txt to new folder /home
            o mv file2.txt /home
            o Then go to home directory and check ls, file exits or not?
            -->>yes file2.text already exist and o/p show premission denied pls dind attached snap
            
 ![image](https://user-images.githubusercontent.com/132274417/236668904-eccaedc8-e3d9-4676-80ad-c7092a6d1d00.png)
           

4. Then we create a new file3.txt and file4.txt in home directory and add
content in it.
o Now do echo “Hello I am newline” > file3.txt and provide the
  output of file3.txt
          o Now do echo “Hello I am newline” >> file4.txt and provide the
          output of file4.txt
          o Tell the different between both step you follow and the reason
          behind it
          
          
  ![image](https://user-images.githubusercontent.com/132274417/236709043-6605d7c0-2b9a-423e-9d49-deda64665a0e.png)

# answere-->> the main differnce is after applying first command the content is deltetd of file3.text file and new line o/p is showwing,but after echo “Hello I am newline” >> file4.txt the contetnt is not deleted and new content is added in last of file4.ext

5. For remove a file or directory you can use the below two commands
          o To delete a file – rm <any_filename>
