"# 323-prac4c" 

Calculator Microservice
Description
This is a calculator microservice built using Node.js and the Express framework. It provides basic mathematical operations, including addition, subtraction, multiplication, division, exponentiation, square root and modulo.

Basic operations: Addition, Subtraction, Multiplication, Division
Advanced operations: Exponentiation, Square Root, Modulo

New API Endpoints:
Exponentiation
Endpoint: POST /exponentiate
Request Body:{ "base": 2, "exponent": 3 }
Response:{ "result": 8 }

Square Root
Endpoint: POST /squareRoot
Request Body:{"num": 16}
Response:{"result": 4}

Modulo
Endpoint: POST /modulo
Request Body:{"dividend": 10, "divisor": 3}
Response:{ "result": 1 }
