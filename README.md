# calculator

Пример работы калькулятора

CMD:

C:\Users\пк>curl -X POST -H "Content-Type: application/json" -d "{\"num1\": 25, \"num2\": 5}" http://localhost:5000/add

{
  "result": 30
}

C:\Users\пк>curl -X POST -H "Content-Type: application/json" -d "{\"num1\": 25, \"num2\": 5}" http://localhost:5000/subtract

{
  "result": 20
}

C:\Users\пк>curl -X POST -H "Content-Type: application/json" -d "{\"num1\": 25, \"num2\": 5}" http://localhost:5000/multiply

{
  "result": 125
}

C:\Users\пк>curl -X POST -H "Content-Type: application/json" -d "{\"num1\": 25, \"num2\": 5}" http://localhost:5000/divide

{
  "result": 5.0
}
