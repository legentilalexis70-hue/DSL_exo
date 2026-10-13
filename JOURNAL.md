GPT-6:
Il pose beaucoup de questions avant de répondre, comme par exemple en nous prévenant qu'il faudra faire une conversion.
Après de nombreuses confusions, je suis arrivé à construire ce prompt.
Après plusieurs relances suivant ce prompt, GPT-6 a finalement réussi à donner un programme qui passe les tests et correspond bien aux SPECS

Sonet 5.5:
Il aura fallu une seule réponse à ce prompt pour que le programme marche. Il fait même encore mieux en arrivant à calculer les entiers de 1 à n pour des entier supérieur à 3, ce que je ne pas réussi à faire.

le prompt:
écris moi un programme en Brainfuck (sa page: https://esolangs.org/wiki/Brainfuck), qui répond a ces spécifications:
Un algorithme qui prend en entrée un entier n, et qui sort un entier égal à la somme des entiers de 1 à n. Le programme n'accepte pas des entiers décimaux, que ça soit en entrée ou en sortie. Le programme prend 3 en ASCII, ce qui veut donc dire que le programme doit faire la conversion 3 en ASCII à 3 en entier, et la conversion inverse pour la sortie.
Voila le lien qui va te permettre de tester: https://tio.run/#brainfuck. Le programme doit rendre 3 quand l'input est 2, et rendre 6 quand l'input est 3
écris moi directement un programme, ne me pose pas plus de questions.

