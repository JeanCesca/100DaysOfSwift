# 100 Days Of Swift 💙

## Day 1 to 10: First steps in Swift

### Let (constante) & Var (variável)
1. Preferível utilizar inicialmente a constante "let" a variável "var".

### Arrays/Sets/Dictionaries
  Sets são coleções de valores assim como Arrays, exceto por duas diferenças:
    - Não há ordem no armazenamento (isso quer dizer que não consigo acessar os itens por index)
    - Nenhum item pode aparecer duas vezes em um Set; os itens precisam ser únicos.
    Ex: let colors = Set(["blue", "red", "white", "red"] //resulta em {"blue", "red", "white"}

  Tuples:
    - let myTuple = (name: "taylor", surname: "swift")
    // myTuple.0 = "Taylor"
    // myTuple.name = "Taylor"

  Dictionaries:
    - let heights = [
     "taylor swift": 1.78,
     "ed sheeran": 1.73
    ]   

  heights["taylor swift"] // 1.78

  Empty Array:
  let array = [Int]()

  Empty Dictionary:
  let dic = [String: String]()
  dic["John"] = ["Lennon"]

  Empty Set:
  let words = Set<String>()
  let numbers = Set<Int>()
  
### Enums
  
  enum Activity {
    case bored
    case running(destination: String)
    case talking(topic: String)
    case singing(volume: Int)
}
  let myTalk = Activity.talking(topic: "voleyball")
  
### Range operators
  
let score = 85

switch score {
case 0..<50:
    print("You failed badly.")
case 50..<85:
    print("You did OK.")
default:
    print("You did great!")
}
  
  //"You did great!"
  
## Day 1 to 10: First steps in Swift

  

