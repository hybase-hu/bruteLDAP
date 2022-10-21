# bruteLDAP
Check LDAP connection with username and password list


▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
▓▓                                                                             ▓
▓▓                                                                             ▓
▓▓    ▓▓▓▓    ▓▓▓▓    ▓▓ ▓▓   ▓▓▓▓▓  ▓▓▓▓       ▓▓     ▓▓▓▓    ▓▓▓▓    ▓▓▓▓    ▓
▓▓    ▓▓ ▓▓   ▓▓ ▓▓   ▓▓ ▓▓    ▓▓    ▓▓▓        ▓▓     ▓▓ ▓▓   ▓▓▓▓    ▓▓ ▓    ▓
▓▓    ▓▓▓▓    ▓▓▓▓    ▓▓ ▓▓    ▓▓    ▓▓▓▓       ▓▓     ▓▓ ▓▓   ▓▓▓▓    ▓▓▓▓    ▓
▓▓    ▓▓ ▓▓   ▓▓ ▓▓   ▓▓ ▓▓    ▓▓    ▓▓▓        ▓▓     ▓▓ ▓▓   ▓▓▓▓▓   ▓▓      ▓
▓▓    ▓▓▓▓▓   ▓▓ ▓▓   ▓▓▓▓▓    ▓▓    ▓▓▓▓       ▓▓▓▓   ▓▓▓▓▓  ▓▓▓ ▓▓   ▓▓      ▓
▓▓   ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓    ▓
▓▓                                                                             ▓
▓▓                                                                             ▓
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                         ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                         ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓    created@hybase-hu    ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓   github.com/hybase-hu  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓                         ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
▓▓                                                                             ▓
▓▓                                                                             ▓
▓▓                                                                             ▓
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓



#######################################################################
Usage: BruteLDAP.exe -U 'c:\users\userlist.txt' -P 'c:\users\passlist.txt' -L 'LDAP://domain.local'" -ForegroundColor Yellow
#######################################################################


[REQUIRED SETTINGS]

-U Userlist: username list file"
-P PasswordList: password list file (default max $C probe per user)" 
-L LDAPRootPath: Domain LDAP link ('LDAP://domain.local')"

[OPTIONAL SETTINGS]

-C Password number probe per user (default is $C)"
   Warning, default ActiveDirectory bad password lockout settings is 7"
   
   
   
**********************************************************************
SUCCESS connection values save in the random geneartion name txt
**********************************************************************
