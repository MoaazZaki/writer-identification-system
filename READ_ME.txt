#The Trainer
[Includes all the developed modules, previous trials, visualizations, and accuracy on the training set.]
*Run me instructions* 📋
1-You don't need to run the very first cell if you don't use google colab. (It's only for mounting the google drive)
2-In the Essentials section. You need to change the following paths to the directory where you keep 
the training images:
✔PATH_TO_A_D
✔PATH_TO_E_H
✔PATH_TO_I_Z
3-There is also another path you need to change which is to something we have generated. A file called 
file_author.csv is included in this folder.
✔PATH_TO_AUTHOR
4-You should run each section by order till the validation and accuracy section. All the sections after this one are
either cells we needed to run only once to generate things to facilitate our work or prevoius trials that are no longer 
included in the final pipline.
*Packages you might need to pip install* 🛠
-->cv2
-->matplotlib
-->numpy
-->pandas
-->itertools
-->skimage
-->seaborn
-->sklearn
-------------------------------------------------------------------------------------------------------------------------------------------------
#The Tester 
[Only includes the necessary code to run the test cases]
*Run me instructions* 📋
1- You need to change the following path to the directory where you keep the -->data folder<--
✔PATH_TO_TEST_FOLDER
2-The last cell generates two files in PATH_TO_TEST_FOLDER:
a) results.txt
b) time.txt
*Folder hierarchy*🖥
>PATH_TO_TEST_FOLDER
    results.txt
    time.txt	
    >data
        >01
            >1
            >2
            >3
            test.png
        >02
         .
         .
*Packages you might need to pip install* 🛠
-->pathlib
-->os
-->time
-->cv2
-->numpy
-->pandas
-->itertools
-->skimage
-->sklearn