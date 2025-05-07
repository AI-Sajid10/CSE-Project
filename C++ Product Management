//Bismillahir Rahmanir Raheem
#include<bits/stdc++.h>
using namespace std;
class product{
private:
	int p_id;
	string p_name;
	string p_company;
	double p_price;
public:
	void set_product()
	{
		cout<< "Enter Product ID: ";
		cin>> p_id;
		cout<< "Enter product Name: ";
		cin>> p_name;
		cout<< "Enter Product Company: ";
		cin>> p_company;
		cout<< "Enter Price: ";
		cin>> p_price;
	}
	void Display()
	{
		cout<< "Product ID: "<< p_id<<endl;
		cout<< "Product Name: "<<p_name<<endl;
		cout<< "Company: "<< p_company<< endl;
		cout<< "Price: "<< p_price<< endl;
	}
	int get_id()
	{
		return p_id;
	}

};
int main()
{
	int n;
	cout<< "\nEnter Number of Products: ";
	cin>> n;
	product p[100];
	for(int i = 0; i < n; i++)
	{
		cout<< "\nEnter Details for Product "<< i+1<< ":\n";
		p[i].set_product();
	}

	int search_id;
	cout<< "\nEnter Product ID to Search: ";
	cin>> search_id;

	bool found = false;
	for(int i = 0; i < n; i++)
	{
		if(p[i].get_id() == search_id){
			cout<< "\nProduct Found\n";
			p[i].Display();
			found = true;
			break;
		}
	}

	if(!found){
		cout<< "Product NOT Found.\n";
	}
	return 0;
}
