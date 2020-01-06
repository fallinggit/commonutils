# commonutils
### 常用工具帮助类
- base包下：
   - ArrayUtils    数组操作工具类
   - CollectionUtils 集合操作
   - DocumentUtils 文档操作
   - RegexUtils 正则操作
   - StringUtils 字符串操作
   - RandomUtils 随机操作
   - BaseTypeUtils 类型之间转换
   - ClassHelper 类转换工具
   - ConvertDateUtils 转换日期工具类
   - IdcardUtils 身份证识别工具类
   - MoneyUtils 钱处理工具类
   - clone  克隆对象
      -  CloneUtils 克隆工具类
   - date   时间转换
      -  DateFormatUtils 日期时间转换工具类
      -  DateUtils 日期转换工具类
      -  TimestampUtils 时间戳转换工具类
   - encrypt 加密解密
     -  AESUtils AES加密工具类
     -  Base64Utils BASE64加解密工具类
     -  DESUtils DES加解密工具类
     -  EncryptAndDecryptUtils 加解密工具类
     -  MD5Utils MD5加密
   - file    文件操作
     -  FileUtils 文件工具类
     -  ZipUitls 文件压缩工具类
   - image   图像处理
     -  ImageUtil 图像处理工具类
   - math    数学操作
      - BigDecimalUtils 大数计算工具类
   - sensitiveword 敏感词操作
      - SensitiveWordFilterUtil 敏感词过滤工具类
      - SensitiveWordInit 初始化敏感词库
   - sequence   生成唯一序列
      - GenerateSequenceUtils 生成唯一时间序列
   - sort        排序
      - BinarySearch 二分查找
      - BubbleSort 冒泡排序
      - QuickSort  快速排序
      - SelectSort 选择排序
   - beanconvert  bean的转换
      - BeanMapConvert Bean与Map的转换
   - database     数据库操作
      - jdbc
        - ConnectDatabase 连接数据库
      - redis
        - RedisSaveListDemo redis保存链表工具类
        - RedisSaveObjectDemo redis存储对象
   - function     function操作
        - function 方法
           - FunctionOperatorDemo function操作
           - FunctionSupplierDemo suplier操作
        - generics 泛型使用
           - GenericsClassTestDemo 泛型例子
        - javalinux java调用scp命令
           - scpTestDemo java操作scp
        - streamdemo stream测试例子
          -  ListDemo List类操作
          -  ListGroupByDemo list分组操作
   - treetool  生成二叉树工具
        - TreeTool 二叉树生成工具
   - stream       jdk8流操作
     - IntStreamUtils   int流工具类操作
     - IntArrayStreamUtils int数组流工具类
- algo包下
   -  astar  A*算法
   -  dijkstra  迪杰斯特拉算法
   -  tsp  旅行商问题
   -  ortools 线性规划工具
   -  topK    topk算法
