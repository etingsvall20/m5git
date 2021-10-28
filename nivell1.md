# Java (llenguatge de programació)

Salta a la navegacióSalta a la cerca
	No s'ha de confondre amb JavaScript.
Infotaula de llenguatge de programacióJava
Tipus	llenguatge de programació multiparadigma, JVM language (en) Tradueix i llenguatge de programació Modifica el valor a Wikidata
Data de creació	1995 Modifica el valor a Wikidata
Disseny	James Gosling i Sun Microsystems Modifica el valor a Wikidata
Desenvolupador	Sun Microsystems i Oracle Corporation Modifica el valor a Wikidata
Epònim	Java coffee (en) Tradueix Modifica el valor a Wikidata
Paradigma de programació	programació estructurada, programació orientada a objectes, programació funcional, llenguatge imperatiu, class-based programming (en) Tradueix, reflexió, programació genèrica, concurrent object-oriented programming (en) Tradueix i component-based software engineering (en) Tradueix Modifica el valor a Wikidata
Darrera versió estable	Java SE 17 () Modifica el valor a Wikidata
Influenciat per	C++, C, Ada, Simula 67 (en) Tradueix, Smalltalk, Objective-C, Object Pascal, Oberon, Llenguatge de programació Eiffel, Modula-3, Mesa, Simula67, C#, UCSD Pascal, object type (en) Tradueix, variadic function (en) Tradueix, anotació (Java), Niklaus Wirth, Patrick Naughton i foreach loop (en) Tradueix Modifica el valor a Wikidata
Extensió dels fitxers	java, class, jar, jad i jmod Modifica el valor a Wikidata
Llicència	GNU General Public License Modifica el valor a Wikidata
Etiqueta d'Stack Exchange	Etiqueta i Etiqueta Modifica el valor a Wikidata
Pàgina web	oracle.com… Modifica el valor a Wikidata

## Duke, la mascota del Java.

Codi font d'un programa escrit amb el llenguatge de programació Java
El Java és un llenguatge de programació dissenyat el 1990 per __James Gosling__ amb altres companys de Sun Microsystems a partir del llenguatge C. Des del seu naixement fou pensat com un llenguatge orientat a objectes. Entre el 13 de novembre de 2006 i el maig del 2007 Sun va alliberar parts de **Java** com a programari lliure de codi obert amb llicència [GPL](https://ca.wikipedia.org/wiki/GNU_General_Public_License)GPL. És un dels llenguatges de programació més utilitzats, i s'utilitza tant per aplicacions web com per aplicacions d'escriptori.

El Java és un llenguatge compilat amb una màquina virtual d'intermediari i, per tant, pot semblar lent en comparació amb altres llenguatges, però ofereix un índex de re-utilització de codi molt elevat, sent possible trobar moltes llibreries lliures de Java. És un llenguatge flexible i potent tot i la facilitat amb la qual es programa i dels resultats que ofereix. Un dels trets que el caracteritza i que el fa una eina molt valorada a l'hora de desenvolupar aplicacions distribuïdes, és el fet que és un llenguatge multi-plataforma.

Generalment els programes de Java es compilen en un [bytecode](https://ca.wikipedia.org/wiki/Bytecode_(Java)) (fitxer .class) que pot córrer en una Màquina Virtual Java. Sun Microsystems disposa de tres implementacions diferents de Java: J2SE per a aplicacions d'escriptori; J2EE per a aplicacions distribuïdes i J2ME per a plataformes amb recursos més reduïts com ara mòbils o PDAs. Per a cada una de les tres implementacions és possible descarregar el JRE (entorn d'execució Java) per a executar aplicacions o el SDK (Eines per al desenvolupament d'aplicacions) per a programar aplicacions en Java, aquest últim també inclou el JRE.

Un programa desenvolupat amb Java **no necessita compilar-se de nou per a poder executar-se en qualsevol de les plataformes que disposi d'una versió instal·lada de JRE prou actualitzada per al programa.**


### Contingut
1. Característiques de Java
2. Tipus de Dades
2.1. Tipus de dada primitius o variables primitives
2.1.1. BOOLEÀ (boolean)
2.1.2. CARÀCTER (char)
2.1.3. NUMÈRICS ENTERS (byte, short, int, long) i NUMERICS REALS (fload, double)
3. Altres Característiques
4. Sintaxi
4.1. Hola Món
4.1.1. Aplicacions autònomes
5. Aplicacions i miniaplicacions
6. Limitacions de seguretat en les miniaplicacions
7. Eines de desenvolupament JAVA2
8. Passos per crear un programa amb Java
9. Com desenvolupar aplicacions: Entorns (IDE)
10. Altres projectes i eines relacionades
11. Programa d'exemple
12. Referències
13. Vegeu també
14. Enllaços externs
Característiques de Java
Senzill: Java s'ha creat perquè sigui un llenguatge senzill amb una sintaxi elegant. Únicament consta de tres tipus de dades primàries, eliminant els punters i l'herència múltiple
Orientat a objectes: Java segueix els paradigmes de la programació orientada a objectes, ja que la programació amb Java se centralitza en la manipulació, creació i construcció d'objectes.
Distribuït: Java permet la construcció d'aplicacions distribuïdes per mitjà d'una col·lecció específica de classes.
Interpretat: Es necessita un intèrpret per executar els programes de Java, això alenteix als programes però els hi dona flexibilitat.
Robust: Java és un llenguatge robust i fiable, s'ha escrit pensant a poder verificar errors i està molt tipificat.
Segur: Java té __pocs problemes de seguretat__, característica molt important en les aplicacions distribuïdes d'Internet.
Arquitectura neutral: Java és __independent de la plataforma final on s'executarà el programa.__
Portable: Java és un llenguatge d'alt nivell i de plataforma independent, això li dona portabilitat.
Alt rendiment: Els compiladors Java han anat millorant les seves prestacions. Els nous compiladors
coneguts com a JIT permeten un rendiment molt semblant als llenguatges convencionals __compilats__.

Concurrent: Java permet l'execució de múltiples fils d'execució, o diverses tasques de forma simultània.
Dinàmic: En temps d'execució, l'entorn Java es pot ampliar mitjançant enllaços a classes que poden estar localitzades en servidors remots o en xarxa.
Tipus de Dades
Tipus de dada primitius o variables primitives
Article principal: Tipus de dada primitius
Els tipus de dades fan referència al tipus d'informació que es treballa, on la unitat mínima d'emmagatzematge és la dada, també es pot considerar com el rang de valors que pot prendre una variable durant l'execució del programa.

Els tipus primitius en Java tenen la mateixa mida en cada implementació menys els tipus booleans que pot variar.

Tipus	Paraula reservada	Mida (bits)	Mida (bytes)	Valor mínim	Valor màxim
- Booleà	boolean	--	--	--	--
- Byte enter	byte	8-bit	1 byte	-128	+127
- Caràcter	char	16-bit	2 bytes	Unicode 0	Unicode {\displaystyle 2^{16}-1}{\displaystyle 2^{16}-1}
- Enter curt	short	16-bit	2 bytes	{\displaystyle -2^{15}}{\displaystyle -2^{15}}	{\displaystyle +2^{15}-1}{\displaystyle +2^{15}-1}
- Enter	int	32-bit	4 bytes	{\displaystyle -2^{31}}{\displaystyle -2^{31}}	{\displaystyle +2^{31}-1}{\displaystyle +2^{31}-1}
- Enter llarg	long	64-bit	8 bytes	{\displaystyle -2^{63}}{\displaystyle -2^{63}}	{\displaystyle 2^{63}-1}{\displaystyle 2^{63}-1}
- Punt flotant	float	32-bit	4 bytes	IEEE 754	IEEE 754
- Punt flotant de doble presició	double	64-bit	8 bytes	IEEE 754	IEEE 754
- BOOLEÀ (boolean) Només pot tenir el valor true o false.

>CARÀCTER (char)
>Utilitzen 16 bits i codifiquen caràcters segons el format UNICODE (no com ASCII que fa servir 8 bits). El Tipus de dada char és un dígit individual, sense signe el qual es pot representar com numèrics (0 al 9), lletres (a-z) i símbol ($, _). NOTA: En llenguatge java la codificació Unicode permet treballar amb tots els caràcters de diferents idiomes.

>NUMÈRICS ENTERS (byte, short, int, long) i NUMERICS REALS (fload, double)
>Els valor literals dels dígits poden ser escrits en base 10, hexadecimal i octal. Els valors numèrics decimals, la coma ha de ser un punt.

Altres Característiques
Absència de punters
Classes i objectes
Herència
Classes abstractes
Interfícies
Programació genèrica
Encapsulació i polimorfisme
Interfícies gràfiques d'usuari
Gestió d'esdeveniments
Programació concurrent
Excepcions
Sintaxi
La sintaxi del Java deriva en gran part del C. Però a diferència d'aquest, que combina la sintaxi per a programació genèrica, estructurada i orientada a objectes, el Java va ser dissenyat gairebé exclusivament com a llenguatge orientat a objectes.[3] Tot el codi es troba dins d'una classe, i tot és un objecte (excepte nombres ordinals i reals, booleans i caràcters per motius de rendiment).

```
// Hola.java
import java.io.IOException;
public class Hola {
    public static void main(String[] args)throws IOException {
        System.out.println("Hola, món!"); 
    }
}
```