---
title: Cryptography
localeTitle: Criptografia
---
## Criptografia

O objetivo básico da criptografia é permitir que duas pessoas se comuniquem através do canal inseguro de tal maneira que uma terceira pessoa não possa entender o que está sendo dito. Este canal pode ser uma linha telefônica ou uma rede de computadores.

A criptografia começou a ser usada pelos romanos para tornar as mensagens em batalha ilegíveis pelo inimigo se decifrassem.

A criptografia anterior à era moderna era efetivamente sinônimo de criptografia, a conversão de informações de um estado legível em aparente absurdo.

A criptografia moderna é usada em dados para que apenas uma parte ou apenas partes autorizadas tenham a capacidade de acessar as informações.

A criptografia ao longo dos anos tornou-se mais avançada.

### Exemplo

As informações que Alice deseja enviar para Bob, que chamamos de "texto sem formatação", podem ser texto, dados numéricos ou qualquer tipo de dado. Alice criptografa o texto simples, usando uma chave predeterminada e envia o "texto cifrado" resultante sobre o canal. Eve, agindo como um MiTM (man-in-the-middle, quando um terceiro escuta a conexão sem a devida permissão), ao ver o texto cifrado no canal, não pode determinar qual era o texto original, mas Bob, que conhece a chave de criptografia, pode descriptografar o texto cifrado e reconstruir o texto simples.

### Cifra de César (Shift Cypher)

A primeira cifra conhecida foi a Cifra de César. A Cifra de César funciona mudando as letras de um "texto simples" por uma quantidade específica para cima ou para baixo no alfabeto.

Do ponto de vista de uma pessoa externa, a mensagem parece ser letras aleatórias com espaços entre elas.

No seu tempo, ela foi muito útil pois não sabiam como decifrar. Porém essa cirfra ainda é ensinada por fins didáticos e históricos pois ela já sofreu com sucesso uma criptoanálise. A vulnerabilidade dela é por repetição das letras do alfabeto de uma determinada língua.

Por exemplo: na língua inglesa, a letra 'e' é a que mais aparece em toda a língua. Se a chave da Cifra de César é 3, a letra 'e' rotacionada três vezes se torna 'h'. Ou seja, toda a letra que for 'e' irá se tornar 'h', assim ficando evidente a repetição das letras.

### Criptografia Moderna

A criptografia moderna usa números pseudo aleatórios e funções matematicamente sólidas para permitir uma comunicação segura. Essas funções recém desenvolvidas não podem ser facilmente quebradas devido à sua estrutura, exigindo que até mesmo centenas de anos de supercomputadores sejam quebrados.

Existem dois tipos principais de criptografia moderna:

### 1) Criptografia Simétrica ou de Chave Única:

A Criptografia de Chave Simétrica é um método de criptografia em que ambas as partes usam apenas uma chave criptográfica para a criptografia e a decriptografia. Esses algoritmos, devido ao seu design, geralmente são muito mais rápidos do que a criptografia de chave pública ou assimétrica.

Algumas técnicas de criptografia simétrica incluem: Data Encryption Standard (DES), Advanced Encryption Standard (AES), Blow Fish, Twofish, RC4.

### 2) Criptografia Assimétrica ou de chave pública:

Os algoritmos de criptografia assimétrica fornecem a cada usuário um par de chaves: uma pública e outra privada. Qualquer mensagem criptografada com uma chave do par só pode ser descriptografada com a outra.

A chave privada só deve ficar em posse da pessoa em questão. Em hipótese alguma ela poderá ser exposta, assim toda a assinatura digital, a criptografia de dados utilizando essa chave privada estará comprometida.

Por outro lado, a chave pública, como o nome diz, ela deve ser pública.

Algumas técnicas assimétricas incluem: RSA, Diffie-Hellman, DSS (assinatura digital padrão), ElGamal, PGP.

### Hashing Criptográfico

A maioria das funções hash criptográficas é projetada para obter uma string de qualquer comprimento como entrada e produzir um valor de hash de tamanho fixo.

Uma função hash criptográfica deve ser capaz de suportar todos os tipos conhecidos de ataque criptográfico.

### Hashing de Criptografia

Uma função hash criptográfica é um tipo de função hash que é projetada para também ser uma função unidirecional (uma função que leva muito tempo e recursos para a força bruta). O principal objetivo dos hashes é lidar com a intregridade da mensagem, portanto, a mesma mensagem sempre resulta no mesmo hash.

#### Mais Informações:

*   [Criptografia: teoria e prática por Douglas Stinson](https://www.crcpress.com/Cryptography-Theory-and-Practice-Third-Edition/Stinson/p/book/9781584885085)
*   [TechTarget on Encryption](http://searchsecurity.techtarget.com/definition/encryption)
*   [Guia de criptografia](https://www.tutorialspoint.com/cryptography/index.htm)
