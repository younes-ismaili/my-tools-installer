# my-tools-installer

  - Run the script
  
     $ brew update
     $ brew install readline 
  
  - how to install valgrind
  
      $ brew tap LouisBrunner/valgrind
      $ brew install --HEAD LouisBrunner/valgrind/valgrind

   - how to run avlgrind
   - install vscode-valgrind extensins in vscode
      $ valgrind --leak-check=full --show-leak-kinds=all --trace-children=yes --log-file="valgrind.txt" ./prog_name "arg1 arg2 .."
