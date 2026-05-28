# Belajar perintah Git
- git config --global user.email ""
- git config --global user.name ""
git config --list
ls -la
git push -u origin main

## -- cuman dilakukan sekali
git init


## -- dilakukan berkali-kali
# (save) cara ribet
git add readme.md # <-- tapi ini repot

# (save) cara gampang
git add .
git commit -m "adding addme.md" # <--commit 

## kalau misalnya ada salah message commit 
git commit -m "message arrunya apa" --amend
## -- ini akan kamu pake untuk ngelihatin ada yang berubah atau gak 
git status

## -- ini akan kita pakai untuk liat udah simpen apa aja
git log 

## -- narik file dari github
git pull 

## Cloning 
git clone https://github.com/arnoldtan93/my-first-repo.git new_folder_name
git clone URL repo yang tadi digunakan nama-baru 

## tentang branching 
git branch <--finding out branches>
## pengen bikin branch yang baru (feature)
git checkout -b nama_branch_baru