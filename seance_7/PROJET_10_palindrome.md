# Palindrome


1. Déclarez les variables nécessaires à votre programme. Vous aurez besoin d'une variable pour stocker le mot entré par l'utilisateur, et une variable pour stocker le résultat de la vérification de palindrome.

2. Utilisez la fonction scanf pour permettre à l'utilisateur de saisir un mot. Assurez-vous de vérifier que la saisie est valide.

3. Pour vérifier si le mot est un palindrome, vous devez parcourir les caractères du mot, de chaque extrémité vers le centre, en comparant chaque paire de caractères correspondants. 
	- Pour cela, vous pouvez utiliser une boucle for qui va parcourir la moitié du mot (la division entière de la longueur du mot par 2). 
	- Pour chaque itération, vous comparez le caractère à la position i (début du mot) avec le caractère à la position n-i-1 (fin du mot). Si une paire de caractères est différente, le mot n'est pas un palindrome.

4. Si la boucle se termine sans avoir trouvé de paire de caractères différents, le mot est un palindrome.

5. Affichez le résultat de la vérification à l'utilisateur à l'aide de la fonction printf.

6. Vous pouvez saisir différents mots pour tester votre programme.