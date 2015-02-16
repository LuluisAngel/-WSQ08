# -WSQ08
Here's the code
// Luis Angel Aguilar Carrillo A01225421

      #include <iostream>
      
      using namespace std;
      
      int suma(int a, int b){
      
      	return a+b;
      }
      
      int resta(int a, int b){
      
      	return a-b;
      }
      
      int mult(int a, int b){
      
      	return a*b;
      }
      
      int div(int a, int b){
      
      	return (a/b);
      }
      
      int mod(int a, int b){
      
      	return a%b;
      }
      
      int main(){
      
      	int x, y;
      
      	cout << "Introduce un numero" << endl;
      	cin >> x;
      
      	cout << "Introduce el segundo numero" << endl;
      	cin >>y;
      
      	cout << "La suma de " << x << " + " << y << " es = " << suma(x,y) << endl;
      	cout << "La resta de " << x << " - " << y << " es = " << resta(x,y) << endl;
      	cout << "La multiplicación de " << x << " * " << y << " es = " << mult(x,y) << endl;
      	cout << "La division de " << x << " / " << y << " es = " << div(x,y) << endl;
      	cout << "El residuo (mod) de " << x << " / " << y << " es = " << mod(x,y) << endl;
      
      
      	return 0;
      }
