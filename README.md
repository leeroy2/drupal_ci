# drupal_ci (PHING)

Info:
build.xml is a build file for PHP (PHING) which checks PHP files for possible syntax errors. If files are OK then it simply copies over SSH the files under ${drupal.root.dir}/sites/all
to the remote machine

Instructions:
In order to deploy drupal websites please create prd.properties and (or) test.properties and fill in the missing property values from the initial build.xml file.
build.xml file should be at ${drupal.root.dir} of your repo.
