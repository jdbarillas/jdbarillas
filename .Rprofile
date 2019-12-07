source("renv/activate.R")
options(blogdown.new_bundle = TRUE)
options(blogdown.author = "Joshua Barillas",
        blogdown.ext = ".Rmd",
        blogdown.subdir = "post",
        blogdown.yaml.empty = TRUE,
        blogdown.new_bundle = TRUE,
        blogdown.title_case = TRUE)

rprofile <- Sys.getenv("R_PROFILE_USER", "~/.Rprofile")

if (file.exists(rprofile)) {
  source(file = rprofile)
}
