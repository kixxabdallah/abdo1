#include <iostream>
#include <vector>
#include <string>
using namespace std;

int main()
{     
    //int n, m, a;  //n= long of garden , m = width of garden , a =long of square  
        //cout << "the long of gatden = ";
        //cin >> n;
        //cout << "the width of garden = ";
        //cin >> m;
        //cout << "the long of square = ";
        //cin >> a;
        //if (n % a == 0) {
        //n = n / a;
        //}
        //else {
        //    n = (n / a) + 1;
        //}
        //if (m % a == 0) {
        //    m = m / a;
        //}
        //else {
        //    m = (m / a) + 1;
        //}
        // a= n*m ;
        //cout << "total = " << a << endl; // 1
    ///////////////////

    //////////////////////////////////////////////

       /* int n;  
        cin >> n;  
        int count = 0;  
        for (int i = 0; i < n; i++) {
            int a, b, c;
            cin >> a >> b >> c;  
            if (a + b + c >= 2) {
                count++;  
            }
        }
        cout << count << endl; *///2
    ///////////////////////////////////////////////////


   /*
        int n, temperature = 0;
        cin >> n; 
        while (n--) {
            string command;
            cin >> command;  

            if (command[1] == '+')
                temperature++;
            else  
                temperature--;  
        }
        cout << temperature << endl; */
    ///////////////////////////////////////////
  
        //int n;
        //cin >> n;  
        //vector<string> catalog;  
        //for (int i = 0; i < n; i++) {
        //    string title;
        //    cin >> title;  
        //    bool found = false;  
        //    
        //    for (int j = 0; j < catalog.size(); j++) {
        //        if (catalog[j] == title) {  
        //            found = true;  
        //            break;
        //        }
        //    }
        //    if (found) {  
        //        int count = 1;
        //        string newTitle = title + to_string(count);
        //        while (true) {
        //            bool unique = true;
        //            for (int j = 0; j < catalog.size(); j++) {
        //                if (catalog[j] == newTitle) {
        //                    unique = false;  
        //                    break;
        //                }
        //            }
        //            if (unique) break;  
        //            count++;
        //            newTitle = title + to_string(count);  
        //        }
        //        catalog.push_back(newTitle);  
        //        cout << newTitle << endl;  
        //    }
        //    else {
        //        catalog.push_back(title); 
        //        cout << "OK" << endl; 
    ////////////////////////////////////////
    ////////////////////////////////

    /////////////////////////////////
       /* string x;
        cin >> x; 

        for (int i = 0; i < x.length(); i++) {
            int digit = x[i] - '0'; 

            
            if (i == 0 && digit == 9) {
                continue;  
            }
            if (9 - digit < digit) {
                x[i] = '0' + (9 - digit);  
            }
        }

        cout << x << endl; */ 



}

