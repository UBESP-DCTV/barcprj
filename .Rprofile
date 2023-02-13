Sys.setenv(RENV_DOWNLOAD_FILE_METHOD = "libcurl")
source("renv/activate.R")

if (!requireNamespace("CMatching")) {
  install.packages(c("minqa", "RcppEigen", "lmtest", "lme4", "Rcpp"))
  install.packages("CMatching", type = "source")
}
