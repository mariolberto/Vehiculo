# Vehiculo
en este código vamos a usar lo que es getter y setter
public class Vehiculo { 
    // ATRIBUTOS
    private double precio; 
    private String marca;
    private String modelo;
    private String color;  

    // METODOS
    // Constructor
    public Vehiculo (String marca,String modelo,double precio, String color ){
      this.precio=precio;
      this.marca=marca;
      this.modelo=modelo;
      this.modelo=color;
    }
    // getters
    public double getPrecio() {
        return precio;
    }

    public String getMarca() {
        return marca;
    }

    public String getModelo() {
        return modelo;
    }

    public String getColor() {
        return color;

    // setters
    public void setPrecio (int precio) {
        this.precio=precio;
    }

    public void setMarca (String marca) {
        this.marca=marca;
    }

    public void setModelo (String modelo) {
        this.modelo=modelo;
    }

    public void setColor (String color) {
        this.color=color;
    }

    //CON ESO HACEMOS ESTA FUNCION QUE PIDIO EN CLAES DEL METODO VEHICULO Y USAMOS EL GETTER Y SETTER

}
