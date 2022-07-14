# BIG_DATA_W_DASK
BSAD 699 Data Science Article

# Loading Massive Files into Dataframes with Dask and Pandas

*So you've got massive file chunks and want to join them to one data frame*
*In this tutorial, I will show you how you can load big data with Dask*

#import pandas and dask.datframe

<img width="700" alt="1" src="https://user-images.githubusercontent.com/29932870/179015593-b04daf3d-a34f-4c37-89cd-2839b9269513.png">

#Take chunks from same file- Dropping NULL DATE values

<img width="700" alt="2" src="https://user-images.githubusercontent.com/29932870/179015743-45553cd0-5185-49e9-9088-d295a0a10e0e.png">
<img width="700" alt="3" src="https://user-images.githubusercontent.com/29932870/179015781-aff3390c-2b30-4b16-b2dd-40b51487aef5.png">
<img width="700" alt="4" src="https://user-images.githubusercontent.com/29932870/179015826-baa23af4-e645-4328-a472-a82304a83153.png">

#Now that we have all of our chunks with NULL Dates Removed, we will CONCAT the 9 master files to create one massive file

<img width="1039" alt="5" src="https://user-images.githubusercontent.com/29932870/179017025-a6995ad5-c4cc-400d-94de-26bf2ff77003.png">

#GREAT! Now we have all 9 chunks loaded into 1 data frame with the variables we need and dropped DATE Values

#NEXT- We will join on Pandas function .MERGE to join different data frames

<img width="1039" alt="6" src="https://user-images.githubusercontent.com/29932870/179017394-7b4fc28b-fac6-44ac-8486-0b129124b35a.png">
