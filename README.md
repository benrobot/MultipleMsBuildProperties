### Succeeds
```
cd 6.0.300
dotnet build -p:PackageVersion=1.1.13004;Version=1.1.13004;AssemblyVersion=1.1.13004;FileVersion=1.1.13004 "-p:AssemblyTitle=Built from Git branch refs/heads/feature/Something Blah blah blah"
```

### Fails
```
cd 6.0.303
dotnet build -p:PackageVersion=1.1.13004;Version=1.1.13004;AssemblyVersion=1.1.13004;FileVersion=1.1.13004 "-p:AssemblyTitle=Built from Git branch refs/heads/feature/Something Blah blah blah"
```

### Fails
```
cd 6.0.400
dotnet build -p:PackageVersion=1.1.13004;Version=1.1.13004;AssemblyVersion=1.1.13004;FileVersion=1.1.13004 "-p:AssemblyTitle=Built from Git branch refs/heads/feature/Something Blah blah blah"
```
