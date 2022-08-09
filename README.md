# 100DaysOfSwift

## Day 1 to 10: First steps in Swift

### Let/Var
1. Preferível utilizar inicialmente a constante "let" a variável "var".

2. Sets são coleções de valores assim como Arrays, exceto por duas diferenças:
- Não há ordem no armazenamento (isso quer dizer que não consigo acessar os itens por index)
- Nenhum item pode aparecer duas vezes em um Set; os itens precisam ser únicos.
Ex: let colors = Set(["blue", "red", "white", "red"] //resulta em {"blue", "red", "white"}

3. Tuples:
- let myTuple = (name: "taylor", surname: "swift")
// myTuple.0 = "Taylor"
// myTuple.name = "Taylor"

4. Dictionaries:
- let heights = [
  "taylor swift": 1.78,
  "ed sheeran": 1.73
]

heights["taylor swift"] // 1.78

5. Empty Array:
let array = [Int]()

6. Empty Dictionary:
let dic = [String: String]()
dic["John"] = ["Lennon"]

7. Empty Set:
let words = Set<String>()
let numbers = Set<Int>()
