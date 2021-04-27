# Setup for macOS

## Requirements

### Xcode tools
```bash
xcode-select --install
```

### IDE
* [Vistual Studio Code](https://code.visualstudio.com/download)
* [IntelliJ](https://www.jetbrains.com/idea/download/#section=mac)

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
Clone the 40percent-web repo
Each line is a separate command:

```
mkdir 40percent-workspace
cd 40percent-workspace
git clone https://github.com/LiangJoshua/40percent-web.git
```

Follow the README.md instructions to finish setting up 40percent-web for development

### Step 3:
Clone the 40percent repo into your 40percent-workspace

```
git clone https://github.com/LiangJoshua/40percent
```

Follow the README.md instructions to finish setting up 40percent for development

### Step 4:
Clone the devops-infrastructure repo into your 40percent-workspace

```
git clone https://github.com/LiangJoshua/devops-infrastructure
```

## Directory Layout
This should be your final directory layout. If it doesn't match, you possibly made an error. Feel free to contact Joshua Liang for assistance. 

```
├── 40percent-workspace/       # Parent app directory
│   ├── 40percent/             # Python flask back end
│   ├── 40percent-web/         # React front end
│   └── devops-infrastructure/     # Development and infrastructure setup instructions
```
