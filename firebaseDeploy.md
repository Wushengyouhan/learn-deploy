1. 登陆firebase，点击右上角Go to console

   https://firebase.google.com/docs/hosting

2. 创建项目‘

   ![image-20250108175014213](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108175019765.png)

3. 关闭谷歌分析，点击创建项目

   ![image-20250108175059269](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108175059325.png)

4. 等待项目创建完成，点击继续

5. 点击 构建-hosting

   ![image-20250108175349479](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108175349549.png)

6. 点击 开始使用

   ![image-20250108175556706](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108175556796.png)

7. 按照教程来，下面是一个例子。

8. 在项目目录下执行

   ```
   npm install -g firebase-tools
   ```

9. 运行firebase login 指令需要开启全局代理和命令行代理，且代理的地点可能会有影响。这次选的泰国。

   ![image-20250108193221068](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108193221123.png)

​	在命令行执行从clashX复制的终端代理命令, 然后执行 ```firebase login```，在浏览器中验证

​                ![image-20250108193350372](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108193350442.png)

![image-20250108193503853](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108193503949.png)



10. 执行初始化命令

    ```
    firebase init
    ```

    ![image-20250108194221691](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108194221763.png)

11. 下面是一些配置项

    ![image-20250108194313775](https://wushengyouhan-note.oss-cn-wuhan-lr.aliyuncs.com/img/20250108194313874.png)

12. 执行部署命令

    ```
    firebase deploy
    ```

    

![image-20250108195428617](/Users/chenchen/Library/Application Support/typora-user-images/image-20250108195428617.png)

13. 如果出错了，就切换代理的位置，重试一下，最后部署的时候，我把节点切到了香港。