# Cloudera Data Science Workbench demos
Basic tour of Cloudera Data Science Workbench by Joep Muselaers 20190131


# Traininguser logins

- training01	3NRBFSBAz4BtSPWi
- training02	U3FaJWPxvNdiYJQn
- training03	2iLrbj3pYjD9XBBY
- training04	ShNqKSmec8RdK9BA
- training05	BvL7viqvCHemxE9o
- training06	FwjxW7nG8Q2JsWGc
- training07	bwh2PcNXX6bj6puz
- training08	FKzdNZwDz3hQwXZq
- training09	hW3LSDZyysyTfXC4
- training10	Mf9Yev7bcEyZtB6K
- training11	uHr9dHjVRoLw2sMt
- training12	sQNfhS2m8dm27KLA
- training13	HMJkG4xC6JPmbtrH
- training14	gew7KQCNXb7V2Z6V
- training15	bdpP3qSHevd3QgLn
- training16	twoFSvMcgwSWiTp7
- training17	HePMdw8Lou7RVcVY
- training18	47qEtYygx3xfABWN
- training19	3Rra37m2zCWFZnAN
- training20	ArRN2mUzujaurHkz


## Workbench
There are 4 scripts provided which walk through the interactive capabilities of Cloudera Data Science Workbench.

1. **Basic Python visualizations (Python 2).** Demonstrates:
  - Markdown via comments
  - Jupyter-compatible visualizations
  - Simple console sharing
2. **PySpark (Python 2).** Demonstrates:
  - Easy connectivity to (kerberized) Spark in YARN client mode.
  - Access to Hadoop HDFS CLI (e.g. `hdfs dfs -ls /`).
3. **Tensorflow (Python 2).** Demonstrates:
  - Ability to install and use custom packages (e.g. `pip search tensorflow`)
4. **R on Spark via Sparklyr (R).** Demonstrates:
  - Use familiar dplyr with Spark using [Sparklyr](http://spark.rstudio.com)
5. **Advanced visualization with Shiny (R)** Demonstrates:
  - Use of 'shiny' to provide interactive graphics inside CDSW
  
## Jobs
We recommend setting up a **"Nightly Analysis"** job to illustrate how data scientists can easily automate their projects.


## Setup instructions
Note: You only need to do this once.

1. In a Python 3 Session:
```Python
!pip3 install --upgrade dask 
!pip3 install --upgrade keras 
!pip3 install --upgrade matplotlib==2.0.0. 
!pip3 install --upgrade pandas_highcharts 
!pip3 install --upgrade protobuf 
!pip3 install --upgrade tensorflow==1.3.0.
!pip3 install --upgrade seaborn
```
Note, you must then stop the session and start a new Python session in order for all the packages to be seen.

2. In an R Session:
```R
install.packages('sparklyr')
install.packages('plotly')
install.packages("nycflights13")
install.packages("Lahman")
install.packages("mgcv")
install.packages('shiny') 
```

3. Stop all sessions, then proceed.

‹
