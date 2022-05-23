public class Main {
    public static void main(String [] args){

        double grav = -9.81; // Earth's gravity in m/s^2
        double initialVelocity = 0.0;
        double fallingTime = 12.0;
        double initialPosition = 0.0;
        double finalPosition = 2.0;

        finalPosition=(0.5*grav*fallingTime+ initialVelocity)*fallingTime + initialPosition;

        System.out.println("The object's position after " + fallingTime +
                " seconds is " + finalPosition + " m.");
    }
}
