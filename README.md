# LR6
Лабораторная работа №6

**История операций в форматированном виде:**

    f34a347 2024-11-20 | B3441GafarovRR | Screenshots folder created
    9aebcb1 2024-11-20 | B3441GafarovRR | Revert "Second line added"
    1b5564d 2024-11-20 | B3441GafarovRR | Second line added
    3e92f37 2024-11-20 | B3441GafarovRR | Second line added
    6a423b3 2024-11-20 | B3441GafarovRR | New line added
    675bb1e 2024-11-20 | B3441GafarovRR | Update mergefile.txt
    921f53b 2020-11-21 | Kurtyanik | Обновление информации
    c08a654 2020-11-21 | Kurtyanik | Файл создан пустым
    3c6e913 2020-11-21 | Kurtyanik | Initial commit

**История команд:**

    1  git config --global user.name "B3441GafarovRR"
    2  git config --global user.email "rinat.gafarov.2002@gmail.com"
    3  git config --global --list
    4  git clone https://github.com/B3441GafarovRR/LR6
    5  cd LR6
    6  git pull origin newBranch
    7  git log
    8  git checkout newBranch
    9  git log
    10  git show
    11  git checkout master
    12  git pull origin master
    13  git merge newBranch
    14  git push
    15  git checkout master
    16  git branch -d newBranch
    17  git add mergefile.txt
    18  git commit -m "New line added"
    19  git add mergefile.txt
    20  git commit -m "Second line added"
    21  git add mergefile.txt
    22  git commit -m "Second line added"
    23  git push
    24  git log
    25  git revert 1b5564d77ef3fdfcf6f9ad90108ac1d9a7470be2
    26  git push
    27  git pull origin master
    28  git checkout -b report
    29  git branch
    30  vim README.md
    31  git log --pretty=format:"%h %ad | %an | %s" --date=short
    32  vim README.md
    33  git log --pretty=format:"%h %ad | %an | %s" --date=short
    34  vim README.md
    35  git checkout report
    36  mkdir screenshots/
    37  ls
    38  git add screenshots/
    39  mv ~/Desktop/png/*.png screenshots/
    40  git add screenshots/*.png
    41  git commit -m "Screenshots folder created"
    42  git push
    43  git push --set-upstream origin report
    44  git checkout report
    45  git log --pretty=format:"%h %ad | %an | %s" --date=short
    46  git pull
    47  git log --pretty=format:"%h %ad | %an | %s" --date=short
    48  vim README.md
    49  vim README.md
    50  git add README.md
    51  git commit -m "README.md updated"
    52  git push
    53  history
