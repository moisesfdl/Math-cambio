# Math-cambio
em analise pra desenvolver 

#include <iostream>
#include <math.h>
#include <stdio.h>
#include <tchar.h>
using namespace std;
struct LetraCambio
{
	int BBD;
	int TEL;
	int GM;
	int V;
	int EUR;
	LetraCambio(){
		cout<<"BBD  ==  BRADESCO\n";
		cout<<"TEL == Telefonica Brasil\n";
		cout<<"GM == General Motors\n";
		cout<<"V == visa\n";
		cout<<"EUR == Moeda\n";
		}
};
struct ValorDolar
{
	int DolarHoje;
	ValorDolar(){
		cout<<"Dolar Hoje == $ + valor\n";
	}
};
struct ValorLetraCambio
{
	int ValorMargin;
	ValorLetraCambio(){
		cout<<"valor Margem na correçao bolsa\n";
	}
};
float multiplicar(float Num1, float Num2);
void moisesfdl();void global();void calc();
int main(int argc, char** argv)
{
	int *ptr;
	int cpf  = '275.551.158-32';
	moisesfdl();
	*ptr == cpf;
	return cpf;
}
void moisesfdl(){
	calc();
}
void global(){
	ValorDolar global;
	if(moisesfdl)
	{
		cout<<"Valor Dolar do dia [";
		cout<<sizeof(global.DolarHoje);
		cout<<"]\n";
	}
}
void calc(){
	float Num1, Num2;
	global();
	if(moisesfdl)
	{
		cout<<"calculo de conversao de moeda dolar US pra BRL [";
		multiplicar(Num1, Num2);
		cout<<sizeof(LetraCambio)<<"*"<<sizeof(ValorLetraCambio)<<"*"<<sizeof(ValorDolar);
		cout<<"]\n";
	}
}
float multiplicar(float Num1, float Num2){
	return Num1 * Num2;
}
