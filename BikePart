public class BikePart {
    private String name;
    private int number;
    private double price;
    private double salesPrice;
    private boolean onSale;

    public BikePart(String name, int number, double price, double salesPrice, boolean onSale) {
        this.name = name;
        this.number = number;
        this.price = price;
        this.salesPrice = salesPrice;
        this.onSale = onSale;
    }

    public String getName() {
        return name;
    }

    public void setName(String name) {
        this.name = name;
    }

    public int getNumber() {
        return number;
    }

    public void setNumber(int number) {
        this.number = number;
    }

    public double getPrice() {
        return price;
    }

    public void setPrice(double price) {
        this.price = price;
    }

    public double getSalesPrice() {
        return salesPrice;
    }

    public void setSalesPrice(double salesPrice) {
        this.salesPrice = salesPrice;
    }

    public boolean isOnSale() {
        return onSale;
    }

    public void setOnSale(boolean onSale) {
        this.onSale = onSale;
    }

    @Override
    public boolean equals(Object o) {
        if (this == o) return true;
        if (o == null || getClass() != o.getClass()) return false;
        BikePart bikePart = (BikePart) o;
        if (number != bikePart.number) return false;
        return name != null ? name.equals(bikePart.name) : bikePart.name == null;

    }

    @Override
    public String toString() {
        return "BikePart{" +
                "name='" + name + '\'' +
                ", number=" + number +
                ", price=" + price +
                ", salesPrice=" + salesPrice +
                ", onSale=" + onSale +
                '}';
    }
}
