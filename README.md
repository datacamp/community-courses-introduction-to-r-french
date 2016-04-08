## Introduction to R in French: Introduction à R

The French statistician and R trainer [Vincent Guyader](vincent@thinkr.fr) has translated the original introduction to R course ([GitHub](www.github.com/Data-Camp/introduction_to_R)) to French. This repository contains all the source files, in French, that correspond to the course that is live on DataCamp.

```R
# get latest version of datacamp
library(devtools)
install_github("datacamp/datacamp")

# upload all chapters
library(datacamp)
datacamp_login("french@datacamp.com", "pass", "")
upload_course(upload_chapters = TRUE, open = FALSE)
```

