# Classification in R

## 4.R.R1

In ch4.R, line 13 is "attach(Smarket)." If that line was omitted from the script, which of the following lines would cause an error?:

- **line 15: mean(glm.pred==Direction)**
- line 18: glm.fit = glm(Direction~Lag1+Lag2+Lag3+Lag4+Lag5+Volume,data=Smarket,family=binomial, subset=train)
- line 22: Direction.2005=Smarket$Direction[!train]
- line 30: table(glm.pred,Direction.2005)