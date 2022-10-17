+ 通常有三种基本的创建交互式Windows应用程序的方式：
  + 使用 Windows API 来进行开发
  + 使用 MFC 来进行开发
  + 使用 Windows Forms



+ c++引以为豪的执行效率与生俱来，配上Windows API能直接与操作系统打交道的高效率特性，强强联合，
再配上能直接与显卡打交道的图形库（DirectX或者OpenGL），这样，在Windows平台上编写游戏的铁三角配置就诞生了。

+ MFC就是一组封装了 Windows API 的 C++ 类而已。
说到底，MFC 还得依靠 Windows API，而且它比 Windows API 高层，也就是说 MFC 跑起来必定会比 Windows API 多走一段路，
这就注定了 MFC 的效率不如 Windows API。
由于 MFC 有底层代码的隐蔽性等特点，且 MFC 毕竟封装了很多实际上没用到的东西，不利于游戏开发的效率和游戏的运行速度，不适合做游戏开发。
MFC 做游戏地图编辑器之类的工具软件倒是比较适合。

+ API——应用程序编程接口
+ SDK——软件开发包
