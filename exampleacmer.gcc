#include <iostream>
using namespace std;


void value(int array[], int lenghtallx, int lenghtfirstx){
	int size;
	cout << lenghtallx << endl;
	cout << lenghtfirstx << endl;
	size = lenghtallx / lenghtfirstx ;
	 cout << size << endl;


	for (int j = 1 ; j < size ; j++){
		int key = array[j];
		int i = j - 1;
		while(i >= 0 and array[i] > key) {
			array[i + 1] = array[i];
			i = i -1; 
		}

		array[i + 1] = key;

	}
	
	for ( int k = 0; k < size; k++) {
		cout << array[k] << endl;
		cout << "\n" << endl;
	}  
}

int main() {
	int  example1[] ={2,3,4,9,8,7,1,5};
	int lenghtall = sizeof(example1); 
	int lenghtfirst = sizeof(example1[0]);
	cout << lenghtall << endl;
	cout << lenghtfirst << endl;

	value(example1, lenghtall, lenghtfirst);
	 return 0;
}






	
