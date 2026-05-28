# Belajar perintah Git
git config --global user.email ""
git config --global user.name ""
git config --list
ls -la

## -- cuman dilakukan sekali
git init


## -- dilakukan berkali-kali
# (save) cara ribet
git add readme.md # <-- tapi ini repot

# (save) cara gampang
git add .
git commit -m "adding addme.md" # <--commit 

## -- iini akan kamu pake untuk ngelihatin ada yang berubah atau gak 
git status