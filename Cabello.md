public class Cabello {
    private String estado;

    public Cabello() {
        this.estado = "Seco";
    }

    public void mojar() {
        estado = "Mojado";
        System.out.println("El cabello esta mojado.");
    }

    public void enjuagar() {
        estado = "Enjuagado";
        System.out.println("El cabello ha sido enjuagado.");
    }

    public void secar() {
        estado = "Seco";
        System.out.println("El cabello esta seco.");
    }

    public void desenredar() {
        System.out.println("El cabello ha sido desenredado.");
    }

    public String getEstado() {
        return estado;
    }
}
