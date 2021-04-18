<div align="center">
  <a href="https://dagshub.com"><img src="https://raw.githubusercontent.com/DAGsHub/client/master/dagshub_github.png" width=600 alt=""/></a><br><br>
</div>

[![Discord](https://img.shields.io/discord/698874030052212737)](https://discord.com/invite/9gU36Y6)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![CI](https://img.shields.io/github/checks-status/jenkinsci/dagshub-branch-source-plugin/master)](https://ci.jenkins.io/job/Plugins/job/dagshub-branch-source-plugin/)
<a href="https://twitter.com/TheRealDAGsHub" title="DAGsHub on Twitter"><img src="https://img.shields.io/twitter/follow/TheRealDAGsHub.svg?style=social"></a>

# DAGsHub Branch Source Jenkins Plugin

Use <a href="https://dagshub.com">DAGsHub</a> repositories as sources for
<a href="https://www.jenkins.io/doc/book/pipeline/multibranch/">Jenkins Multibranch Workflow projects</a>.

After installing the plugin, when you create or edit a Jenkins multibranch project, you can select a 
DAGsHub repo as a branch source, which means you can trigger automatic builds for any git branch, tag 
or pull request in your repo, if they have an existing 
[Jenkinsfile](jenkins.io/doc/book/pipeline/jenkinsfile/).

## Installation
Install from Jenkins Update Center. Go to Jenkins > Configure > Manage Plugins > Available and search for DAGsHub branch source plugin then select Install.

## Release notes
[See the Github releases](https://github.com/jenkinsci/dagshub-branch-source-plugin/releases) for release notes.

---

Made with 🐶 by [DAGsHub](https://dagshub.com/).
