# Problem-Setting
Problem Setting Guidelines For Competitive Programmming Contest

  Commands for Testcases Input and Output Generation and File Comparison:

      Windows:
          1) To generate testcases from a generator program

                  Let us say we wrote TestCaseGen.cpp, compile it so that it generates TestCaseGen.exe

                  Open Command Prompt in The Same Folder

                  (To Open Command Prompt In A Folder, Browse to that Folder in file Explorer, Then in the address bar type cmd)

                      TestCaseGen.exe > input02.txt

                  This command generates input file named input02.txt



          2) To Get Output corresponding to a particular input file, 

                  Let us say our solution was Shiv.cpp

                  Open Command Prompt in The Same Folder

                      Shiv.exe < input02.txt > shivout02.txt

                  This command generates output file named output02.txt


          3) To compare two output files

                      fc SOLUTION1out02.txt SOLUTION2out02.txt

              The command should show the differences or give message 'No Differences'




      Linux/Mac:

          1) To generate testcases from a generator program

                  Let us say we wrote TestCaseGen.cpp, compile it so that it generates binary file say 'TestCaseGen'

                  Open Terminal in The Same Folder

                      ./TestCaseGen > input02.txt

                  This command generates input file named input02.txt



          2) To Get Output corresponding to a particular input file, 

                  Let us say our solution was Shiv.cpp, generate binary file

                  Open Terminal in The Same Folder

                      ./Shiv < input02.txt > shivout02.txt

                  This command generates output file named output02.txt


          3) To compare two output files

                      diff SOLUTION1out02.txt SOLUTION2out02.txt

              The command should show the differences or give message 'No Differences'
