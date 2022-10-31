



International Journal of Trend in Scientific Research and Development (IJTSRD)

Soft Lattice in Approximation  Space

                                                                          
Payoja Mohanty
3270 Klaiman drive, Mississauga,
Ontario, Canada, L4Y3C8



                                                        
Email: Payoja.mohanty05@gmail.com

ABSTRACT

Rough
set theory is a powerful tool to analysis the uncertain and imprecise problem
in  information systems. Also the soft
set and lattice theory can be used as a general mathematical tool for dealing
with uncertainty. In this paper, we present a new concept, soft rough lattice
where the lower and upper approximations are the sub lattices and narrate some
properties of soft rough lattice with some examples.
             



KEYWORDS: Rough set, soft set, lattice theory, lower approximation
and upper approximation of soft lattice


1.     
INTRODUCTION

 Rough set theory was proposed by Prof.
Z. Pawlak in 1982[7] to deal   with uncertainty,
vagueness and imprecise problems. The classical rough set theory is  based on an equivalence relation that is, a
knowledge on a universe of objects U. Knowledge is based on the ability to
classify objects, and by objects we mean anything we can think of, for example
real things, states, abstract concepts, process, moment of time etc. For a
finite set of objects U, any subset X ⊆ U will be called a concept or a category in U and any family of concepts
in U will be referred to as knowledge about U.  Let us consider a classification or partition
of a certain universe U, that is, a family X={} is called  a partition of U if  for 

, i≠j, i,j=1,2,…,n and  = U.  W know that partition(or classification) of U
 and an equivalence relation on U are
interchangeable notion. So we consider equivalence relation 

R: U→  U instead of classification as it
is easy to manifulate. 

         Let R be an equivalence
relation on universe U, then U/R be the family of all equivalence classes of R
referred to as categories or concepts of R, and denotes a  category in R containing
an element x∈ U. Here R is a knowledge on U. 

          In 1999 D.  Molodtsov[6] introduced the concept of soft
sets, which is a new mathematical tool for dealing with uncertainty. Soft set
theory has potential applications in many different fields including game theory,
operational research, probability theory. Maji et al[4] defined several
operations on soft sets and made a theoretical study on the theory of soft
sets. The combination of the theories soft set and rough set be studied by Das
and Mohanty[2], Mohanty et al[5] and also by the other authors Feng et al[3].

                        Lattice are relatively
simple structures since the basic concepts of the theory include only orders,
least upper bounds, greatest lower bounds. Now the lattice plays on important
role in  many disciplines of computer
sciences and engineering. Though the concept of lattice was introduced by Pirce
and Schroder, but Boole(1930) and Birkhoff(1967)[1] gave the actual development
of  lattice  theory.

2.      PRELIMINARIES:



Definition-2.1:[8]  Let U be the universal set and C be an
equivalence relation(or knowledge)  on U,
where C is termed as indiscernibility relation. U/C be family of all
equivalence class of C, known as catagories of C, for xU.
 is an equivalence class of x. The relational
system  K=(U,C) is called a approximation
space. The lower and upper approximation of a set XU
under the indiscernibility relation C are defined as



X={xU:
}
and



X={
xU:
}
respectively.



 



Example-2.2:



    Let U={}
be the various colors for a painting. Let C be the knowledge on U, we get
a  partition of  U as



U/C={{},
{},
{},
{},
{}}



Where
 are red color,  are green color,   are yellow color,    color and 
 is blue color.



Let
X={}⊂
U. That is X  certain painting the lower
and upper approximation of  X are



X={}.
So yellow  color certainly belong to the
painting X.



And
X={,,
}.
So green and yellow color are possibly used for the painting  belong to X.



Hence,  X≠X.



Therefore,
the set X is rough with respect to knowledge C.



 



Example-2.3:



    Let U={}
be the different chocolate in a jar according to their price. Let D be the
knowledge on U, we get a partition of  U
as



 



U/D={{,},{},
{},
{},
{}}



That
is  {,}
are the 5rupees chocolate,  {}
are the 10rupees chocolate,  {}
are 10rupees chocolate, {}  are 30rupees chocolate and  {}is
50rupees chocolate. Let X={,,
}⊂
U, that is a set of chocolates are picked a random.



The
lower and upper approximation of X is 



 



X={}.
So 20rupees and 50 rupees chocolate are certainly belong to X.



X={,,
,
,
}.
So the chocolates of 20 rupees, 30 rupees and 
50rupees   are possibly classified
belong to X.



Hence,  X≠X.



Therefore,
the set X is rough with respect to knowledge D.



 



Definition-2.4:
Let U be an initial universe, E be the set of parameters related to U. Let P(U)
denotes the power set of U, A⊆
E and F be a mapping given by F:A →P(U),
then the pair (F,A) is called soft set over U.



 



Example-2.5:    Let U={}
be the set of shop, E={}
be the  set of parameters on U that is  stands for flower,  stands for seed,  stands for fresh,  stands
for stale and  stands for root vegetables. Let a mapping  F:E→P(U)
be given as F()={,},
=
{},
F()={},
F()={}
and F()={}
means  and are
root vegetables.



Let
A={}⊆
E then the soft set



(F,A)={(,
F()
), (green ,  ), (fresh, F())}



              ={(cheap , {,}),
(green , {}),
(fresh , {})}



 



Example-2.6:
Let U={}
be different quality bikes available in India market, E= {}
be the  set of parameters on U that is  stands for expensive,  stands for good mileage,  stands for sports, stands
for crusier and  stands for touring. Let a mapping  G:E→P(U)
be given as G()={,}
the expensive bikes are ,
 and ,
=
{,},
G()={},
G()={,}
and G()={}.




Let  A={}⊆
E then the soft set



(G,A)={(,
G()
), (good mileage ,  ), (cruiser, G())}



={(expensive,
{,}),
(good mileage, {,}),
(cruiser,   {,})}



 



            Definition-2.7:  Let Z=(Z,≾)
be a partially      



ordered
set. Then Z is called a lattice if for any two elements r and s of Z have a
least upper bound r∨s
and a greatest lower bound r∧s are in Z.



 



          Defintion-2.8:  Let (L,∨,∧)
be a lattice and 



              let S⊆
L be a subset of  L. Then (S,∨,∧)
is  



             called a sublattice of  (L,∨,∧)
if and only if 



             S is closed under both operations
of  



              join(∨)
and meet(∧).




 



Example-2.9: The power set
P(S) is a lattice under the operation union and intersection. That is S={⍺, }



Then P(S)={⌽,{ ⍺},{ },{ }, {⍺,  }, {}, {⍺, },S}.



Let A=(P(S),⋃,∩) is  a lattice.



That is { ⍺}⋃ { }={ }



                 {⍺}∩ { }=⌽



            { }⋃{ }={ }



                  { }∩{ }= { }



 



Example-2.10: Let A=(,|)= (1,2,3,4,5,6,10,12,15,20,30,60)
is a lattice.



    Join: 
6 ∨10=lcm(6,10)=30



    Meet: 6∧ 10=gcd(6,10)=2



    Join: 
10∨12=lcm(10,12)=60



          Meet: 10∧ 12=gcd(10,12)=2



 



3.     
SOFT ROUGH LATTICE:



 



Let L be an lattice, E be
the set of parameter and P(L) denotes the set of all of  L. The collection W=(F,A) is soft lattice
over L, where F is a mapping given by F:A →  P(L). Then S=(L,F,A) is called soft lattice
approximation space. 



 



Definition-3.1: For X  ⊆L, we define lower and
upper approximation as



  and 



 



If  ,
then X is called soft rough lattice. Otherwise X is soft definable
lattice.  Here,   and   are sublattices.



 



Example-3.2:
Let S={⍺, } be a set and  L=(S,⊆)
= {⌽,{ ⍺},{ },{ }, {⍺,  }, { }, {⍺, },S} be a lattice. Let E={} be the set of parameters
and D={}. Lt F: D→ P(L) be a mapping given by
F()={ { ⍺},{⍺,  }}, F()={ ⌽,{ ⍺},{ }, {⍺, }}, F()={{⍺},{⍺,}}, F()= {⌽,{ ⍺}, S}, F()={ { }, { } } be sublattices of L. Let X={{ ⍺},{⍺, }}∈ P(L). Then



{{⍺},{⍺,}} and =
{⌽,{⍺},{ },{⍺, },{⍺,  },S}



 



 



Theorem-3.3:



 Let W=(F,A) be soft lattice over L, S=(L,F,A)
be a soft lattice approximation space and X, Y⊆ L, we have



(a)    



(b)   



(c)  
 X⊆
Y⇒



(d)    X⊆
Y⇒  



 



          Proof:



(a)   According to definition of soft lattice lower
and upper approximation, we have



 



  



and




 



(b)   




        and 



 



(c)  
 Assume that X⊆
Y



By
definition, F(a)⊆
X⇒
u∈



So, u∈ F(a)⊆ Y



Therefore,  



(d)  Suppose  that X⊆ Y



  ⇒ 



   ⇒⊇



   ⇒ L-



  ⇒  



 



Theorem-3.4: 



 Let W=(F,A) be soft lattice over L, S=(L,F,A)
be a soft lattice approximation space and X, Y⊆ L, we have



 ⋃  



 (b)  ∩



 (c)⊇ ⋃



(d) 



(e) 



(f) 



Proof:



These can be prove
directly.



 



4.     
CONCLUSION:




This
paper aim to define soft rough lattice which is a new mathematical model to
deal with uncertain and vague concept. Some properties are proved. Frther
research can be made for the new model soft rough lattice.



 



 



 



 



 



                   REFERENCES



 



1.    G. Birkhoff, “Lattice Theory”, Trans. Amer. Math, Soc., New York, 1967.

 

2.    M. Das, D. Mohanty, “Dispensability on soft rough set theory”, International Journal of Engineering, Science and Mathematics, vol.10(4), pp. 1-10, 2021.



 



3.    F.Feng, X. Liu, V. Leoreanu-Fotea, Y. B. Jun, Soft sets and soft rough sets, Information Sciences 18(2011) 1125-1137.

 

4.    P.K. Maji, R. Biswas, R. Roy, “Soft set theory”, Computers and Mathematics with Applications, vol.45, pp. 555-562, 2003.



 



5.    D. Mohanty, N. Kalia, L. Pattanayak, B.B. Nayak ,  “An introduction to rough soft set”, Mathematical Science, International Research Journal, vol. 1(3), pp. 927-936, 2012.



 



6.   
D. Molodtsov, “Soft
set theory first results”, Computers and Mathematical with Applications, vol.
37, pp. 19-31, 1999.



 



7.     Z. Pawlak, “Rough set theory”, International Journal of Computer and Information Sciences, vol. 11, pp. 341-356, 1982.

 

8.     Z. Pawlak, “Rough sets-theoretical aspects of reasoning about data”,  Kluwer Academic Publishers, 1991 .



 



 



