# Setup for Microsoft Windows

## Requirements

### IDE
* [Vistual Studio Code](https://code.visualstudio.com/download)
* [PyCharm](https://www.jetbrains.com/pycharm/download/)

* [Git](https://git-scm.com/downloads) (to install Git)
* [Github](https://github.com/)
* [Slack](https://slack.com/)
* [Jira](https://jira.atlassian.com/)
* [Node.js](https://nodejs.org/)
* [NVM](https://github.com/nvm-sh/nvm)
* [NPM](https://www.npmjs.com/get-npm)
* [Python 3.8.3](https://www.python.org/downloads/)

## Full setup

### Step 1:
Request permission through Joshua Liang for github, slack, and jira

### Step 2:
Clone the calisthantics-web repo
Each line is a separate command:

```
mkdir calisthantics-workspace
cd calisthantics-workspace
git clone https://github.com/LiangJoshua/calisthantics-web.git
```

Follow the README.md instructions to finish setting up calisthantics-web for development

### Step 3:
Clone the calisthantics repo into your calisthantics-workspace

```
git clone https://github.com/LiangJoshua/calisthantics
```

Follow the README.md instructions to finish setting up calisthantics for development

### Step 4:
Clone the devops-infrastructure repo into your calisthantics-workspace

```
git clone https://github.com/LiangJoshua/devops-infrastructure
```

## Directory Layout
This should be your final directory layout. If it doesn't match, you possibly made an error. Feel free to contact Joshua Liang for assistance. 

```
├── calisthantics-workspace/       # Parent app directory
│   ├── calisthantics/             # Python flask back end
│   ├── calisthantics-web/         # React front end
│   └── devops-infrastructure/     # Development and infrastructure setup instructions
```