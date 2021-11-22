# PowerShell-Lessons-Learned
1. Expand "members" of an object: append | Get-Member
2. PowerShell modules should be placed in a NEW subfolder named the same as the module in one of the folders in the $env:PSModulePath (e.g. PSGuacamole)
3. [IO.Path]::DirectorySeparatorChar returns / on macOS but \ on Windows
4. [system.io.path]::GetTempPath() works for TEMP path on both macOS and Windows.
