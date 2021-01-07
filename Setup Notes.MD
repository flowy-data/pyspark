## How to setup your environment.


Mac OS specific

#### Install Homebrew

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

#### Install Using Brew
```
brew install java
brew install scala
brew install apache-spark
```

 #### Add this to .zshrc or .bashrc
```
#spark
export SPARK_HOME=/usr/local/Cellar/apache-spark/3.0.1/libexec           
export PATH="$SPARK_HOME/bin/:$PATH"
```

#### Test the install
`spark-shell `

#### Create Python Environment
```
conda create -n spark python=3.8
# install pyspark
pip install pyspark
```
