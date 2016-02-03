# forLoop.// forLoop.cpp : Defines the entry point for the console application.
//

#include   "stdafx.h"

using   namespace  std;

int   _tmain ( int   argc ,  _TCHAR *  argv [])
{
	cout <<  "for loop: \n"  << endl;

	 //Example 1
	 for  ( int  index1 = 0; index1 < 10; index1++) 
	{
		cout <<  "Hello World! :)"  << endl;
	}
	cout << endl;

	 //Example 2
	 int  index2 = 4;
	 for  (index2; index2 < 8; index2++)
	{
		cout << index2 << endl;
	}
	cout << endl;

	 //Example 3
	 int  isPositive= -400;
	 int  index3 = 48;
	 for  (; isPositive <= 0;)
	{
		cout <<  "Inside the loop: isPositive = "  << isPositive << endl;
		isPositive += index3;
		index3 += 48;		
	}
	cout <<  "Out of the loop: isPositive = "  << isPositive << endl;
	cout << endl;

	 //Example 4
	cout <<  "This loop will execute till: indexA < indexB"  << endl;
	 for  ( int  indexA = 4, indexB = 16; indexA < indexB; indexA++, indexB--)
	{
		cout <<  "indexA = " << indexA <<  ", indexB = "  << indexB << endl;
	}
	cout << endl;

	 return  0;}
