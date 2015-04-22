_Note: This lesson is currently orphaned. People interested in taking a lead on further developing it are welcome to step forward. Post an issue expressing your interest and where you would like this to go, or file a pull request._

##Purpose
To teach students to VERB [and VERB] the way that organization can be used to inform themselves and others about the project throughout its life

##Motivation
Why is it worth organizing?
Graph Illustrating effort verse time. Yes, this is a little painful, but think of how painful it will be during publication process.

![graph]
(https://raw.githubusercontent.com/tracykteal/shell-genomics/master/img/gvng.jpg)

##Overview of exercises
1. get set of files (raw data, scripts, overall .Rmd) for gapminder all
  in one directory

  - raw data: `raw1.csv`, `raw2.csv`, `raw3.csv`
  - scripts to clean the data: `clean1.R`, ..., `clean7.R`
  - overall Rmd: `project.Rmd`

  Run the whole thing to produce clean data (`clean.csv`) and output
  files (`project.md`, `project.html`, `sweden.png`).

2. How to organize these files? Students work on this in small groups, to
   organize into subfolders (separating code from data).

   Come back together to discuss students' solutions; point them
   toward a modified version of Bill Nobel's approach.

        project.Rmd
        doc/paper/
        data/raw/raw1.csv
        data/raw/raw2.csv
        data/raw/raw3.csv
        data/clean/clean.csv
        code/clean1.R
        ...
        code/clean7.R
        results/project.md
        results/project.html
        results/figure/sweden.png

3. Discussion of paths, particularly regarding relative vs absolute paths.
      - what we had to change (paths) to redirect files
      - If you gave to friend how do those path names effect that?
      - importance of absolute vs relative paths
      - what if you were to move this to a new computer?
      - Working directory

4. Exercise: we need to do the actual moving around, and we need to

   - go into the `code/*.R` files and change the paths to the raw and
     clean data
   - go into the `project.Rmd` file to change the paths to `clean*.R`
     and `data/clean/clean.csv`.
   - change `project.Rmd` to send figure to `results/figure/`; change
     preferences for knitr to send output to `results/`.

  (Potentially skip this exercise and provide them with a reorganized
  version.)

5. Add some new analysis to the main Rmd file, and re-run.

6. metadata exercise: what metadata will you want to record in order to explain what files are what, and which ones produce which others
    - README file explaining everything

      - for yourself, coming back to this 6 months from now
      - for a collaborator

7. versions: how do they keep track of versions of things? (discussion in small groups and then come back together)

      - periodic zipping of project directory
      - Time Machine or other backup system
      - project on dropbox
      - github

8. (Lecture interlude: demonstration of GitHub)
