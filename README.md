# MCOC-Proyecto-0

a=1.0
b=2.0
c=3.0

x=10.0
y=20.0
z=30.0


s=(a/c)    #1/3
print "s= 1/3=",s  

#dos_s= s*2 
#print "dos_s=", dos_s

m=s+s+s  # 1/3 + 1/3 + 1/3 = 1
print "m= 1/3+1/3+1/3=",m

l1= m-s     # 1/3 + 1/3 + 1/3 - 1/3 = 2/3
print "l1= 1/3+1/3+1/3-1/3=",l1

l2= l1-s     #1/3 + 1/3 + 1/3 - 1/3 - 1/3 = 1/3
print "l2= 1/3+1/3+1/3-1/3-1/3=",l2

l3_suma= l2-s     #1/3 + 1/3 + 1/3 - 1/3 - 1/3 - 1/3 = 0
print "l3_suma= 1/3+1/3+1/3-1/3-1/3-1/3=",l3_suma

l3_multiplicacion=3*s-3*s
print "l3_multiplicacion=", l3_multiplicacion

# al realizar la operacion (3*s-3*s) el resultado entrega 0, pero al tener la operacion
# (s+s+s-s-s-s el resultado es 1,1102.....**-16), por lo que hay un problema de "prioridad"
# del computador, en donde por regla hace primero las divisiones y las multiplicaciones, sin 
# darse cuenta que si sumase primero (en este ejemplo) no solo se le haria el trabajo mas 
# facil, si no que obtendria el resultado correcto (ya que por aproximar en en sus divisiones
# le termina dadno un numero infinitamente pequeño, peor no igual a cero)

print ""
print "separacion"
print ""

k0_suma=(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)
print "k0_suma= (2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)=", k0_suma

k1_suma=(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)
print "k1_suma= (2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)+(2.0/6)-(2.0/6)-(2.0/6)-(2.0/6)=",k1_suma

#la diferencia entre estos dos es que en k0_suma tenemos dos paraes iguales, unos positivos
# y otros negativos, por lo que el resultado matematicamente es cero, pero como ya vimos por
#el ejemplo anterior esto no va a dar cero, pero siguiendo su logica 
#debiera dar el doble del l3_suma ya que es la misma operacion repetida dos veces
# (2* 1,1102...*-16, sin embargo no nos da el doble, si no que le mismo resultado de l3_suma)
# Luego al analizar k1_suma sabemos que matematicamente el resultado es 1, pero 
#si seguimos la logica de error del programa, nos debiera dar como resultado 
# 1+ 1,1102...**-16, pero denuevo no es asi y nos da 1)











