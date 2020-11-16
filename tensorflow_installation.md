# Tensorflow Installation

In order to install Tensorflow a virtual enviroment has to be created.
We use the virtualenv library in order to do so, it is preintalled with python3.

```bash
python3 -m virtualenv venv
```

After installing the virtual environment we need to activate in order to install packages in it.
In order to do so you can run the following command.

```bash
source venv/bin/activate
```

We can confirm that the virtual enviornment is open by the tag *venv* appearing to the left.
Now we can install Tensorflow on the virtual environment, however we have to prevent it from caching.
To do so we intall it with the following command.

```bash
mkdir /scratch/nas/num/username/.cache
pip install --cache-dir=/scratch/nas/num/username/.cache --build=/scratch/nas/num/username/.cache tensorflow
```
