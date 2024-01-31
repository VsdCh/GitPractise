In this repository:
1. program ver 1.0
2. program ver 2.0 (i edited code in file just in website)
3. added (uploaded) same file called test.py but with text: program ver 3.0
seems like file was replaced (test.py >> test.py)
4. program ver 4.0 (edited file on site)
5. cloned git repository
6. locally edited file test.py: "program ver 5.0 (edited in IDLE)"
7. made git push
8. after push, on site ive nmade changes in README.md
9. then i ipdate local repository from site (README.md should be updated)
10. locally i write program ver 6.0 (edited in IDLE) in test.py, write 10th line in README.md and push again

**Example**

In PythonCorePractise:
There was diff between local and remote repository:

---------------------------------------------------------------------
line1 = "teaCHeR"

line2 = "reSeArcHer"

print(line1.casefold())

print(line2.casefold())

<<<<<<< HEAD

print(line1.capitalize())

print(line2.capitalize())

||||||| a63fed2

=======

#делает так чтобы все line были строчными буквами
>>>>>>> b9295020a2a3333b2e56bd199d3676880fe6a889
--------------------------------------------------------------------
***Scheme***
1. HEAD = same part

2. only in local

3. only in remote


***commands*** (NOTE: you should be in folder of your repository): 

          git clone [url]
          
          git add --all
          
          git commit
          
          git commit -a --allow-empty-message -m ''
          
          git push

          git pull

          git remote add <name> <url>
          
          git fetch <NameOfRepository>
          git pull <NameOfRepository> master
          git push
          
git pull = (without any more) update changes from REMOTE to LOCAL
