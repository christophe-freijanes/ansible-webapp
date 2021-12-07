# ansible-webapp
- Repository ansible-webapp of training deployment with role ansible
- This playbook will allow to deploy on two client servers an apache2 container containing a web site.

- For deploy the webapp, run this command:
```sh
ansible-playbook -i hosts.yml -vvv play-deploy-webapp.yml --tags "webapp"
```
- Command-line ansible tag
```sh
--tags all - run all tasks, ignore tags (default behavior)
--tags [tag1, tag2] - run only tasks with either the tag tag1 or the tag tag2
--skip-tags [tag3, tag4] - run all tasks except those with either the tag tag3 or the tag tag4
--tags tagged - run only tasks with at least one tag
--tags untagged - run only tasks with no tags
```