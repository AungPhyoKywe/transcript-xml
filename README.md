# Parliamentary Transcripts

Opendata repository which contain digitized version of Parilamentary Transcripts from 
- [Pyithu Hluttaw (Lower House)](https://www.pyithuhluttaw.gov.mm/)
- [Amyotha Hluttaw (Upper House)](https://www.amyotha.hluttaw.mm/)
- [Pyidaungsu Hluttaw (Union House)](https://pyidaungsu.hluttaw.mm/)

## File Names
  File names contains six digits like this ``02-16-01.xml``. Fist two digit stands for Term, the middle two digit stands for Session and Last two digits stands for Sitting Day.
  So ``02-16-01.xml`` means Second Term, 16th Session, First Sitting Day.
  
## Directory Structure 
Root directories are divided by their terms and in the sub directory files are again divided by House and File type. The directory structure is as follow.

- First Term
  - lower
    - xml (First Term Lower House)
  - upper
    - xml (First Term Upper House)
- Second Term
  - lower
    - xml (Second Term Lower House)
  - upper
    - xml (Second Term Upper House)
  - union
    - xml (Second Term Union House)
   
## How we did it
Draft paper of the digitization process is available [here](https://docs.google.com/document/d/e/2PACX-1vR99NGl48LqOJsl8nwoGtrP0sOEBiGtPq9V4e2bWRuLQgj2MEsIorqNThiDYFJcwDKTy7kDpLjTJGBB/pub)
