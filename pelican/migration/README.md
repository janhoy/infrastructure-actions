# Migrating from Infrastructure Pelican to GitHub Actions

## Migration instructions
https://cwiki.apache.org/confluence/display/INFRA/Moving+from+Infrastructure-pelican+to+GitHub+Actions

## Template and GHA Workflow file
The build-pelican.yml.ezt and pelican.auto.ezt templates in this directory are used by the generate_settings.py script. 
The build-pelican.yml workflow may be used directly by projects wishing to use the pelican workflow.

## Updating the workflow

Before using the workflow file, ensure that the source and target branches are correct. otherwise you *could* commit to a production branch
