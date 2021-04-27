## My favorite  robot

  #### by zzs

My favorite of these robots is the white and flexible somersault humanoid robot: Atlas. 

*Because it has a head, torso and limbs like a human, the eyes are two stereoscopic sensors.*

  **Atlas has the function of being able to stand up when you fall down. It can well realize the control of the balance force**

~~the movement is more smooth, can make corrections according to the changes of the environment.~~

***************************************

  [Atlas](https://baike.baidu.com/item/%E9%98%BF%E7%89%B9%E6%8B%89%E6%96%AF/19287186?fromtitle=Atlas%E6%9C%BA%E5%99%A8%E4%BA%BA&fromid=16173573&fr=aladdin)

  [README.md](/README.md)

  ![Atlas](https://bkimg.cdn.bcebos.com/pic/574e9258d109b3ded9f78b07cbbf6c81800a4c10?x-bce-process=image/watermark,image_d2F0ZXIvYmFpa2U4MA==,g_7,xp_5,yp_5/format,f_auto)

  ![robot](/robot.jpg)







  ```c
  #include<stdio.h>
  int Ack(int m,int n)
  {
  	//printf("函数参数m=%d,n=%d\n",m,n);
  	if(m==0)
  		return n+1;
  	if(n==0)
  		return Ack(m-1,1);
  	if(m>0&&n>0)
  		return Ack(m-1,Ack(m,n-1));
  }
  int main(void)
  {
  	int m,n;
  	printf("请输入函数参数m,n: ");
  	scanf("%d%d",&m,&n);
  	printf("Ack(%d,%d)=%d \n",m,n,Ack(m,n));
      return 0;
  }
  
  ```

  

  * AAAAA
  * BBBBB
  * CCCCC

1. DDDDD
2. EEEEE
3. FFFFF
4. GGGGG

| A    | B    | C    |
| ---- | ---- | ---- |
| D    | E    | F    |
| G    | H    | I    |
