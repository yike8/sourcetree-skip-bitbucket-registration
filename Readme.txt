How to skip bitbucket registration when installing sourcetree?

The first step is to run SourceTreeSetup-3.1.3.exe and close it after popping up the registration interface.

The second step is to open the %AppData%\Atlassian directory, find accounts.json and user.config, and replace them with the files I provided.(The %LocalAppData%\Atlassian directory is still valid, but it is recommended to follow the new operation method.）

e.g.
%AppData%\Atlassian\SourceTree\accounts.json
%AppData%\Atlassian\SourceTree.exe_Url_iayhtc13zv3obzuz5vchezjs1az2q5ef\3.3.8.3848\user.config
