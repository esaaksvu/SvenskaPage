slide 0: nimet + otsikko

slide 1: aiheet (1. krypt basics, 2. symm. + lohkosalaus kaaviot, 3. RSA)

slide 2: kryptering

slide 3: lohkosalaus kaavioita 1-3

slide 4: RSA kaava.

============================================================================

Esittäytyminen:

jag är ...../jag heter
jag är ..../jag heter
vi studierar datavetenskap
vår presentation handlar om kryptering

// (vi har gjort några html sidar som vi ska visa.)

teemat:

vi har tree teman som är 'kryptering', 'symmetrisk kryptering' och 'asymmetrisk kryptering'.

kryptering: // näytelmä, missä visualisoimme kryptauksen tarkoitusta
1. E --Msg--> M
2. Nyt huomataan "stalkkaajat". MITÄ TEHDÄ?
3. E --Crypt(msg)-> C_msg
4. E --C_msg--> M
5. (っ◕‿◕)っ

Där finns karaktärkryptering men vi ska berätta om blockkryptering. 

symmetrisk kryptering:

Symmetrisk kryptering är ett form av kryptering som användas samman nyckel för kryptering och dekryptering.
Avsändare och mottagare har samma nyckel och därför kan inte alla andra läsa meddelande som har skickat. 

blockchiffer:

vi har tree bilder som är grafer av ECB, CBC och CFB.

ECB:

ECB står för engelska ord 'electronic codebook'. Det är enkelt metod av blockchiffer. Meddelande ska splittas i blocken.
varje block ska krypteras separat. Kryptering användas en nyckel som är samma för alla blocken.

CBC:

CBC påminnar ECB men ECB blocken beror inte på varandra. CBC står för 'cipher block chaining'. 
Det betyder 'kedjeanvändande blockchiffer'.  Förre kryptering av blocket, CBC gör xor-operation om block och
sista krypterat block. Så vi har en kedja.

CFB:

CFB står för 'cipher feedback'. CFB krypterar IV eller sista blocken med nyckel och sen gör xor för resultatblocken och nästa block av meddelandet. CFB också har kedjning.

asymmetrisk kryptering:

Asymmetrisk kyrptering användar inte samma nyckel för kryptering och dekryptering. Asymmetrisk kyrptering användar ett nyckelpar. En nyckel är öppen('publik') för att kryptera med och en egen privat nyckel för att kunna dekryptera.
RSA är en asymmertrisk kryptering program.
