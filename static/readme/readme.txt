环境：  Python3.x    django

实现：对日志数据的可视化
	
思路：1. 对原数据进行结构化
          2. 将结构化数据存储进数据库
          3. 查询出path的种类
          4. 查询出每个path出现的次数
          5. 对数据处理成我们想要的比例关系
          6. 使用matplotlib进行数据的可视化
          7. 将使用数据绘制的图，保存在static/imgs/data.png中
          8. 在视图函数中将图片的绝对路径拼接，发送给前端
          9. 浏览器将路径渲染成图片，形成数据的分析及可视化