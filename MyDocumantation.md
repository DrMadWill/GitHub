# My Documantation
***
### Merge Testing
### Conflict Testing v1
### Pull request Testing
***
### GitHub Code
***
- `git init` => _folder_-ə `init` _file_-larını əlavə edir.
- `git add .` =>  _folder_-dəki hər şeyi  _stage area_-a göndərir.
- `git commit -m "commit"` =>  _stage area_-dakı hər şeyi `local repository`-ə göndərir.
- `git branch -M main` =>  əsas `branch`-ı `main`-ə çevirir.
- `git push - u origin main` =>  `branch`-ı `main` olan  `remote repository`-ə göndərir.
- `git branch` => `local` olan `branch`-ları çıxarır.
- `git branch -a` => btün `branch`-ları çıxarır.
- `git branch testing` => burada `local`-da `testing` adlı `brach` yaradır.
- `git checkout testing` => burada `local`-dakı `testing` adlı `brach`-a keçir.
- `git status` => məlumatlarin _stage area_-a və `remote`-a əlavə edilib edilmədiyini bildirir.
- `git pull` => `remote repository`-idə olan dəyişiklikləri `local repository`-ə əks etdirir.
- `git push origin :testing` => `remote`-dakı `testing` `branch`-ını sillər.
- `git branch -D testing` => `local`-dakı `testing` `branch`-ını sillər.
- `git checkout -b Test` => `Test` `branch`-ı yaradır və o `branch`-a keçir.
- `git merge origin/Testing`=> `Testing` `branch`-ını olduğu `branch`-a `merge`-ləyir.
- `git merge origin/Testing`=> `Testing` `branch`-ını olduğu `branch`-a `merge`-ləyir.
- `git merge Testing main` => `Testing` `branch`-ını `main` `branch`-ına `merge`-ləyir.
- `git stash push` => dəyişikliyi qeydir ancaq _stage area_-a əlavə etmir. `brach` arasinda deşilikdə isfadə edilir.
- `git stash list` => `stash` edilmiş iformationları list səkilində göstərir.
- `git stash apply` => `stash` edilmiş iformationları kod sətrində göstərir.
- `git stash clear` => `stash`-ları təmizləyir.
- `git reset --hard` => `branch`-dakı dəşiklikləri en soncu `commit`-ə qaytarir `discard` deyilən hadisə.
- `git checkout -- MyDocumantation.md` `branch`-dakı _MyDocumantation.md_ faylındakı dəşiklikləri en soncu `commit`-ə qaytarir.