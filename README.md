# tgts.xml-beacons
Inserting beacon codes into tgts.xml files for ATC scenario development. 
This is my resource for learning new skills - Python programming, primarily with XML, and LibreOffice
Intended audience is SGET developers, but anyone who can lend a hand coding in Python and using xml is welcome to contribute.
Sget developers write air traffic scenarios to be used in simulation labs across the country. My own lab is at ZDV ARTCC (Google).
The tools used in writing scenarios are inadequate for some types of data, therefore I'm learning Python to aid in building better data.
Since LibreOffice is deployed on the SGET Linux boxes (CentOS 5), I want to work on a cross-platform solution to use the data in MS apps.
This will replace, in most cases , my old sed/awk methods of inserting data, and should make things cleaner.
First goal is a script to assign realistic beacon code allotments using ZDV criteria, and make it adaptable for other ARTCCs.
Evenually, I want to program a portable xml based template that will run in either LibreOffice or Excel, 
and assign system messages to targeted sections of the various xml files used to construct a scenario.
These will be used to manipulate target reliability, EDST messages (SPA, free text, etc), track data, RECON, and the like.
Samples of scenario files will be uploaded, pending FAA approval. This will be scenario data, based on, but not actual, flight data.
