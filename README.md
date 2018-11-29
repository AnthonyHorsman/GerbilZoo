package Gwhale;

/**
 *
 * @author Anthony
 */
class Gwhale{
    // attributes
    int NumberOfTeeth = 2;
    int length;
    int TopSpeed;
    
    
    String Habitat = "I live in the ocean but can walk on land";
    String MatingCall = "I squeal like a gerbil as my mating call";
    String Diet = "I am a carnivore";
    
    public void getName(String myName)
    {
        Name = myName;
        System.out.println("My name is " + Name + " and I am a dolphin.");
    }
    public void FoodDiet()
    {
        System.out.println(Diet);
    }
    public void Pod()
    {
        System.out.println(PodType + " with other dolphins.");
    }
    public void Attributes(int weight, int length, int TopSpeed)
    {
        System.out.println("The rough average weight of all dolphins is " + weight + " lbs and the average length of all dolphins is " + length + " feet. Dolphins are also very fast and can reach speeds up to " + " mph." );
    }
}
