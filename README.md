# SVM支持向量機 support vector machine
 
如何分辨橘子跟蘋果? SVM可以分辨出最極端的個體，再根據極端的個體來分類。	
![image](https://github.com/egroeglee/pictures/blob/master/SVM/1.png)

範例: 與Logistic regression相同

![image](https://github.com/egroeglee/pictures/blob/master/SVM/2.png)

Confusion Matrix:
![image](https://github.com/egroeglee/pictures/blob/master/SVM/3.png)

	與logistic Regression的相差不大

Output: 用SVM(Linear)來畫線

![image](https://github.com/egroeglee/pictures/blob/master/SVM/4.png)
	 

# Kernel SVM 曲線平滑劃分

前言:當資料無法用簡單的線性來分類時(分線性可分)，可以用K-SVM來處理。
![image](https://github.com/egroeglee/pictures/blob/master/SVM/5.png)

![image](https://github.com/egroeglee/pictures/blob/master/SVM/6.png)

	這次的Kernel設定為高斯
 ![image](https://github.com/egroeglee/pictures/blob/master/SVM/7.png)
 
	更多的參數可用
 ![image](https://github.com/egroeglee/pictures/blob/master/SVM/8.png)
 
Confusion Matrix:
 ![image](https://github.com/egroeglee/pictures/blob/master/SVM/9.png)

Output: 高斯
![image](https://github.com/egroeglee/pictures/blob/master/SVM/10.png)
 
 
 可以看出不同的核(Kernel)對於結果的圖像有不同的結果
