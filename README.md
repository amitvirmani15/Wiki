Remove downloaded packages recursively from local repo
Powershell
Remove-Item –path "C:\Users\admin\source\repos" -include *packages* -recurse