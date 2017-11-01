# NerdLauncher
 >Android编程权威指南第23章项目

###解析隐式intent
1. [Intent.ACTION_MAIN](http://blog.csdn.net/hanghangaidoudou/article/details/6419152)
2. packageManager.queryIntentActivities:查询手机上所以的MAIN activity
3. 利用ResolveInfo.loadLabel()方法，对字母顺序进行排序
4. ResolveInfo类
5. ActivityInfo中可以获得activity的包名和类名

###显示intent
1. 设置intent的setClassName来设置包名和类名来创建一个显示的intent
2. 设置intent.addFlags()标志
3. Intent.FLAG_ACTIVITY_NEW_TASK控制每个activity仅创建一个任务
