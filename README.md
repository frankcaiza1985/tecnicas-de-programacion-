# tecnicas-de-programacion-
   public class Camion : Vehiculo
    {
        public override void mostrarDatos()
        {
            base.mostrarDatos();
            Console.WriteLine("Capacidad de carga: " + capacidadCarga);
        }
    }
 public class Coche : Vehiculo
    {

        public override void mostrarDatos()
        {
            
            base.mostrarDatos();
            Console.WriteLine("Numero de puertas: " + numeroPuertas);
        }
    }

public class Moto : Vehiculo
    {
      
        public override void mostrarDatos()
        {
            base.mostrarDatos();
            Console.WriteLine("Cilindrada: " + cilindrada);
        }
    }
