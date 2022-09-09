# MP03 Grup 2T
# Avaluació Inicial

### Nom i cognoms:

1. Marca les UFs de primer d'aquest mòdul que tens superades:

    a- UF1 X

    b- UF2 X

    c- UF3 X

2. Has programat abans de començar els estudis de DAW? On? Quant de temps?

    Resposta: Sí 
    
    
    -A el grau mig de CFGM en el modúl d'introducció a la programació, durant tot l'any.


3. Què és compilar un programa?

    Resposta:
    
    
    - Significa fer la traducció del llenguatge de programació escrit a codi màquina.

4. Què és un llenguatge interpretat i en què es diferencia d'un llenguatge compilat?

    Resposta:


    - El llenguatge interpretat es pot executar directament y el compilat requereix traduir-se a codi màquina per executar-se

5. Quins llenguatges de programació has fet servir?

    Resposta: Java, PHP, Python, RStudio, JavaScript.


6. Quina diferència hi ha entre un lleguatge de programació d’alt nivell i un de baix nivell?

    Resposta: 


    - L'alt nivell no requereix ser traduït a codi màquina y pot ser llegible per una persona y el de baix nivell no

7. Explica què és un algorisme.

    Resposta:


    - És un conjunt d'operacions matemàtiques que realitzen una funció concreta

8. En el món de la programació Orientada a Objecte, digues quina diferència hi ha entre:

    a- Una classe i un objecte
    

    b- Una funció i un mètode
    
    
    
    Resposta d'a:


    -Una classe conté objectes i un objecte perteneix a una classe

    Resposta de b:


    -Una funció s'utilitza per solucionar un objectiu i un métode és una acció d'un objecte

9. Feu un programa, amb el llenguatge de programació que vulgueu, que calculi l’àrea d’un quadrat i mostri el resultat per pantalla.

    float areaSquare(float x){
      
      return x*x;
    
    }
    print(areaSquare(2));

9. Feu un programa (amb el llenguatge de programació que vulgueu) que, donat un número qualsevol, imprimeixi la seva taula de multiplicar.

    void printTable(int x){
      
      for(int i = 0; i++){
        
        int total = x * i;
        
        print(x + "" + i + " = " + total);
        
      }
    
    }
    printTable(3);

10. Quin és el resultat d'executar el següent programa?

```java
public class Vehicle{
    public boolean used;
    public String make;
    
    public static void main(String... args){
        Vehicle v = new Vehicle();
        if(v.used) {
            System.out.println(v.make);
        } else {
            System.out.println(v.make.length());
        }
    }
}
```

    a - null X
    b - 0
    c - Hi ha un error de compilació a la línia 7
    d - La línia 8 genera un error d'execució
    e - La línia 10 genera un error d'execució
