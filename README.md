<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>
# machine-learing
## INTRO：
  - linearRegression
    - 线性回归
	    - TAG：监督学习，回归算法，线性算法
	    - 优化算法：1）最小二乘法；2）梯度下降法
    - 文件夹中包含了以下文件：LinearRegression.py;LinearRegression_least_square_method.py;LinearRegression_scikit-learn.py;data.txt;data2.txt
		- LinearRegression.py:实现了一个简单的线性回归类，优化算法使用梯度下降法，模型训练完后，可以查看模型参数、模型训练中的损失值、一元特征样本的样本与模型比照图；还有用于预测的predict类方法。
		- LinearRegression_least_square_method.py：使用最小二乘法实现一遍线性回归，这里时使用函数型式，并没有创建类。
		- LinearRegression_scikit-learn.py：使用sklearnz库中现有的模型模拟了一边其中线性回归类的使用方法。
		- data.txt、data2.txt：自己随意创建的样本集，data样本中只有一个特征、data2样本中又两个特征。
  - logisticRegression
    - 逻辑回归
    - TAG：监督学习，分类算法，线性算法
    - 优化算法：梯度下降法
    - $$ x=y$$
