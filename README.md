# Moves-zeros-

#include<iostrem>
using namespace std;
int main(){
int n;
int arr[n];
cout<<" enter a element of array";
int j = 0;
for(int i = 0;i<n;i++){
cin>>arr[n];
}
for (int i = 0; i < n; i++) {
        if (A[i] != 0) {
            swap(A[j], A[i]);
            j++;
        }
    }
    for (int i = 0; i < n; i++)  {
        cout << A[i] << " ";
    }
    return 0;
    };
