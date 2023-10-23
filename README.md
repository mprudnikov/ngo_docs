# Bears On Boards Report Command-Line Tool

## Mac OS X Usage

The Report Command-Line Tool (CLI tool) is a Python script that generates the Survey and Survey Appendix Word docs based on a Qualtrics ID supplied as an argument. Once the CLI tool is installed, it can be run from a terminal like so:

```
python3 ./reports_cli.py -s <Qualtrics ID>
```

### Installation Steps

1. Install Brew package manager
2. Install Python interpreter using Brew
3. Download The CLI tool
4. The CLI tool is ready!

   
#### Installing Brew Package Manager
In the Terminal App run the following line:
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
Reopen the Terminal App and run the following command to make sure we have the latest package references:
```
brew update && brew upgrade
```

#### Installing Python and Dependencies Using Brew
Install Python by running the following command in the Terminal:
```
brew install python
```
Besides installing Python, Brew also installs `pip` package manager, which we will use in the next step:
```
pip3 install docxtpl QualtricsAPI
```
