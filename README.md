# PTexture

A package to compute a total of 261 texture features from voxel lists.

## News

* 11/21/2018. An option to skip tests is implemented. By default, tests are skipped. If you do want to test, set 'do_test' variable to True at the top of the code.
* 9/9/2018. ZLNU is renamed to ZSNU standing for zone-size non-uniformity.
* 9/9/2018. Test codes are added for robustness.


## How to use

1) If you are not at https://github.com/metavol/ptexture, please go there.

2) Click the green button 'Clone or download' and then click 'Download ZIP'

3) Save the zip on your computer anywhere

4) Extract the zip

5) Create a folder such as 'my_data' on the top level of extracted folder (same level as testdata1, testdata2)

6) Copy your voxel data ('case1.txt' for example) to the above created folder.

7) Run Jupyter Notebook or Jupyter Lab

8) Open 'ptexture_with_text.ipynb'

9) 'Edit' menu -> 'Clear All Outputs'

10) Go to the bottom of the source code

11) Find the this line in the bottom box:

df = superBatch(directory = r'testdata1', dim = 3, nbin = 64, lo = 0, hi = 20, connection = 26, ngldm_mode = 1, full = False, report_progress = True, column_renamer = None)

12) Change 'testdata1' to your folder name that was created in 5)

13) 'Run' menu -> 'Run All Cells'

14) If successfully done, an excel file is created.

If any errors occure, please contact Kenji Hirata.


Kenji Hirata, MD, PhD

Hokkaido University, Sapporo, Japan

khirata@med.hokudai.ac.jp
