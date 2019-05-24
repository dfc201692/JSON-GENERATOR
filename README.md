# JSON-GENERATOR
https://www.json-generator.com/

PRACTICA UDEMY PRUEBA DESDE PAGINA WEB. SERVICES

[
  '{{repeat(1, 3)}}',
  {
    id: '{{index()}}',
    activo: '{{bool()}}',
    balance: '{{floating(1000, 4000, 2, "$0,000.000")}}',
    foto: 'http://placehold.it/32x32',
    edad: '{{integer(20, 40)}}',
    nombre: '{{firstName()}} {{surname()}}',
    genero: '{{gender()}}',
    compania: '{{company().toUpperCase()}}',
    email: '{{email()}}',
    direccion: '{{integer(100, 999)}} {{street()}}, {{city()}}, {{state()}}', 
    zip: '{{integer(100, 10000)}}'
    
  }
  ]
  
  
  
  EXCECUTE
  
  [
  {
    "id": 0,
    "activo": true,
    "balance": "$3,020.980",
    "foto": "http://placehold.it/32x32",
    "edad": 32,
    "nombre": "Samantha Glenn",
    "genero": "female",
    "compania": "MANTRIX",
    "email": "samanthaglenn@mantrix.com",
    "direccion": "738 Seabring Street, Derwood, Guam",
    "zip": 7338
  },
  {
    "id": 1,
    "activo": true,
    "balance": "$2,689.620",
    "foto": "http://placehold.it/32x32",
    "edad": 26,
    "nombre": "Schroeder Houston",
    "genero": "male",
    "compania": "PLUTORQUE",
    "email": "schroederhouston@plutorque.com",
    "direccion": "410 Commerce Street, Thomasville, Northern Mariana Islands",
    "zip": 6554
  },
  {
    "id": 2,
    "activo": true,
    "balance": "$3,854.560",
    "foto": "http://placehold.it/32x32",
    "edad": 20,
    "nombre": "Barbra Rowe",
    "genero": "female",
    "compania": "CORPORANA",
    "email": "barbrarowe@corporana.com",
    "direccion": "341 Highlawn Avenue, Imperial, Palau",
    "zip": 6294
  }
]
  
