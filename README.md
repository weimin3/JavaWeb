# JavaWeb
Notes
## 1. 基础回顾
### 1.1 Junit单元测试
测试分类：
- 黑盒测试：给输入值，看是否输出期望值
- 白盒测试：关注程序具体执行流程。Junit

Junit使用：白盒测试
* 步骤：
  1. 定义一个测试类(测试用例)
  - 建议：
       - 测试类名：被测试的类名Test
       - 包名：xxx.xxx.xx.test
  2. 定义测试方法：可以独立运行
  - 建议：
      - 方法名：test测试的方法名
      - 返回值：void 
      - 参数列表：空参
  3. 给方法加@Test
  4. 导入Junit依赖环境
* 判定结果：
  * 红色：失败
  * 绿色：成功
  * 使用断言操作处理结果。```Assert.assertEquals(expected result,actual result)```

@Before & @After
* 初始化方法：用于资源申请，所有测试方法在执行之前都会先执行该方法。即执行之前 @Before
* 释放资源方法：在所有测试方法执行完后，都会自动执行该方法。即执行前：@After


### 1.2 反射

### 1.3 注解




## 1. 数据库

## 2. 前端

## 3. web核心
## 4. 项目

## 5. SSM框架： 简化web开发的经典框架

## 6. SpringBoot:
## 7. SpringCloud