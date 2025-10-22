## Generating Ideas:
* Duolingo CSC207 game
* three main minigames: connections, crossword, multiple choice
* Connections will be by api, crossword by self implementation, multiple choice with database or json file whatever
* possibly create a leaderboard system afterwards


### Program Structure Ideas
#### UI
JavaFX + CSS + some open-source components
+ view (Controller)
+ componentenes (Progress Ring, Streak Bar etc.)
+ states (current course/ level)
+ assets (css, icons, sounds)

#### Data
+ repository (CourseRepository, QuestionRepository, ProgressRepository...)
+ datasource (JsonCourseDataSource, CacheDataSource, LocalFS)

#### App
+ Main.java

#### engine
+ question types (MCQ, connections, crossword)
+ JudgeStrategy (validator)
+ scheduler (make quiz, do review)
