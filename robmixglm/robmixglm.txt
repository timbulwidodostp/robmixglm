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
robmixglm_1 <- robmixglm(Dependen~Independen_1 + Independen_2, data = robmixglm)
summary(robmixglm_1)
robmixglm_2 <- robmixglm(Dependen~Independen_1 + Independen_2, data = robmixglm, cores = 1)
summary(robmixglm_2)
# Fits a Robust Generalized Linear Model and Variants Use robmixglm With (In) R Software
# Robust Generalized Linear Models (GLM) using Mixtures Use robmixglm With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished
