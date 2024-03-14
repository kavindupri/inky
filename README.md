public class Inky{
    public Inky(String pinky){
        System.out.println(pinky);

    }

    public Inky(String  pinky,String Blinky,String Rinky){
        System.out.println(Blinky + "" + pinky);
        System.out.println(pinky + "" + Rinky);
        System.out.println(Blinky + "" + pinky+""+ Rinky);

    }
    public static void main(String[] args) {
        String pinky ="Donkey";

        Inky ponky = new Inky(pinky);

        String Blinky ="pinky";
        String Rinky = "Monkey";
        Inky ponky2 = new Inky(pinky,Blinky,Rinky);
    }
}
