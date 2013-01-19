General Format
==============
    {Record Type},{Row #}, {data}

Record Type
===========
* 001 - header
* 020 - unit record
* 021 - award record
* 900 - end sentinal

Record Format 001
-----------------
    001,{record #},A,{report date},210842,PackMaster ME,02.00

Record Format 020
-----------------
    020,{record #},Pack,{unit #},{charter expiration YYYYMM},{District},{City},{State},{Zip},{Chartered Org},{Cubmaster 1st name},{Cubmaster middle},{Cubmaster Last},{cubmaster address 1},{cubmaster line 2},,,{cm city},{cm state},{cm zip},US,{cm area code},{cm prefix},{cm last 4},,,,,,{report date},{need by date},{board of review date},

Record Format 021
-----------------
    021,{record #},{Scout last},{scout middle},{scout first},{birthday - YYYYMMDD},{SSN},{award date},{award code},

Record Format 900
-----------------
    900,{record #}

Example File
============
    001,1,A,20120919,215325,PackMaster ME,02.00,
    020,2,Pack,0057,201301,Mohawk,Little Rock,AR,72207,First Christian Church,John,,Scouter,123 Main St,line 2,,,Fairfax,VA,22032,US,434,442,1234,,,,,,20120919,20120924,20120919,
    021,3,Bobby,,Scout,20030102,,20120901,RC,
    021,4,Bobby,,Scout,20030102,,20120901,RI,
    021,5,Bobby,,Scout,20030102,,20120920,RR,
    021,6,Bobby,,Scout,20030102,,20120901,C10,
    021,7,Bobby,,Scout,20030102,,20120902,C11,
    021,8,Bobby,,Scout,20030102,,20120903,C12,
    021,9,Bobby,,Scout,20030102,,20120904,C13,
    021,10,Bobby,,Scout,20030102,,20120905,C14,
    021,11,Bobby,,Scout,20030102,,20120906,C15,
    021,12,Bobby,,Scout,20030102,,20120907,C16,
    021,13,Bobby,,Scout,20030102,,20120908,C17,
    021,14,Bobby,,Scout,20030102,,20120909,C18,
    021,15,Bobby,,Scout,20030102,,20120910,C19,
    021,16,Bobby,,Scout,20030102,,20120911,C20,
    021,17,Bobby,,Scout,20030102,,20120912,C21,
    021,18,Bobby,,Scout,20030102,,20120913,C22,
    021,19,Bobby,,Scout,20030102,,20120914,C23,
    021,20,Bobby,,Scout,20030102,,20120915,C24,
    021,21,Bobby,,Scout,20030102,,20120916,C25,
    021,22,Bobby,,Scout,20030102,,20120917,C26,
    021,23,Bobby,,Scout,20030102,,20120918,C27,
    021,24,Bobby,,Scout,20030102,,20120919,C28,
    021,25,Bobby,,Scout,20030102,,20120920,C29,
    900,26,

Award Codes for Cub Scout Packs
===============================
* RC - Bobcat
* RI - Tiger
* RW - Wolf
* RB - Bear
* RR - Webelos
* RA - Arrow of Light
* C10 - Aquanaut Webelos Pin
* C11 - Artist Webelos Pin
* C12 - Athelete Webelos Pin
* C13 - Citizen Webelos Pin
* C14 - Communicator Webelos Pin
* C15 - Craftsman Webelos Pin
* C16 - Engineer Webelos Pin
* C17 - Family Member Webelos Pin
* C18 - Fitness Webelos Pin
* C19 - Forester Webelos Pin
* C20 - Geologist Webelos Pin
* C21 - Handyman Webelos Pin
* C22 - Naturalist Webelos Pin
* C23 - Outdoorsman Webelos Pin
* C24 - Readyman Webelos Pin
* C25 - Scholar Webelos Pin
* C26 - Scientist Webelos Pin
* C27 - Showman Webelos Pin
* C28 - Sportsman Webelos Pin
* C29 - Traveler Webelos Pin
