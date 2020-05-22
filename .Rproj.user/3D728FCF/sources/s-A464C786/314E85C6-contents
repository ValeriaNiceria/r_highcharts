fluidRow <- function (...) 
{
  div(class = "row", ...)
}


column <- function (width, ..., offset = 0) 
{
  if (!is.numeric(width) || (width < 1) || (width > 12)) 
    stop("column width must be between 1 and 12")
  colClass <- paste0("col-sm-", width)
  if (offset > 0) 
    colClass <- paste0(colClass, " col-sm-offset-", offset)
  div(class = colClass, ...)
}
