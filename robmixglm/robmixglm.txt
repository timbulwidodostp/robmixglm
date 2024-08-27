# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Fits a Robust Generalized Linear Model and Variants Use robmixglm With (In) R Software
# Robust Generalized Linear Models (GLM) using Mixtures Use robmixglm With (In) R Software
install.packages("robmixglm")
install.packages("MASS")
library("robmixglm")
library("MASS")
robmixglm = read.csv("https://raw.githubusercontent.com/timbulwidodostp/robmixglm/main/robmixglm/robmixglm.csv",sep = ";")
# Estimation # Fits a Robust Generalized Linear Model and Variants Use robmixglm With (In) R Software
# Robust Generalized Linear Models (GLM) using Mixtures Use robmixglm With (In) R Software
robmixglm <- robmixglm(100*log10(pres)~bp, data = robmixglm, cores = 1)
summary(robmixglm)
# Fits a Robust Generalized Linear Model and Variants Use robmixglm With (In) R Software
# Robust Generalized Linear Models (GLM) using Mixtures Use robmixglm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished