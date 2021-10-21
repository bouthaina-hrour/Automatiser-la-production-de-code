# Automatiser-la-production-de-code

## I.MAKE

 1.Running a Makefile
 
  ![](screenes/a1.PNG? "Running Makefile")

 2.Makefile targets
 
   ![](screenes/a2.PNG)
   
 3.Makefile targets
 
   ![](screenes/a4.PNG)
   
 4.make clean
 
   ![](screenes/a5.PNG)
 
 5.Variables
 
   ![](screenes/variables2.PNG)
   ![](screenes/variables1.PNG)
 
 6.The all targets
 
   ![](screenes/all-2.PNG)
   
   ![](screenes/all-1.PNG)
   
 7.Multiple targets
  
   ![](screenes/multipletargets1.PNG)
   
   ![](screenes/multipletargets2.PNG)
   
 8.Multiple targets
  
   ![](screenes/multipletargets1.PNG)
   
   ![](screenes/multipletargets2.PNG)
 
 9.Automatic Variables
 
   ![](screenes/automatic-v1.PNG)
   
   ![](screenes/automatic-v2.PNG)
   
 10.Static Pattern Rules
     
   ![](screenes/staticpatternrules1.PNG)
   
   ![](screenes/staticpattern2.PNG)
   
 11.Command Execution
 
   ![](screenes/cmdexecution1.PNG)
   
   ![](screenes/cmdexecution2.PNG)
 
 12.Change Default Shell
 
   ![](screenes/change-default-shell.PNG)
   
   ![](screenes/changedefaultshell2.PNG)
   
 13.Recursive use of make
 
   ![](screenes/1.PNG)
   
   ![](screenes/2.PNG)
   
 14.Use export for recursive make
   
   ![](screenes/3.PNG)
   
   ![](screenes/4.PNG)
   
 15.Export variables to have them run in the shel
   
   ![](screenes/5.PNG)
   
   ![](screenes/6.PNG)
   
 16.Export all variables
   
   ![](screenes/7.PNG)
   
   ![](screenes/8.PNG)
   
 17.Flavors and modification
   
   - a.Recursive and simply expanded flavors of variables
 
   ![](screenes/9.PNG)
   
   ![](screenes/10.PNG)
   
  - b.Use simply expanded to append to a variable
 
   ![](screenes/11.PNG)
   
   ![](screenes/12.PNG)
   
   - c.Sets variables with ?= 
 
   ![](screenes/13.PNG)
   
   ![](screenes/14.PNG)

   - d.Make a variable with a single space
 
   ![](screenes/15.PNG)
   
   ![](screenes/16.PNG)
   
   - e.Undefined variables
   
   ![](screenes/17.PNG)
   
   ![](screenes/18.PNG)
   
   - f.Use += to append
   
   ![](screenes/19.PNG)
   
   ![](screenes/20.PNG)
   
 18.Command line arguments and override
 
   ![](screenes/21.PNG)
   
   ![](screenes/22.PNG)
 
 19.List of commands and define
 
   ![](screenes/23.PNG)
   
   ![](screenes/24.PNG)
   
 20.Target-specific variables
   
   ![](screenes/25.PNG)
   
   ![](screenes/26.PNG)
   
 21.Pattern-specific variables
   
   ![](screenes/27.PNG)
   
   ![](screenes/28.PNG)
    
 22.Conditional part of Makefiles
 
   - a.Conditional if/else
   
   ![](screenes/29.PNG)
   
   ![](screenes/30.PNG)
    
   - b.Check if a variable is empty
   
   ![](screenes/31.PNG)
   
   ![](screenes/32.PNG)
   
   - c.Check if a variable is defined
   - 
   ![](screenes/33.PNG)
   
   ![](screenes/34.PNG)
   
    - e.$(makeflags)
   
   ![](screenes/35.PNG)
   
   ![](screenes/36.PNG)
   
   
 23.Functions
 
   - a.First Functions
   
   ![](screenes/39.PNG)
   
   ![](screenes/40.PNG)
    
   - b.Replace spaces or commas
   
   ![](screenes/39.PNG)
   
   ![](screenes/40.PNG)
    
   - c.Do NOT include spaces in the arguments 
   
   ![](screenes/41.PNG)
   
   ![](screenes/42.PNG)
   
   - d.String Substitution
   
   ![](screenes/43.PNG)
   
   ![](screenes/44.PNG)
   
   - e.The foreach fuction
   
   ![](screenes/45.PNG)
   
   ![](screenes/46.PNG)
   
   - f.The if function
   
   ![](screenes/47.PNG)
   
   ![](screenes/48.PNG)
   
   - g.The call function
    
   ![](screenes/49.PNG)
   
   ![](screenes/50.PNG)
   
   
   - h.The shell function
    
   ![](screenes/51.PNG)
   
   ![](screenes/52.PNG)
   
  24.Other Features
    
   - a.Multiline
    
   ![](screenes/53.PNG)
   
   ![](screenes/54.PNG)
   
    
   - b..PHONY
    
   ![](screenes/55.PNG)
   
   ![](screenes/56.PNG)
   
   - c.Delete on error
    
   ![](screenes/57.PNG)
   
   ![](screenes/58.PNG)
  ## II.MAVEN 
  
  1-Create a projet
  
   ![](screenes/creatingproject.PNG)
  
  2-Build the Project
   
   ![](screenes/build.PNG)
   
  3-Clean a project
    
   ![mvnclean](https://user-images.githubusercontent.com/73646814/138285289-8ac53182-0caa-4818-bbf2-5c0935ab2cf6.PNG)
  
  4-Compile a project
    
   ![](screenes/butcompile.PNG)
   
  5-Package a project
  
   ![](screenes/mvnpackage1.PNG)
   
   ![](screenes/mvnpackage2.PNG)
   
  6-Test a newly compiled and packaged JAR
  
   ![](screenes/helloworld.PNG)
   
  7-Execute phases and goals in sequence
  
   ![](screenes/phasesinsequence.PNG)
 
  8-Clean and copy dependencies
 
   ![cleanandcopydependencies](https://user-images.githubusercontent.com/73646814/138290715-e0c7a819-1b81-42b1-b369-b3b434b4f1e4.PNG)

  
  9-Generating the Site
   
   ![](screenes/mvnsite.PNG)
   
   ![](screenes/siteofmyapp.PNG)
   
  10-Le plugin maven-help-plugin
 
   ![](screenes/mvnhelpeffectivepom.PNG)
   
   ![](screenes/ep1.PNG)
   
   ![](screenes/ep2.PNG)
   
  11-Le plugin maven-compiler-plugin
  
   ![](screenes/validatecompiletest.PNG)
   
  12-Packaage project into 4 jars
  
   ![](screenes/jars.PNG)
  
     a- JavaDoc jar
     
   ![](screenes/javadoc1.PNG)
   
   ![](screenes/javadoc2.PNG)
   
   ![](screenes/javadoc3.PNG)
   
     b- Sources jar
     
   ![](screenes/source1.PNG)
    
   ![](screenes/source2.PNG)
   
    c- Executable jar with dependencies
    
   ![](screenes/dependency1.PNG) 
   
   ![](screenes/dependency2.PNG)
   
   ![](screenes/dependency3.PNG)
   
   ![](screenes/dependency4.PNG)
   
   13- le pluging gpg sert à signer tous les artefacts attachés au projet avec GnuPG (GPG est l'acronyme de GNU Privacy Guard. Application qui permet le chiffrement et la signature de données.)
   - Son exécution est configuré dans la phase du déployement.
 
  
          
         
