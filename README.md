# Demo

projektėlis skirtas darbui su github

## GIT comandos

<b>Sukurti ssh raktą, pridėti ssh agent ir rakto pridėjimas prie projekto</b>  
ssh-keygen -t rsa -b 4096 -C "email@email.com  
[github'e irašyti nauja ssh raktą iklijuojant viešajo rakto kodą]  
eval "$(ssh-agent -s)"   ---- windows power shell: Get-Service -Name ssh-agent | Set-Service -StartupType Manual
ssh-add ~/.ssh/{rakto vardas}  

<b>Projekto paemimas iš github</b>  
clone git@github.com:RejusCer/demo.git  
push  

<b>Naujo projekto sukurimas lokalioje aplinkoje</b>  
git init  
git remote add origin git@github.com:RejusCer/demo.git  
push -u origin master  

<b>GIT branch komandos</b>  
git branch [name] {-d ištrinti šaką}  
git checkout -b [name] {-b sukurti šaką}  
git diff [su kuo lyginti]  
git push -u origin [branch]  
git pull  

<b>Kitos komandos:</b>  
status  
add . {arba atvirkštynis variantas} reset  
commit -m "" {arba atvirkštynis variantas} reset HEAD~1 {arba} reset HARD [commit kodas]  
