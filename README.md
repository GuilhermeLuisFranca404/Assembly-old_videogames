# Assembly-old_videogames
<h4 align="center"> 
	🚧  🚀 Em construção...  🚧
</h4>

Desvendando um pouco com assembly com video games antigos, projeto baseado e creditos dados a <a target="_blank" href="https://www.youtube.com/watch?v=WoOVbPnpyjk&list=PLLFRf_pkM7b6Vi0ehPPovl1gQ5ubHTy5P&index=2">esta playlist brasileira</a>, conduzido por <a href="https://github.com/ManualDoCodigo">Douglas Diniz</a> do canal <a href="https://www.youtube.com/@ManualdoCodigo">Manual do Código</a>.

# Unidades de medida
Antes de entendermos o funcionamento do video games, vamos entender um pouco sobre unidades de medida, o básico é o seguinte, na ordem crescente de unidades básicas (decimais) temos: bit, byte, e a partir daí já podemos ter nossas medidas de unidades, onde entenda:
<pre>
1 byte = 8 bits;
16 bits = 2 bytes;
Ou seja, para se obter 1 byte precisamos de 8 bits.
</pre>
  Com o tempo, com mais memória que passamos a ter, precisamos criar novas formas de mostrar unidades de medidas, seria difícil chegar e dizer um milhão de bytes não? Então por isso foi criado novas medidadas de unidades, como KB, MB, GB, TB, PB entre outras...<br>
  Para se ler isso, lemos assim, o B no final se significa bytes, ou seja:
<pre>
K = kilo
M = mega
G = giga
T = tera
P = peta
Sendo, KB kilobyte e GB gigabyte e assim vai
</pre>
E assim podemos entender um maior número de bytes, sendo 1000 bytes 1 kilobyte, 1000 kilobytes 1 megabyte e assim vai, seguinda a ordem acima.<br><br>
Só que além das unidades de medida Decimais, as vistas acima e mais usadas, temos além destas as medidas de unidade Binárias, veja um comparação de valores e unidades decimais e binárias: 
<pre>
        Binário                               Decimal
Nome     | Símbolo | Valor <small>(base 2)</small>     Nome     | Símbolo |  Valor <small>(base 10)</small>
kibibyte | KiB	   | 2^10	       kilobyte | KB	  |  10^3
mebibyte | MiB	   | 2^20	       megabyte | MB	  |  10^6
gibibyte | GiB	   | 2^30	       gigabyte	| GB	  |  10^9
tebibyte | TiB	   | 2^40	       terabyte	| TB	  |  10^12
pebibyte | PiB	   | 2^50	       petabyte	| PB	  |  10^15
exbibyte | EiB	   | 2^60	       exabyte	| EB	  |  10^18
</pre>
Mas para que essa separação?, bem pereba algo primeiro, em base 2, os binários tem base 2, ou seja, matematica básica, serão todos multiplos de 2, ou seja: 1, 2, 4, 8, 16, 32, 64, 128, 254, 512, 1024, 2048... já os decimais, base 10, seus multiplos seriam isso: 10, 100, 1000, 10000, 100000... essa é sua diferença, 100KB comparados a 100KiB tem diferença de 2,35%, mas isso aumenta, 100TB com 100TiB, a diferença é de 9,06%.<br>
Perceba também agora que para termos 1GiB, será preciso de 1024MiB.<br>
Agora onde são usados cada um deles?, bem, base 2 (binários) são comumente usados em espaço em disco e memória (ssd e ram), por terem uma maior precisão, já base 10 (decimais) para espaço em disco (hd).<br><br>
Por fim temos os não famigerados KBit ou MBit, que se for inteligente se deve ter entendido, lembre, 1 byte = 8bits, ou seja, 8x maior ou vise versa, em suma: 8GBit = 1GB.
