# cursoprueba
  
realiazr un merge de local con remoto:  
  
- creamos una rama en github https://github.com/magzupao/cursoprueba.git de tipo public
- en la PC en local creamos una carpeta "prueba" y en el creamos unos ficheros
- en la misma carpeta ejecutamos "git init" se crea la carpeta .git
- vamos a fusionar el local con el remoto
  git remote add origin https://github.com/magzupao/cursoprueba.git  
  git fetch origin main  
  git checkout main  
  git merge origin/main  
  git push  
    
  visualizamos los archivos descargados:  
  ls -l   
  ls -la  
    
  subimos los archivos de local al remoto:  
  git add .  
  git commit -m "prueba envio"  
  git push origin main  
  
  
  
