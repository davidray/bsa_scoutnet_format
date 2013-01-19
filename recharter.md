General Format
==============
{Record Type},{Row #}, {data}

Record Types
============
* 001 - header
* 010 - Unit info
* 011 - Registered member?
* 012 - Second line of 11
* 015 - Unregistered parent?
* 016 - Second line of 15
* 900 - end sentinal

Record Type 001
---------------
001,1,R,Date Created (YYYYMMDD),102808,TroopMaster ME,02.00,

Record Type 010
---------------
    010,2,Unit Type (Troop/Pack),Unit Number (4 digits),Charter Expiration Date (YYYYMM),District,Charter Org Name,Charter Org Address Line 1,,,,Charter Org City,Charter Org State Code,Charter Org Zip,US,Charter Org Area Code,Charter Org Phone 1-3,Charter Org Phone 4-7,,,,,,12,New Charter Expiration Date (YYYYMM), ,,N,N,N,N,1,3,Meeting Time (H:MM),Meeting Place Name,Meeting Place Address,,,,Meeting Place City,Meeting Place State,Meeting Place Zip,US,Meeting Place Area Code,Meeting Place Phone 1-3,Meeting Place Phone 4-7,,,,,,16,0,2,0,18,0,0,0,0,24000,0,27000,0,0,0,2000,53000,

Record Type 011 & 012
---------------------
    011,Row #,P,SSN,Driver's License #,Driver's License State Code,,First Name,Middle Initial,Last Name,Suffix,Nickname,,,Birthdate(YYYYMMDD),Gender(M/F), ,,Position Code,8,R1,Grade,N,

  012,Row #,2,Y,Street Address Line 1,Street Address Line 2,,,City,State,ZIP,US,area code,phone 1-3,phone 4-7,,,,,,

Record Type 015 & 016
---------------------
These rows follow the scout row to which they relate 

    015,Row #,Parent #(1 or 2),Y,,,,,First Name,Middle Initial,Last Name,,Nickname,,,,Gender(M/F),Occupation Type Code,Employer,
    016,Row #,2,Y,Street Address Line 1,,,,City,State,Zip,US,Area Code,Phone 1-3,Phone 4-7,,,,,,

Record Type 900
---------------
    900,Row #

Position Codes
==============
* CR Chartered organization representative
* CC Committee chairman
* MC Committee member
* SM Scoutmaster 
* SA Assistant Scoutmaster
* NL Crew Advisor
* NA Crew associate Advisor
* SK Skipper
* MT Mate
* VC Varsity Scout Coach
* VA Assistant Varsity Scout Coach
* CM Cubmaster
* CA Assistant Cubmaster
* WL Webelos den leader
* WA Assistant Webelos den leader
* DL Den leader 
* DA Assistant den leader
* TL Tiger Cub den leader
* PT Pack trainer
* PC ScoutParent unit coordinator
* 10 Leader of 11-year old Scouts (LDS Troop)
* 88 Lone Cub Scout friend and counselor
* 96 Lone Scout friend and counselor
* PS ScoutParents
* AP Tiger Cub adult partners (AP) 

Occupation Type Codes
=====================
* 354999 - Protective (Fire/Police)
* 339999 - Administrative/Clerical