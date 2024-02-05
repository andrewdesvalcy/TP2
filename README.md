# TP2
LL
a=10
b=5
print(a)
print(b)
resultat = a*b
print(resultat)
A = 7.2
B = 10.1
#on remarque que les deux autres variable a et b sont pas impacter par A et B donc les majuscule différencie les objets
resultat= A*B
#cette fois ci la variable resultat est impacter car nous avons pas modifier la valeur 
rm(a,b,resultat,A,B)
v1= seq(1,5)
v2= v1+3
v3= seq(1,6)
v4=v3**2
v5=v4/2
v6= c("lundi","mardi","mercredi", "jeudi","vendredi","samedi","dimanche")
class(v6)
print(v6[2])  
print(v6[7])
v7= c(TRUE,FALSE,TRUE,FALSE)
class(v7)
v8= c(seq(1.1,1.9, by = 0.1))
class(v8)
v9= c(-1,-2,-3,-4,-5)
class(v9)
v10= c(NA,NA,NA)
class(v10)
#les fonctions c(), seq(), length()
seq1= seq(1,10)
length(seq1)
seq2= seq(2,20, by = 2)
length(seq2)
v11=c(rep(3, times = 3))
v12=rep(c("A","b","c"), times = 3)
v13=rep(c(TRUE,FALSE), times = 4)
rm(v1,v2,v3,v4,v5,v6,v7,v8,v9,v10,v11,v12,v13,seq1,seq2)
v5= runif(5,0,1)
v6= runif(10,-5,5)
v7= runif(100,10,20)
mean(v7)
min(v7)
median(v7)
max(v7)
v8= rnorm(20,-2,3)
mean(v8)
sd(v8)
v9=rnorm(2000,0,1)
mean(v9)
sd(v9)
quantile(v8,probs=c(0.25,0.5,0.75))
quantile(v9,probs=c(0.25,0.5,0.75))
quantile(v9,probs=c(0.1,0.2,0.3,0.4,0.5,0.6,0.7,0.8,0.9))
v10=rnorm(3000,2400,300)
round(v10)
sum(v10)
median(v10)
quantile(v10,probs=0.99)
