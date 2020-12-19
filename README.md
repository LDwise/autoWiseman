# autoWiseman (with [Google Colab notebooks](https://colab.research.google.com/github/LDwise/autoWiseman/blob/main/autoWiseman.ipynb))
Automatically complete [EB Wiseman](https://wiseman.com.hk) lessons with full marks.\
Using **Python** with **selenium** pakeage.

---
## Root
A method to get total scores.
- open a page for get all answear on offline network
- open another page for input answaer on online network\
watch a [video](https://youtu.be/xcrjj_qhfiU) to learn it.
---
## Step
1. [Download selenium](#download-selenium)
2. [Into Wiseman Lessons list](#into-wiseman-lessons-list)
3. [Get lessons link for loop](#get-lessons-link-for-loop)
4. [Into lesson link with offline network & Press "Submit" to get correct answear](#get-correct-answear)
5. [Into leesson link with online network & input correct answear and submit to web server](#submit-correct-answear)
6. redo step 3-7 untill all lessons finished
---
## Download selenium
- Download lastest installer`!apt -q -qq update`
- Download chromium chromedriver to use selenium successfully`!apt -q -qq install chromium-chromedriver`
- Download selenium of python`!pip -q install selenium`
## Into Wiseman Lessons list
Login
- method 1
 - Into [Login](https://lms.wiseman.com.hk/lms/user/) page
 - Input Username and Password
 - Press Login buttom
 ![Aytk.png](https://i.qpix.com/2020/12/14/Aytk.png)
- method 2
 - Into `https://lms.wiseman.com.hk/lms/user/login.do?username=%s&password=%s` page & input Username and Password
Into Lessons list page
 - Into `https://lms.wiseman.com.hk/lms/user/secure/course/eb/select_theme/lessons.shtml` [EB Level 1](https://lms.wiseman.com.hk/lms/user/secure/course/eb/select_theme/lessons.shtml) page
## Get lessons link for loop
## Get correct answear
## Submit correct answear
###### Program by a high school student.
