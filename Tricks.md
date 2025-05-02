# Pendrive
### Check Drive Status (GPT/MBR)
1) Open CMD as Administrator
2) Type 'diskpart'
3) Type 'list disk'
4) If disk has a star(*) mark at GPT section then it's GPT.

## Convert Drive Status (GPT/MBR)
1) Open CMD as Administrator
2) Type 'diskpart'
3) Type 'list disk'
4) Type 'select disk 1/2/3' [enter your desired disk number]
5) Type 'clean'
6) Type 'convert GPT/MBR'

## Bootable to Normal Pendrive
1) Open CMD as Administrator
2) Type 'diskpart'
3) Type 'list disk'
4) Type 'select disk 1/2/3' [enter your desired disk number]
5) Type 'clean'
6) Type 'create partition primary'
7) Type 'active' [For MBR partition only]
8) Type 'format fs=ntfs quick'