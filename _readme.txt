ES (E-Mini S&P 500 Futures)  DataSet
==========================================

NOTE: Only minutes with trading volume are included. Bars with zero volume are excluded. 

 
Timeframes : 1-minute, 5-minutes, 30-minutes, 1-hour
 
Continuous:02-Jan-2008 - 11-Nov-2022
Individual Contracts : ESH08 - ESZ23 (December 2023)


Updates
-------
Dataset is updated daily (day's updates available by 11pm US Eastern time)

(daily updates only apply to the continuous unadjusted data. Continuous adjusted data and
individual contract data are updated weekly).




Notes
-----


The continuous futures series is a single series of futures prices created by combining
the active front month contracts.
The full dataset contains both adjusted and un-adjusted continuous series. The adjusted series adjusts for price jumps on contract roll dates to ensure a consistent series which is suitable for backtesting. 

The individual contracts are in separate files with the file format:
ES{expiry month}{year}.txt

Months are :January	(F), February (G), March (H), April (J), May (K)
June (M), July (N), August (Q), September (U), October (V), November (X)
December (Z)
Note : Not all futures have a contract for each month.

Year is a two digit number eg : 2017 is 17
 


- File Format : {DateTime, Open, High, Low, Close, Volume}
- Timezone is US Eastern Time   
- Timestamps run from the start of the period (eg 1min bars stamped 09:30 run from 09:30.00 to 09:30.59)
- Times with zero volume are omitted (thus gaps in the data sequence are when there have been no trades)
- Excel will usually fail to open large files directly. 
  To use the data in Excel, open the files using notepad and then break into smaller files or copy/paste into Excel
- Data license is available at https://firstratedata.com/about/license
   

___________________________
copyright FirstRateData.com