mvn-site-docs
===================

Example project to generate documentation with maven

Maven configuration to make:

 - Site docs with custom style sheet CSS
 - Javadoc, with custom style sheet CSS
 - UmlGraph to javadoc
 - Maven Dashboard plugin
 - Cobertura Maven plugin
 
 Instructions
 -----------------------------
 1. mvn clean site
 2. mvn site:stage
 
 to build at one by one:
 1. mvn javadoc:javadoc
 2. mvn cobertura:cobertura
 3. mvn site:site -DskipTests=true
 4. mvn site:stage
 