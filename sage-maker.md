## SageMaker

Jupyter notebooks can be run on a home computer but whenever we would like to run a very demanding jupyter notebook that needs a very powerful computer, we may run into limitations.

Fortunately though, the easiest soution is to use cloud computing in order to run those demanding jupyter notebooks.

For example, when we would like to process data consisting of tenths of thousands of entries, a home computer may either be too slow or incapable of processing those data.

Thus, one solution is to use AWS SageMaker. The easiset way to run SageMaker is to create a jupyter notebook and store it in a GitHub repository and then to start SageMaker by cloning that repository.

Depending on the processing power needed, we could choose the appropriate instance type to process our data. Obviously, the more powerful the instance, the more expensive it would be and so, we need to choose an instance type wisely in order to have a balance between the ideal processing power and the ideal billing.

