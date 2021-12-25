► NanoBackups-Script ◄

➤ This script makes a backup file for every file you create with text editor nano.

➤ NanoBackups Setup:
   
    ● nano .profile
    ● Paste the following lines in the documment anywhere you desire:
      > mkdir -p ~/.NanoBackups
        alias nano='nano -T 4 -c -B -C ~/.NanoBackups'
    ● source .profile (To save and apply changes to the documment.
