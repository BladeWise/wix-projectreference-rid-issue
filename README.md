# wix-projectreference-rid-issue
Repro repo for WiX issue with ProjectReference with specific RID.

Attempting to build the solution with `dotnet build -c Release` results in a **NETSDK1047** error.
Attempting to build the solution with `dotnet build -c Release -r win-x64` succeeds.
