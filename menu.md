## 点击菜单键出现的时选项菜单OptionMenu
1. 覆盖Activity的onCreateOptionMenu(Menu menu)方法，当菜单第一次打开时调用。
2. 调用Menu的add()方法添加菜单项（MenuItem），同时可以调用MenuItem的setIcon（）方法来为菜单设置图标
3. 当菜单项（MenuItem）被选择时，覆盖Activity的onOptionsItemSelected（MenuItem item）来响应事件
4. action bar 
