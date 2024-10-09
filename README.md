# Eduwekka
Arquivo arff
@relation desempenho_educacional

@attribute escola string
@attribute estado {BA, SP, RJ, MG, RS}
@attribute ideb_2021 numeric
@attribute pisa_matematica numeric
@attribute pisa_leitura numeric
@attribute pisa_ciencias numeric
@attribute regime_ensino {publica, privada}
@attribute turno {matutino, vespertino, integral}

@data
"Escola A", SP, 5.8, 475, 455, 470, publica, matutino
"Escola B", RJ, 6.2, 490, 480, 500, privada, integral
"Escola C", MG, 4.9, 430, 410, 420, publica, vespertino
"Escola D", BA, 6.0, 500, 490, 510, privada, matutino
"Escola E", RS, 5.5, 460, 450, 470, publica, integral
