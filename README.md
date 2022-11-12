# competitve-coding
pattern questions with output
/*#include <iostream>
using namespace std;
int main()
{
    int n;
    cout<<"enter the details for the patterns \n sir\n";
    cin>>n;
    int i,j,ele;
    for(i=1;i<=n;i++)
    {
        for(j=1;j<=i;j++)
        {
            
            if((i+j)%2==0)
            {
                cout<<" 1  ";
            }
            else
            {
                cout<<" 0";
            }
            cout<<endl;
        }*/
        #include <iostream>
        using namespace std;
        int main()
        {
            int i,j,n;
            cin>>n;
            
            for(i=1;i<=n;i++)
            {
                for(j=1;j<=i;j++)
                {
                    int ele=i+j;
                    if(ele%2==0)
                    {
                        cout<<"1";
                    }
                    else{
                        cout<<"0";
                    }
                }
                 cout<<endl;//remember the pos of endl after ending of each row
                 
            }
           
        }

    
