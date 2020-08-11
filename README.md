# pipeline-template-catalogs

Full details can be found https://docs.cloudbees.com/docs/admin-resources/latest/pipeline-templates-user-guide/setting-up-a-pipeline-template

Create a github credential with an id of ```githubcreds```

Note: github needs secret text type credential

To upload ```java -jar jenkins-cli.jar -auth admin:<token> -s https://<master url> pipeline-template-catalogs --put < catalog.json```

To download ```java -jar jenkins-cli.jar -auth admin:<token> -s https://<master url> pipeline-template-catalogs > catalog.json```