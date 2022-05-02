package edu.handong.csee.java.lab07.string;

public class FamilyNamePrinter{
    private String[] stringNames;
    private String[] familyNames;

    public static void main(String[] args){
        FamilyNamePrinter name = new FamilyNamePrinter(args[0]);
        name. printFamilyNames();

    }
    public FamilyNamePrinter(String names){
        this.stringNames = names.split(",");
        for (String Name : stringNames){
            for (int i=0; i<stringNames.length ; i++){
                stringNames[i] = stringNames[i].trim();
                familyNames = stringNames[i].split(" ");
                Name = familyNames[1];
                System.out.println(Name);
            
            }
            break;
        }
    
    }

    public String[] printFamilyNames(){
        return familyNames;
    }
    
}
