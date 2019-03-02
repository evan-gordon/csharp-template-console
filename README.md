## Init Your Project

Change root directory name to your project name</br>

Remove .git from project</br>
```
rm -rf .git
```

Initialize git in your new project</br>
```
git init
```

Add your source code and tests</br>

Enjoy :)</br>

## To Run
```
dotnet run src/
```

## To Test
```
dotnet test test/
```

### Contribution
If you see any issues with the current setup, or want to make the project more general feel free to submit a PR.

### Steps Used in Project ceation
```
#init dotnet console app
cd src/
dotnet new console

#init test
cd ../test/
dotnet new xunit
dotnet add reference ../src/src.csproj
```