# errors-powershell

### PS C:\Users\Naresh Pal\Downloads> Get-ChildItem -Path C:\Users\Naresh Pal\Downloads -Recurse -Directory -Filter "Projects*" -ErrorAction SilentlyContinue
Get-ChildItem : A positional parameter cannot be found that accepts argument 'Pal\Downloads'.
At line:1 char:1
+ Get-ChildItem -Path C:\Users\Naresh Pal\Downloads -Recurse -Directory ...
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetChildItemCommand

