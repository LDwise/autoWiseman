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
1. [Download selenium](#process-user)
2. Get Name & Score (for display)
3. Get lessons link for loop
4. Into lesson link with offline network
5. Press "Submit" to get correct answear
6. Into leesson link with online network
7. input correct answear and submit to web server
8. redo step 3-7 untill all lessons finished
---
## Download selenium
download lastest installer
'!apt -q -qq update'\
download chromium chromedriver to use selenium successfully.
'!apt -q -qq install chromium-chromedriver'\
download selenium of python
'!pip -q install selenium'

- Login
  - Into [Login](https://lms.wiseman.com.hk/lms/user/) page
  ![Ayfe.png](https://i.qpix.com/2020/12/14/Ayfe.png)
  - Input Username and Password
  ![Ayt3.png](https://i.qpix.com/2020/12/14/Ayt3.png)
  - Press Login buttom
  ![Aytk.png](https://i.qpix.com/2020/12/14/Aytk.png)
- Lessons list
###### Program by a high school student.
