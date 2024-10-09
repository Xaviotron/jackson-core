Xavier Dontigny - 20215658

Nicholas Gebran - 20149284

# Documentation des tests

## Taux de couverture final: 81.99%
<img src="images\finalCoverage.png" />

# Test 1

## writeRaw(String, int, int)

[Lien du test - Ligne 502](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que l'overload sur la méthode writeRaw avec les paramètres String, Int et Int, découpe la slice attendue de notre String lors de son écriture.

### Avant

<img src="images\1avant.png" />

### Après

<img src="images\1apres.png" />

# Test 2

## writeRaw(char[], int, int)

[Lien du test - Ligne 529](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que l'overload sur la méthode writeRaw avec char[], Int i et Int j, écris les j prochains charactères de l'array à partir de l'indice i.

### Avant

<img src="images\2avant.png" />

### Après

<img src="images\2apres.png" />

# Test 3

## writeRaw(char)

[Lien du test - Ligne 556](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que l'overload sur la méthode writeRaw avec le paramètre unique char. Devrait écrire uniquement le charactère passé en paramètre.

### Avant

<img src="images\3avant.png" />

### Après

<img src="images\3apres.png" />

# Test 4

## writeRawValue(String, int, int)

[Lien du test - Ligne 581](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que l'overload sur la méthode writeRawValue avec les paramètres String, Int et Int, découpe la slice attendue de notre String lors de son écriture.

### Avant

<img src="images\4avant.png" />

### Après

<img src="images\4apres.png" />

# Test 5

## writeRawValue(char[], int , int)

[Lien du test - Ligne 608](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que l'overload sur la méthode writeRawValue avec char[], Int i et Int j, écris les j prochains charactères de l'array à partir de l'indice i.

### Avant

<img src="images\5avant.png" />

### Après

<img src="images\5apres.png" />

# Test 6

## writeTree(TreeNode)

[Lien du test - Ligne 635](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste la branche de writeTree(TreeNode) quand delegateCopyMethods est faux et que le TreeNode passé en paramètre est null. Cette branche utilise writeTree récursivement. Ce cas spécifique de writeTree() n'était pas testé précédemment.

### Avant

<img src="images\6avant.png" />

### Après

<img src="images\6apres.png" />

# Test 7

## writeTree(TreeNode)

[Lien du test - Ligne 657](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste la branche de writeTree(TreeNode) quand delegateCopyMethods est vrai. Cette branche utilise writeTree récursivement. Ce cas spécifique de writeTree() n'était pas testé précédemment.

### Avant

<img src="images\7avant.png" />

### Après

<img src="images\7apres.png" />

# Test 8

## writeTree(TreeNode)

[Lien du test - Ligne 681](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste la branche de writeTree(TreeNode) quand delegateCopyMethods est faux, le TreeNode n'est pas null et que l'ObjectCodec est null. Ce cas spécifique de writeTree() n'était pas testé précédemment.

### Avant

<img src="images\8avant.png" />

### Après

<img src="images\8apres.png" />

# Test 9

## writeObject(Object)

[Lien du test - Ligne 709](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste la branche de writeObject(Object) quand delegateCopyMethods est vrai. Cette branche utilise writeObject récursivement. Ce cas spécifique de la méthode n'était pas testé précédemment.

### Avant

<img src="images\9avant.png" />

### Après

<img src="images\9apres.png" />

# Test 10

## writeObject(Object)

[Lien du test - Ligne 735](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste la branche de writeObject(Object) quand delegateCopyMethods est faux et (Object)pojo  est null. Ce cas spécifique de la méthode n'était pas testé précédemment.

### Avant

<img src="images\10avant.png" />

### Après

<img src="images\10apres.png" />

# Test 11

## writeNumber(char[], int, int)

[Lien du test - Ligne 758](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que l'overload sur la méthode writeNumber avec les paramètres char[], Int i et Int j, écris les j prochains charactères de l'array à partir de l'indice i comme un nombre.

### Avant

<img src="images\11avant.png" />

### Après

<img src="images\11apres.png" />

# Test 12

## writeBinary(Base64Variant, byte[], int, int)

[Lien du test - Ligne 778](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que l'overload sur la méthode writeBinary avec les paramètres avec les paramètres byte[], Int i et Int j, écris les j prochains bytes de l'array à partir de l'indice i dans la base passée en paramètre.

### Avant

<img src="images\12avant.png" />

### Après

<img src="images\12apres.png" />

# Test 13

## enable(JsonGeneratorFeature)

[Lien du test - Ligne 800](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que le feature activé par la fonction applique son effet sur le generator.

### Avant

<img src="images\13avant.png" />

### Après

<img src="images\13apres.png" />

# Test 14

## disable(JsonGeneratorFeature)

[Lien du test - Ligne 821](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste qu'un feature activé par la fonction enable n'applique pas son effet sur le generator si on le disable().

### Avant

<img src="images\14avant.png" />

### Après

<img src="images\14apres.png" />

# Test 15

## useDefaultPrettyPrinter()

[Lien du test - Ligne 844](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que le PrettyPrinter de base applique ses effets sur le générateur lorsqu'on invoque la fonction useDefaultPrettyPrinter().

### Avant

<img src="images\15avant.png" />

### Après

<img src="images\15apres.png" />

# Test 16

## setPrettyPrinter(PrettyPrinter)

[Lien du test - Ligne 866](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que le PrettyPrinter passé en paramètre applique ses effets sur le générateur.

### Avant

<img src="images\16avant.png" />

### Après

<img src="images\16apres.png" />

# Test 17

## overrideStdFeatures(int, int)

[Lien du test - Ligne 893](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que le premier feature passé en paramètre n'applique pas ses effets sur le generator, tandis que le deuxième si.

### Avant

<img src="images\17avant.png" />

### Après

<img src="images\17apres.png" />

# Test 18

## overrideFormatFeatures(int, int)

[Lien du test - Ligne 917](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que le premier feature passé en paramètre n'applique pas ses effets sur le generator, tandis que le deuxième si.

### Avant

<img src="images\18avant.png" />

### Après

<img src="images\18apres.png" />

# Test 19

## setFeatureMask(int)

[Lien du test - Ligne 942](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que le mask passé en paramètre applique son effet sur le generator.

### Avant

<img src="images\19avant.png" />

### Après

<img src="images\19apres.png" />

# Test 20

## setCodec(ObjectCodec)

[Lien du test - Ligne 967](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste que le coded passè en paramètre est bel et bien le codec du generator après invocation.

### Avant

<img src="images\20avant.png" />

### Après

<img src="images\20apres.png" />

# Test 21

## setHighestNonEscapedChar(int) ET getHighestEscapedChar()

[Lien du test - Ligne 986](../../src/main/java/com/fasterxml/jackson/core/util/DelegatesTest.java)

Teste le getter et setter simultanément en comparant la valeur de l'attribut après le set et la valeur attendue.

### Avant

<img src="images\21aavant.png" />
<img src="images\21bavant.png" />

### Après

<img src="images\21aapres.png" />
<img src="images\21bapres.png" />