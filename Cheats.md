# General Cheats
 |Action             | Application   | Description
 |:------------------:|:--------------:|:--------------:|
 |Command K          | github site   | Jump to a location be it Repo or file
 |Command K          | Apple Finder  | Open a server list
 |F1                 | VSCode        | Command Palette
 |CTRL + SHIFT + P   | VSCode        | Command Palette
 |CTRL Enter         | VSCode        | CoPilot Suggestions
 |F4                 | Syteline      | Filter in Place

# Terminal Cheats
 | Action | Bash or not | Notes |
 |:------:|:-----------:|:-----:|
 | Syteline_import[Utilities<VERSION_NUMBER>.jar] | Bash Script | Copy and paste the version number from the file in IDM |
 |Kill_This | Bash Script | clear ssh-agent |
 |push[<BRANCH_NAME>] | Bash Script | Push to a branch |

 ### Find Strings
 | Action | OS | Notes |
 |:------:|:--:|:-----:|
 |```findstr <STRING> "N:\LabelOutputs\*" ```| Windows | Find a string in a folder |
 |```findstr "<STRING>" [N:\LabelOutputs\*]|findstr "<STRING>" ```| Windows | Find a string in a folder |
 |```grep -i or l <STRING> N:\LabelOutputs\*``` | macOS | Find a string in a folder |
 |```grep -r <STRING>  ```| Linux/Mac | Find a string when in a folder |
 |```select-string -path N:\LabelOutputs\* -pattern "<STRING>" ``` | PowerShell | Find a string in a folder |
 |```select-string  '<STRING>' "$HOME\..\..Volumes\N:\LabelOutputs\*" ```  | PowerShell | Find a string in a folder|
 |```select-string  -pattern '04/07/2023', 'Label Backup' -AllMatches "$HOME\..\.. \Volumes\LabelOutputs\*" ```  | PowerShell | Find two strings in a folder will return all|
 |```select-string -pattern '(?s) (Label Backup).+? (04/07/2023)' "$HOME\.. \.. \Volumes\LabelOutputs\*" ``` | PowerShell | Find a string in a folder with 2 conditions must be in that order |
 |```Get-ChildItem -Path "$HOME\..\..\Volumes\kt-fs1\LabelOutputs\" -Filter "*.dat" -Recurse | select-string -pattern '(?s)(2_2.2).+?(07/10/2023)'``` | PowerShell | Find a sting and all the sub folders |
  
## llama 
**Easy terminal searching**

*Use ```ll``` to open*
|Action | Description|
|:-----:|:----------:|
|arrows or HJKL | navigate|
|Enter | open|
|Backspace | go back|
|Space | open in new tab|
|Esc | close with cd action|
|ctrl + c | close without cd action|
|/ | fuzzy search|
|dd | delete|
|Below is a test| auto complete test|
|yy | copy|
|pp | paste|
|cc | rename|
|mm | move|
|gg | go to top|
|G | go to bottom|
|? | help|
|q | quit|
|antonmedv/lama | GitHub|

