#include <iostream>
using namespace std;
int main () {
int n;
cin>>n;
int arr[n*2];
int sum = 0;
int count = 0;
for (int i = 0 ; i<n*2 ; i++)
{
    count++;
    cin>>arr[i];
    if (count%2==0)
    {
        sum+=arr[i];


    }

    }
for (int i = 0 ; i<n ; i++)
    cout<<sum<<endl;
}
