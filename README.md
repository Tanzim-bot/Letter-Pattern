#include <iostream>
using namespace std;
int main() 
{
	//Will Create an array of characters 'A' through 'G'.
   
	char letter [7] = { 'A', 'B', 'C', 'D', 'E', 'F', 'G' };

	//This outer loop illustrates through each row of the pattern(7 rows).

	for (int a = 0; a < 7; a++)
	{
		// This loop adds leading spaces before the letters in each row.
	   // The number of spaces decreases as we move down the rows.
		for (int b = 0; b < 6 - a; b++)
		{
			cout << " ";
		}
		for (int c = 0; c <= a; c++)
		{
			cout << letter[a];
		}
		cout << endl;
	}

    return 0;
