//Incio de codigo 

using System;

// Definimos una clase llamada Profesor
public class Profesor
{
    // Propiedad para guardar el nombre del profesor
    public string Nombre { get; set;}
}

// Definimos una clase llamada Departamento
public class Departamento
{
    // Propiedad para guardar el nombre del departamento
    public string Nombre { get; set;}
    
    // Método que recibe un objeto Profesor como parámetro
    public void MostrarProfesor(Profesor p)
    {
        // Imprime el nombre del profesor
        Console.WriteLine("Profesor: " + p.Nombre);
        
        // Imprime el nombre del departamento
        Console.WriteLine("Departamento: " + Nombre);
    }

}

// Clase principal del programa
class Program
{
    // Método principal donde inicia la ejecución
    static void Main()
    {
        // Creamos un objeto de tipo Profesor
        Profesor profe = new Profesor();
        
        // Le asignamos un nombre al profesor
        profe.Nombre = "Vera";
        
        // Creamos un objeto de tipo Departamento
        Departamento poo = new Departamento();
        
        // Le asignamos un nombre al departamento
        poo.Nombre = "Programacion Orientada a Objetos";
        
        // Llamamos al método MostrarProfesor y le pasamos el objeto profesor
        poo.MostrarProfesor(profe);
    }
}
