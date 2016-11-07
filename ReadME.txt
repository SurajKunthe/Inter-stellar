Steps to run Tests from the command prompt

1.Open command prompt and type cd\ and press Enter.

2.Now go to project home directory, for this type cd /d directory path and Enter.

3.Now we can set classpath, for this specify bin folder i.e ( set classpath=directory path\bin;) and Enter.

4.Now,Run xml file using below command: (In my case - "testng1.xml" and "jarfiles" - name of the folder containing all jar files) and Enter.
  
  java -cp bin;jarfiles/* org.testng.TestNG testng1.xml 