// Vehicle.java
class Vehicle {
    public void drive() {
        System.out.println("Driving a vehicle");
    }
}

// Car.java
class Car extends Vehicle {
    @Override
    public void drive() {
        System.out.println("Repairing a car");
    }
}


public class Main {
    public static void main(String[] args) {
        Vehicle myVehicle = new Vehicle();
        myVehicle.drive(); 

        Car myCar = new Car();
        myCar.drive();       
    }
}
