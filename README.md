# Model Mania in FreeCAD Link Branch

My attempt to complete all of the 
[SolidWorks Model Mania](https://blogs.solidworks.com/tech/2022/02/23-years-of-model-mania.html)
challenges using Realthunder's [experimental FreeCAD Branch](https://github.com/realthunder/FreeCAD_assembly3/releases).

Each year in which a challenge was offered has a folder in this repository,
containing the modelled part (or a partially finished attempt).

Notes:
- The challenges usually have a 2 stage format. I've chosen to separate stage 1 
  and 2 into their own files.
- Stage 2 usually has a mechanical simulation component. This part of the challenge
  will be worked on once the modelling parts are as complete as possible.
- All FreeCAD files are saved in Directory format for better 
  behavior under git.
- This repository has over 1GB of mesh and brep data. Except `git clone`
  to be slow.  
- All files confirmed working with the following FC version:
  ```
  OS: Manjaro Linux (XFCE/xfce)
  Word size of OS: 64-bit
  Word size of FreeCAD: 64-bit
  Version: 2021.1015.24301 +4280 (Git) AppImage
  Build type: Release
  Branch: LinkDaily
  Hash: 556c87868ea46796242156e9f73eae98259794b7
  Python version: 3.9.7
  Qt version: 5.12.9
  Coin version: 4.0.1
  OCC version: 7.5.2
  ```

Progress table:

|       Symbol           |          Indicates                                 |
|------------------------|----------------------------------------------------|
| :heavy_check_mark:     | Completed with no major problems                   |
| :large_orange_diamond: | Complete with some changes made to model           |
| :red_circle:           | Incomplete, usually due to FreeCAD OCC limitations |
| :black_square_button:  | Incomplete, not attempted yet                      |


| Year |          Stage1        |        Stage2          |       Simulation       |
|------|------------------------|------------------------|------------------------|
| 2000 | :heavy_check_mark:     | :heavy_check_mark:     | N/A                    |
| 2001 | :heavy_check_mark:     | :heavy_check_mark:     | N/A                    |
| 2002 | :heavy_check_mark:     | :black_square_button:  | N/A                    |
| 2003 | :heavy_check_mark:     | :heavy_check_mark:     | N/A                    |
| 2004 | :heavy_check_mark:     | :heavy_check_mark:     | N/A                    |
| 2005 | :heavy_check_mark:     | :heavy_check_mark:     | N/A                    |
| 2006 | :heavy_check_mark:     | :heavy_check_mark:     | N/A                    |
| 2007 | :heavy_check_mark:     | :heavy_check_mark:     | N/A                    |
| 2008 | :large_orange_diamond: | :large_orange_diamond: | :heavy_check_mark:     |
| 2009 | :heavy_check_mark:     | N/A                    | :heavy_check_mark:     |
| 2010 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2011 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2012 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2013 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2014 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2015 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2016 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2017 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2018 | :heavy_check_mark:     | :large_orange_diamond: | :heavy_check_mark:     |
| 2019 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2020 | :heavy_check_mark:     | :heavy_check_mark:     | :heavy_check_mark:     |
| 2021 | :heavy_check_mark:     | N/A                    | :heavy_check_mark:     |
| 2022 | :heavy_check_mark:     | N/A                    | :heavy_check_mark:     |
