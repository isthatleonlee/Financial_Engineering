.First <- function() {
  dir.create(paste0(getwd(), "/Data"), showWarnings = F)
  dir.create(paste0(getwd(), "/Output"), showWarnings = F)
  dir.create(paste0(getwd(), "/Output/Plots"), showWarnings = F)
  dir.create(paste0(getwd(), "/Output/Data"), showWarnings = F)
  dir.create(paste0(getwd(), "/Script"), showWarnings = F)
  dir.create(paste0(getwd(), "/Script/Functions"), showWarnings = F)
  

  
  if (!("renv" %in% list.files())) {
    renv::init()
  } else {
    source("renv/activate.R")
  }
  
  cat("\nWelcome to your R-Project:", basename(getwd()), "\n")
}