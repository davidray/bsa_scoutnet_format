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
    010,2,Unit Type (Troop/Pack),Unit Number (4 digits),Charter Expiration Date (YYYYMM),District,Charter Org Name,Charter Org Address Line 1,,,,Charter Org City,Charter Org State Code,Charter Org Zip,US,Charter Org Area Code,Charter Org Phone 1-3,Charter Org Phone 4-7,,,,,,Charter Term (Months),New Charter Expiration Date (YYYYMM), ,,Magazine Bulk Delivery? (Y/N),Leader Trained? (Y/N),100% Boys Life? (Y/N),Quality Unit? (Y/N),Meeting Frequency Code,Meeting Day Code,Meeting Time (H:MM),Meeting Place Name,Meeting Place Address,,,,Meeting Place City,Meeting Place State,Meeting Place Zip,US,Meeting Place Area Code,Meeting Place Phone 1-3,Meeting Place Phone 4-7,,,,,,Paid Adult Count,Transfer Adult Count,Multiple Adult Count,Non-Registered Adult Count,Paid youth count,Transfer youth count,Multiple youth count,Adult Boys Life Count,Yout Boys Life Count,Adult Registration Fee,Adult Transfer Fee,Youth Registration Fee,Youth Transfer Fee,Adult Boys Life Fee,Youth Boys Life Fee,Unit Fee,Total Registration Fee,

Record Type 011 & 012
---------------------
    011,Row #,Primary/Multiple/Transfer/Non-Registered (P/M/?/?),SSN,Driver's License #,Driver's License State Code,,First Name,Middle Initial,Last Name,Suffix,Nickname,,,Birthdate(YYYYMMDD),Gender (M/F), ,,Position Code,8,Rank Code,Grade,Boys Life (Y/N),
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
* M  Scout? Member?

Rank Codes
==========
* RN - Scout
* RT - Tenderfoot
* R2 - 2nd Class
* R1 - 1st Class
* RS - Star
* RL - Life
* RE? - Eagle

Occupation Type Codes
=====================
* 354999 - Protective (Fire/Police)
* 339999 - Administrative/Clerical

Meeting Frequency Codes
=======================
* 1 - Weekly
* 2 - Bi-Weekly
* 3 - 1st Week
* 4 - 2nd Week
* 5 - 3rd Week
* 6 - 4th Week
* 7 - 1st & 2nd Week
* 8 - 1st & 3rd Week
* 9 - 1st & 4th Week
* 10 - 2nd & 3rd Week
* 11 - 2nd & 4th Week
* 12 - 3rd & 4th Week
* 13 - 1st, 2nd, & 3rd Week
* 14 - 1st, 2nd, & 4th Week
* 15 - 1st, 3rd, & 4th Week
* 16 - 2nd, 3rd, & 4th Week

Meeting Day Codes
=================
* 1 - Sunday
* 2 - Monday
* 3 - Tuesday
* 4 - Wednesday
* 5 - Thursday
* 6 - Friday
* 7 - Saturday