# Saludos en GO

Este paquete proporciona una forma simplede obtener saludos de personas

## Instalación
Ejecuta el siguiente comando para instalar el paquete:
```bash
go get -u github.com/Reales09/greetings
```

## Uso
Aquí tienes un ejemplo de cómo utilizar el paquete en tu código:

```go

impot(
    "fmt"
    "github.com/Reales09/greetings"
)

func main(){
    message, err := greetings.Hello("Reales")

    if err != nil{
        fmt.Println("Ocurrió un error: ",err)
        return
    }
    fmt.Println(message)
}
```
Este ejemplo importa el paquete github.com/Reales09/greetings y llama  a la función Hello
saludos personalizado. Si ocurre un error, se impreme un mensaje de error.