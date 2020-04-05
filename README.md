![readme](docs/header-image.png)

# **AWS Tutorials**
An overview and how to on some of the most popular cloud computing services availble. Use them by themseleves or part of a larger system. They take care of most of the hard stuff.

## **Getting Started**

#### **1. Install Anaconda**


#### **2. Clone this Repo**
After installing Anaconda create a folder and clone this repository to grab the files you will need to follow along.

```bash
cd ~ && cd desktop && mkdir aws-tutorial
git clone https://github.com/meads2/AWS-Demo.git
ls
```

#### **3. Install Dependencies**
Now that you have the files installed, you will create an identical enviornment as me using conda env.yml file containing my envionment specs.

```bash
conda create -f env.yml
python -m ipykernel install --name aws-tut
conda activate aws-tutorial
```

#### **4. Set AWS Vars**
To use AWS you are going to need to set your own credentials to your account. In this tutorial we are going to be using the US-East-1 Region and AZs as they have most services. Feel free to choose whichever you would like as these services are almost globally available.

```bash
export AWS_CLIENT_ID='YOUR_AWS_CLIENT_ID'
export AWS_SECRET_KEY='YOUR_AWS_SECRET_KEY'
export AWS_REGION='us-east-1'
export
```

#### **5. Launch Jupyter Lab**
Now that everything is setup you can launch Jupyter Lab and start going through the tutorials in the folder.

```bash
jupyter lab
```
