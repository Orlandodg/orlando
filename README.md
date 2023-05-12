# orlando
ejercicio 6
public class Temperatura {
    

      private double farenheit;
        private double celsius;


public Temperatura(double farenheit, double celsius){
       this.farenheit = farenheit;
       this.celsius = celsius;
       

}

    Temperatura() {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }
    public double getFarenheit() {
        return farenheit;
    }

    public double getCelsius() {
        return celsius;
    }

    public void setFarenheit(double farenheit) {
        this.farenheit = farenheit;
    }

    public void setCelsius(double celsius) {
        this.celsius = celsius;
    }
    public double  celsiusTofarenheit(){
      farenheit = (1.8)*(celsius + 32);
        return farenheit;
        
    }       
    public double farenheitTocelsius(){
       celsius =(farenheit - 32)/1.8;
        return celsius;
    }

    void setcelsius(double cel) {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    void setfarenheit(double cel) {
        throw new UnsupportedOperationException("Not supported yet."); // Generated from nbfs://nbhost/SystemFileSystem/Templates/Classes/Code/GeneratedMethodBody
    }

    

   
}

        
