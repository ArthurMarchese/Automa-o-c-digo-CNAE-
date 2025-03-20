(function (cnae) {
if (typeof(cnae) !== "string") {
cnae = cnae.toString();
}
let inicio_cnae = parseInt(cnae.slice(0, 2));
const categorias = {
Agronegócio: [1, 2, 3],
"Indústrias extrativas": [5, 6, 7, 8, 9],
"Indústrias de transformação": [
10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25,
26, 27, 28, 29, 30, 31, 32, 33
],
"Eletricidade e gás": [35],
"Água e saneamento": [36, 37, 38, 39],
"Construção civil": [41, 42, 43],
Comércio: [45, 46, 47],
Logístico: [49, 50, 51, 52, 53],
"Alojamento e alimentação": [55, 56],
Comunicação: [58, 59, 60, 61, 62, 63],
"Serviços financeiros": [64, 65, 66],
"Serviços administrativos": [77, 78, 79, 80, 81, 82],
Educação: [85],
Saúde: [86, 87, 88]
};
for (let categoria in categorias) {
if (categorias[categoria].includes(inicio_cnae)) {
return categoria;
}
}
return "Não cadastrado";
})("[Cliente.Código CNAE]");
