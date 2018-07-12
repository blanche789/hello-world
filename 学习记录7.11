# hello-world
Test-hello world！
Blanche！
- Test
  - test2
## 数组的排序
- Arrays类（隶属于java.util）
    - sort(int[ ] a) 排序方法
    - fill()  填充方法
    - binarySearch(int []a,int key)  二分法找寻所需值
    - System.out.println(Arrays.toString(value));打印数组
    
    - Tips:以上方法均可通过遍历来实现


- **命令行参数(String[] args)**
    - 通过Run as来填充args


- **for加强**

            for(int i : a) 
            {
                System.out.println(i);
            }

- **包装类(wrappclass)**
    - 类型
        - Integer
        - Character
        - Long
        - Short
        - Doublie
        - Float
        - Boolean
        - Byte
    
    - Tips: 
     包装类既将基本数据类型转化为对象,作为对象,可以调用许多便捷的方法
    - Example:
    
          a.toHexString(500);
          a.doubleValue();
          a.parseInt("985");

- **自动装箱和拆箱**
    
      Integer a = 1000;  //Integer a - new Integer(1000);
      int c =new Integer（1000）;  //int c = new a.intvalue;

- **Date类**(从1970.1.1的0点开始计算,通过毫秒计算)
    - 常用的方法
        - setTime(value);
        - getTime();
        - before(Date when)

- DateFormat类（实现字符串与时间的转换，子类为SimpleFormat，位于java.text包中）
    
		Date a = new Date(1234123412342L);
		DateFormat df = new SimpleDateFormat("yyyy-M-d");
        String str1 = df.format(a);
            
        String str2 = “1999-7-10”；
        DateFormat df2 = new SimpleDateFormat（“yyyy-M-d”）；//与字符串的格式对应
        Date b = df2.parse（str2）;


-   calendar类(子类GregorianCalendar)
    - 作用:用来对日期更好的转换
    - 常用的方法有:
        - Calendar d = new GregorianCalendar();
        - d.set(year,month,dateofmonth);
        - Date c = d.getTime();
        - d.add(Calendar.Year,30); //在年上增加30个月
        

-  **异常**
    - 一个图
     
        ```
        graph TB
        
        A(throwable) --> B(error)
        A(throwable) --> C(Exception)
        C(Exception) --> D(RunTimeException)
        C(Exception) --> E(OtherException)
        
        ```
    
    - 五个关键字
        - try、catch、finally、throws、throw
    
    - 在捕获的时候先捕获小的，再捕获大的
    
    - 异常和重写的关系
        - 继承的类的重写的方法必须抛出与基类中方法一样的异常类型或者不抛出异常

- File类
    - 类的说明：File类是用来查看文件或者创建文件的
    - 常用的方法以及静态字符串：
        - File.separator -->在windows系统是\,在linux系统是/
        - File f = new File(directory, file);
        
                    		if(f.exists()) {
        			System.out.println("文件路径:" + f.getAbsolutePath());
        			System.out.println("文件大小:" + f.length());
                    }else {
        			f.getParentFile().mkdirs(); //这里必须调用mkdirs的方法,因为文件多个目录
        			try {   //属于IOException,须抛出异常
        				f.createNewFile();
        			} catch (IOException e) {
        				e.printStackTrace();
        			}
        		}
