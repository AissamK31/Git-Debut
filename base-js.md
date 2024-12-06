prise de note js

1. syntaxe:
        
        -terminer le code par un ;

        - 3 type de variables (boite qui stock une info): 
                let (utiliser le plus souvent)
                var (pareil que let mais old school)
                const pour constante (valeur stock qui ne change pas)
        exemple1:
        let (var) message;
        message = 'Hello'; // stocke la chaîne de caractères 'Hello' dans la variable nommée message 
        exemple2:
        const myBirthday = '18.04.1982';

        -type de données:
        
                number: 
                Le type number sert à la fois à des nombres entiers et à des nombres à virgule flottante.
                let n = 123;
                n = 12.345;

                BigInt: 
                Le type BigInt est une primitive numérique en JavaScript qui peut représenter des entiers de grandeur arbitraire.
                Une valeur BigInt est créé en ajoutant n à la fin d’un entier

                string: 
                Une chaîne de caractères en JavaScript doit être entre guillemets.
                3 types de guillemets.
                Double quotes: "Hello".
                Single quotes: 'Hello'.
                Backticks: `Hello`.
                Les backticks sont des guillemets “à fonctionnalité étendue”. Ils nous permettent d’intégrer des variables et des expressions dans une chaîne en les encapsulant dans ${…}, par exemple :
                let name = "John";
                // une variable encapsulée
                alert( `Hello, ${name}!` ); // Hello, John!
                // une expression encapsulée
                alert( `the result is ${1 + 2}` ); // le résultat est 3

                Boolean: 
                Le type booléen n’a que deux valeurs: true et false.
                Ce type est couramment utilisé pour stocker des valeurs oui / non: true signifie “oui, correct” et false signifie “non, incorrect”.

                La valeur “null”:
                La valeur spéciale null n’appartient à aucun type de ceux décrits ci-dessus.
                Il forme un type bien distinct qui ne contient que la valeur null 

                La valeur “undefined”:
                La valeur spéciale undefined se distingue des autres. C’est un type à part entière, comme null.
                La signification de undefined est “la valeur n’est pas attribuée”.
                Si une variable est déclarée mais non affectée, alors sa valeur est exactement undefined

                L'opérateur typeof:
                L’opérateur typeof renvoie le type de l’opérande. Il est utile lorsqu’on souhaite traiter différemment les valeurs de différents types ou de faire une vérification rapide.
                L’appel typeof x renvoie une chaîne de caractères avec le nom du type :
                typeof undefined // "undefined"
                typeof 0 // "number"
                typeof 10n // "bigint"
                typeof true // "boolean"
                typeof "foo" // "string"
                typeof Symbol("id") // "symbol"
                typeof Math // "object"  (1)
                typeof null // "object"  (2)
                typeof alert // "function"  (3)