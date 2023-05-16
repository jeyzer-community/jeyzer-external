
------------------------------------------------------------------------------------------------
                            External profile repository
------------------------------------------------------------------------------------------------

Jeyzer access to this repository :

- The Jeyzer Web Analyzer will load external profiles from this directory in a developer environment

- The Jeyzer project Maven build will automatically assemble all these profiles into a jeyzer-profiles-external-${jeyzer version}.zip file.
  Zip file is generated in the jeyzer-dist/target/distribution directory.
  It will be up to you to deploy it in your runtime environment (R&D, QA, production...) 
  and reference it in the right variables (script, appserver profile root directories...).
  

