# Jenkins Job Configuration
First, we will tell jenkins where the source code can be found.
Typically, jenkins is configured with some source code management like git-

1. Scroll down to the section 'Source-Code-Management'
2. Select 'Git'
3. In the text field Repositories type in the URL of the git project 'https://github.com/mrsarm/helloworld-c'
4. You do not have to alter the other options for 'Source-Code-Management'

5. Scroll down to 'Buildverfahren'
6. Setup 3 steps with 'run shell' as pointed out in the project readme https://github.com/mrsarm/helloworld-c
7. Hit 'Save'
