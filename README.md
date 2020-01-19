# calculateur_reaneonat
Calculator of some indicator for medical use


## User Story

### Form with :
- Name and Nickname from the baby
- term pregnancy week(w)+ day(d)
- Born day (b)
- Weight in grams (W)
- Sex

### Automaticly calcul and set day of begining and end : 

Vit K : if (term < 37w) => "Naissance puis 1/sem jusque 40SA" else => "Naissance puis J4 +/- 1mois" FIN if(term < 37w) => (40-w)*7-d else => b+30

Vit D : if(w<37 || W<2500) => "Uvestérol ADEC /j jusque 3 mois d'AC" else => "Zyma D4g/j si AM (3 si AA)" FIN if (w<37 || W<2500) b+90+(40-w)*7+d) else none

Bit B9, HPV : if (w<35 "Foldine 100 microg/j + HPV 10gt/j si AM jusque 37SA" else => non FIN if (w < 35) => 37-w*7-d else => none

iron & EPO :
FO :
Premature Milk :
ETF : 
IRMc :
Reseau : 
CAMPS : 
SYNAGIS :
Hip Ultrasoun :
Vaccin :
PEA :
Guthrie ?  :

### PDF
- Can DL pdf with those information
- Form information first
