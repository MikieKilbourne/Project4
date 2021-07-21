# Project4
Mikie Kilbourne submitted the Report on BrightSpace

  The Profile class has a simple constructor that sets all the fields to the parameters. It also has get and set methods for all of it's fields. 
  This class is used by the ProfileUsage class to make profiles, check if a profile has already been made, and allow the user to change attributes
  of their profile. I tested the Profile class by using the constructor in the main of the ProfileUsage, changing attributes of the profiles by
  using the set methods, and then printed them to make sure that they worked. 
  
  The ProfileUsage class is a large class that has the main that calls all other methods and classes in the project. It saves and retrieves all
  the profiles that have been made. It retrieves them at the beginning of the program and puts it into an arraylist of profiles. It then saves it
  at the end of the program. It also allow the user to either sign in to their profile or sign up and make a profile. The program prints errors if
  the user makes a mistake when making a profileand allows them to retry. If the user is signing up it makes sure that an account with that name has
  already been created. If they are signing up they input their name, age, gender and password. The account tells them if their password is weak,
  medium, or strong based on whether it has any numbesr or speica characters. If they are signing in they make sure that profile does indeed exist
  and allows them to access. Once they have either signed in or their account is created they can edit attributes using set methods from the Profile 
  class. They delete their profile by removing it from the arraylist of profiles. If they want to post or comment on a post the main calls the PostDriver. 
  The program exits when the user chooses to log out. I tested the class thoroughly by creating names, ages, and genders to make sure the error
  messages pop up. I checked that the strength of the password is correct by inputting several different password. I checked to see if all the attributes
  are changed in the profile when the set methods are called by printing the attributes by calling their get methods. I also tested to make sure that
  the profiles are saved and properly retrieved when the program starts back up by making several accounts, exitiing the program, and then trying to sign
  into them. All these tests were succesful. 
