## SageMaker

Jupyter notebooks can be run on a home computer but whenever we would like to run a very demanding Jupyter notebook that needs a very powerful computer, we may run into limitations.

Fortunately though, the easiest soution is to use cloud computing in order to run those demanding jupyter notebooks.

For example, when we would like to process data consisting of tenths of thousands of entries, a home computer may either be too slow or incapable of processing those data.

Thus, one solution is to use AWS SageMaker. The easiset way to run SageMaker is to create a Jupyter notebook and store it in a GitHub repository and then to start SageMaker by cloning that repository.

Depending on the processing power needed, we could choose the appropriate instance type to process our data. Obviously, the more powerful the instance, the more expensive it would be and so, we need to choose an instance type wisely in order to have a balance between the ideal processing power and the ideal billing.

By default, only the basic instance types are available and thus, in order to use a more powerful instance type we need to request an instance type increase by submiting the appropriate request to the AWS customer support.

## Machine Learning and Deep Learning using SageMaker

Jupyter Notebooks can also be used to train a machine learning or a deep learning model using SageMaker.

For faster training, there are also GPU instances available, while the ml.p2.xlarge is the smaller available GPU instance.

In case someone prefers to rather use CPU training, then the recomened instance types are:

* ml.c4.2xlarge
* ml.c5.2xlarge

CPU training though, would take more time for a model to be trained.

Obviously the choise would also depend on the kind of data we are using to create our machine learning or deep learning model.

