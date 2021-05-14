# css 总结
many
面试题总结

1.border加渐变边框
  border: 2px solid;
  border-image: linear-gradient(90deg, rgba(0,198,255,0), rgba(0,198,255,1), rgba(0,198,255,0)) 20 20;
  ![image](https://user-images.githubusercontent.com/47661092/118213398-6fe55680-b4a0-11eb-9569-2b6bdbda0c4a.png)
  
2.平行四边形
  transform:skew(20deg);
  解决内部其他样式变形，
  再加div设置transform:skew(-20deg);
  
3.border 加阴影
  套个div设置box-shadow: 0px 0px 20px #ff0000;
  然后再设置
