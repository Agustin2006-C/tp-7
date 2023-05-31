using namespace std;

int contarletraA (string f);

int main() 
{
	string frase;
	cout<<"ingrese frase"<<endl;
	getline(cin,frase);
	cout<<"contador de letras A:"<<contarletraA(frase);

return 0;
} 	
	int contarletraA(string f)
	
	 
	{int i;int cont=0;
	
	for(i=0;i<f.size();i++)
	
	{
		if(f[i]=='a'||f[i]=='A')
		{cont++;}
	}
	
	return cont;
}
