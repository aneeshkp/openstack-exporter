# openstack-exporter
OpenStack Exporter for Promethues using gophercloud client



[![Build Status](https://travis-ci.org/redhat-nfvpe/openstack-exporter.svg?branch=master)](https://travis-ci.org/redhat-nfvpe/openstack-exporter) [![Go Report Card](https://goreportcard.com/badge/github.com/redhat-nfvpe/openstack-exporter)](https://goreportcard.com/report/github.com/redhat-nfvpe/openstack-exporter)

## Note about development
- go to https://github.com/redhat-nfvpe/openstack-exporter and fork it to
  your account
- Now in your environment run
  - `go get github.com/redhat-nfvpe/openstack-exporter`
- and Navigate to the top level of the repository  openstack-exporter
  ```
  cd to openstack-exporter
  ```

- Rename the current origin remote to upstream
  - `git remote rename origin upstream https://github.com/yourname/openstack-exporter.git`
- From here, the best approach would be to create a feature branch and work from there.
   ```
   git checkout -t -b new-feature
   // create new feature commits
   git add files
   git commit -m "message"
   git push origin new-feature
   ```
- Don’t forget to pull the changes from upstream before sending in a PR. This
  helps avoid merge conflicts.
  ```
  git fetch upstream
  git merge upstream/master
  ```

- To Update your fork with upstream/master
  ```
  git push origin/master
  
  ```
