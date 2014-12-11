Purpose: To teach students to VERB [and VERB] the way that organization can be used to inform themselves and others about the project throughout its life

Motivation
Why is it worth organizing?
Graph. Yes, this is a little painful, but think of how painful it will be during publication process. 

Overview of exercises:
- get a bunch of files (raw data, scripts, overall .Rmd): run the whole thing to produce clean data and output files
- now have a bunch of files (raw and clean data, scripts, results); how to organize them?
    - README file explaining everything
    - organize into subfolders (separating code from data)
- Potentially: have them actively reorganize and change paths
- get a version with files reorganized; add some new analysis to the main Rmd file
- (Lecture interlude: 
      - what we had to change (paths) to redirect files
      - importance of absolute vs relative paths
      - what if you were to move this to a new computer?)
- metadata exercise: what metadata will you want to record in order to explain what files are what, and which ones produce which others
      - for yourself, coming back to this 6 months from now
      - for a collaborator
- versions: how do they keep track of versions of things? (discussion in small groups and then come back together)
  Discussion of 3 main options:
      - periodic zipping of project directory
      - Time Machine or other backup system
      - project on dropbox
      - github
- (Lecture interlude: demonstration of GitHub)      

Activity
1. Organize old directory (move data into separate folder)
2. Re-run analysis: doesn't work
3. How do you fix it
    -  absolute vs relative paths / working directory
4. Now we need to add another analysis
5. What is the protocol for starting a new analysis
    -  document analysis change readme.md
    -  understand where the outputs should be 
    -  how we got them in the right places 
    -  absolute vs relative paths / working directory
    -  If you gave to friend how do those path names affect that?
    - How long will it take for you to figure your analysis 6 months from now?

