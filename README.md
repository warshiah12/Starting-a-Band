# Starting-a-Band
Lecture 7 exercise 4
#include<iostream>
#include<string>
using namespace std;
int main()
{
	bool musicfriend= true ;  //declaring variable with datatype bool
	string instrument ;            //declaring variable with datatype
	if (musicfriend == true)  //using nested if else
{
		cout << "Enter the instrument you can play (Guitar or Drum) : " << endl;
		cin >> instrument;
		if (instrument == "drum" || instrument=="DRUM") //using else if statement
		{
			cout << "Yay you can play drum! Can you join my Band? " << endl;
	    }
		else if(instrument=="guitar"|| instrument=="GUITAR")
		{
			cout << "Yay you can play Guitar! Can you join my Band? " << endl;
		}
		else
		{
			cout << "You cannot join the band. I need someone who can play guitar or drum." << endl;
		}
}
	else
	{
		cout << "Looks like i can't form my own band " << endl;
	}	
	return 0;
}
