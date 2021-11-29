# Cplus2.0-forloops-2
my first repository(1st sem hands on exam in coc) determining the students record, name and grades in subjects.

#include<iostream>
using namespace std;
int main()
{
    //declare used variables
    string isfirstName, islastName, isyearlevel;
    int eng, math, sci, pe, fil, his, total;
    int i;
    float average;
   
      for (i=1;i>0,i--;){
	//ask user's details
    cout << "\nFirst Name:"<<endl;
    getline(cin, isfirstName) ;
    
    cout << "\nLast Name:"<<endl;
    getline(cin, islastName);
    
    cout << "\nYear and Level:"<<endl;
    getline(cin, isyearlevel);
    
    
    //ask user to input grades in every subject
    cout << "\nInput grade in English: ";
    cin >> eng;
    
    cout << "\nInput grade in Math: ";
    cin >> math;
    
    cout << "\nInput grade in Science: ";
    cin >> sci;
    
    cout << "\nInput grade in PE: ";
    cin >> pe;
    
    cout << "\nInput grade in Filipino: ";
    cin >> fil;
    
    cout << "\nInput grade in History: ";
    cin >> his;
  
     
    //Calculation
    total = eng+math+sci+pe+fil+his;
    average = total/6;
    
    
    //print result
     cout << "\nStudent Record: ";
     cout <<"\nName: "<<isfirstName<<""<<islastName;
     cout <<"\nAverage: "<<average;
    }
    return 0;
}
  /*output:
  first name: iren
  last name: salazar
  year and level: 1st year college
  input grade in english: 99
  input grade in math: 99
  input grade in Science: 99
  input grade in Filipino: 99
  input grade in History: 99
  
  student record:
  name: irensalazar
  average: 99 */
  
  
  */
