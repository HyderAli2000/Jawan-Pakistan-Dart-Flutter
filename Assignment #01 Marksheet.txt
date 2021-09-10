void main() {
  print("------------------------------MARKSHEET------------------------------\n");
  
  double eng_marks = 69.5;
  double urdu_marks = 61;
  double maths_marks = 60.5;
  double phy_marks = 71;
  double chem_marks = 56;
  double total_marks = 500;
  
  print("YOUR TOTAL MARKS CORSE WISE\nEnglish: $eng_marks \nUrdu: $urdu_marks \nMaths: $maths_marks \nPhysics: $phy_marks \nChemistry: $chem_marks\n");
  
  if (eng_marks >= 60){
    print("Cleared in English exam!");
  }
  else{
    print("Failed in English!");
  }
  
  if (urdu_marks >= 60){
    print("Cleared in Urdu exam!");
  }
  else{
    print("Failed in Urdu!");
  }
  
  if (maths_marks >= 60){
    print("Cleared Maths exam!");
  }
  else{
    print("Failed in Maths!");
  }
  
  if (phy_marks >= 60){
    print("Cleared Physics exam!");
  }
  else{
    print("Failed in Physics!");
  }
  
  if (chem_marks >= 60){
    print("Cleared in Chemistry exam!");
  }
  else{
    print("Failed in Chemistry!");
  }
  
  double marks_obt = eng_marks + urdu_marks + maths_marks + phy_marks + chem_marks;
  double per = marks_obt / total_marks  * 100;
  print("\nYour Percentage is: $per");
  
  if (per >= 60 && per < 70){
    print("\nYou've Secured $per% with C grade and $marks_obt Total marks");
  }
  else if (per >= 70 && per < 73){
    print("\nYou've Secured $per% with C+ grade and $marks_obt Total marks");
  }
  else if (per >= 73 && per < 79){
    print("\nYou've Secured $per% with B grade and $marks_obt Total marks");
  }
  else if (per >= 79 && per < 87){
    print("\nYou've Secured $per% with B+ grade and $marks_obt Total marks");
  }
  else if (per >= 87){
    print("\nYou've Secured $per% with A grade and $marks_obt Total marks");
  }
  else{
    print("\nF grade");
  }
}
