#' Vectors of colors for figures
#' Creates different vectors of related colors that may be useful for various IISG-related figures
#' 
#' @param set Character string indicating a set of colors
#' 
#' @return Vector of character strings 
#' 
#' @author J Stuart Carlton, \email{stuart@@jscarlton.net}
#' 
#' @keywords utilities
#' 
#' @examples 
#' plot(0, 0, type="n", xlab="", ylab="", xlim=c(0, 9), ylim=c(7.5, 0), yaxs="i",
#'      xaxt="n", yaxt="n", mar=c(0.6, 5.1, 0.6, 0.6), xaxs="i")
#' axis(side=2, at=1:5, c("main", "blues", "purples", "teals", "oranges"), las=1)
#'
#' gen <- iisgcolors("main")
#' points(seq(along=gen), rep(1,length(gen)), pch=21, bg=gen, cex=4)
#' text(seq(along=gen), rep(c(0.55, 0.7), length(gen))[seq(along=gen)], names(gen))
#'
#' points(1, 2, pch=21, bg=iisgcolors("blues"), cex=4)
#' points(1, 3, pch=21, bg=iisgcolors("purples"), cex=4)
#'
#' teals <- iisgcolors("teals")
#' points(seq(along=teals), rep(4,length(teals)), pch=21, bg=teals, cex=4)
#' text(seq(along=teals), rep(3+c(0.55, 0.7), length(teals))[seq(along=teals)], names(teals))
#'
#' oranges <- iisgcolors("oranges")
#' points(seq(along=oranges), rep(5,length(oranges)), pch=21, bg=oranges, cex=4)
#' text(seq(along=oranges), rep(4.7, length(oranges)), names(oranges))
#'
#' @export

iisgcolors <- 
  function(set = c("main", "blues", "purples", "teals", "oranges"))
  {
    main <- c('blue' = "#24509A",
              'purple' = "#3F29A0",
              'teal' = "#169281",
              'orange' = "#E8A224")
    
    blues <- c('shade0' = "#092A63",
               'shade1' = "#143B7D",
               'shade2' = "#24509A",
               'shade3' = "#3F64A4",
               'shade4' = "#6283BC")
    
    purples <- c('shade0' = "#1C0C67",
                 'shade1' = "#2B1882",
                 'shade2' = "#3F29A0",
                 'shade3' = "#5745AB",
                 'shade4' = "#7868C1")
    
    teals <- c('shade0' = "#005E51",
               'shade1' = "#087667",
               'shade2' = "#169281",
               'shade3' = "#319B8C",
               'shade4' = "#56B4A7")
    
    oranges <- c('shade0' = "#956000",
                 'shade1' = "#BD7E0D",
                 'shade2' = "#E8A224",
                 'shade3' = "#F7BB4F",
                 'shade4' = "#FFCF79")
    
    switch(match.arg(set),
           main=main,
           blues=blues,
           purples=purples,
           teals=teals,
           oranges=oranges)

  }