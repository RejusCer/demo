# Demo

projektėlis skirtas darbui su github

## GIT comandos

<b>Sukurti ssh raktą, pridėti ssh agent ir rakto pridėjimas prie projekto</b>
ssh-keygen -t rsa -b 4096 -C "email@email.com
[github'e irašyti nauja ssh raktą iklijuojant viešajo rakto kodą]
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/{rakto vardas}

<b>Projekto paemimas iš github</b>
clone git@github.com:RejusCer/demo.git
push

<b>Naujo projekto sukurimas lokalioje aplinkoje</b>
git init
git remote add origin git@github.com:RejusCer/demo.git
push -u origin master

<b>Kitos komandos:</b>
status
add .
commit -m ""
