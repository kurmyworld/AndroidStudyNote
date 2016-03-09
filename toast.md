# Toast
- Toast.makeText(context,显示内容,显示时间)
  - context可以是Activity的实力或者getApplicationContext()得到
  - 时常一般用两个Toast的常量
- ### 显示文本
```java
 Toast.makeText(this,"Message",Toast.LENGTH_LONG).show();
```
- ### 显示图片
```java
  Toast t = new Toast(this);
  ImageView imageView = new ImageView(this);
  imageView.setImageResource(R.drawable.photo4);
  t.setView(imageView);
  t.show();
```
