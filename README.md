# cloud-native-yeah

## What is Cloud-Native?
## Infrastructure
- Pros:
  - Scalable
  - Portable
  - Collaborative
  - Restarts (if you stuff up!)
- Cons:
  - Cost?
  - Local data?
  - Where to host data?
  - Environmental consideration - cloud compute vs. local machine footprint?

## GitHub + Code Spaces
- Codespaces is free at basic useage levels (then Team or Entperise membership allows greater utilisation)
- Make repo
- Launch code space
- Edit README
  - https://github.com/SustainableDevelopmentReform/cloud-native-yeah
- Load data - interact similarly to VS code desktop app
- Show examples (command line)
  - plastics tracker
  - Coding the app on a ipad pro, deploying to github pages
  - https://sustainabledevelopmentreform.github.io/CSDR-plastics-tracker/
- Can further customise runtime/dev environment
  - Not really my thing → prefer to use Colab (coming next) or VS Code Desktop/R Studio + GitHub
  - BUT it is very acheivable: https://github.com/revodavid/devcontainers-rstudio
  - THere are lots of prebuilt dev containers, and you can also customise your own

## Colab + Google Earth Engine (GEE)
- Colab you can run for free at basic processing levels
  - By default it will start with a Python runtime
  - But you can start with an R runtime, e.g. https://colab.research.google.com/drive/12VVcG1zxHJRPEwbPPkfzrt1UvJ0HUOHr?usp=sharing
- End-to-end cloud native example
- Squiddle data API interface -> Colab with R runtime -> d/l trianing data then ingest into GEE
- GEE processing and modelling (to make maps)
- GEE app deployment

## Other things of note
- Other Jupyter notebook implementations
- Linking directly to things like Observable, Shiny apps etc.
- General concept of "Code as Infrastrucutre" -> becomes more important as you move into implementing workflows into cloud architecutres like AWS/Azure/GCP 
