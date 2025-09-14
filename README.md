# errors-powershell

### In PowerShell, you need to wrap such paths in quotes, otherwise it treats Pal\Downloads as a separate argument.
+ Get-ChildItem -Path C:\Users\Naresh Pal\Downloads -Recurse -Directory ...
+ ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : PositionalParameterNotFound,Microsoft.PowerShell.Commands.GetChildItemCommand

### Manually download zip and follow commands one by one
âŒ Download failed: File is not a valid ZIP.

### Requested registry access is not allowed.
Run script as Administrator

