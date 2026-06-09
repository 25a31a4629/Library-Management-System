#include <iostream>
#include <string>
using namespace std;

int main()
{
    string books[5];
    int count = 0;
    int choice;

    do
    {
        cout << "\n1. Add Book";
        cout << "\n2. Display Books";
        cout << "\n3. Exit";
        cout << "\nEnter Choice: ";
        cin >> choice;

        switch(choice)
        {
            case 1:
                if(count < 5)
                {
                    cout << "Enter Book Name: ";
                    cin.ignore();
                    getline(cin, books[count]);
                    count++;
                }
                else
                {
                    cout << "Library Full!";
                }
                break;

            case 2:
                cout << "\nBooks Available:\n";
                for(int i = 0; i < count; i++)
                {
                    cout << i + 1 << ". " << books[i] << endl;
                }
                break;

            case 3:
                cout << "Exiting...";
                break;

            default:
                cout << "Invalid Choice";
        }

    } while(choice != 3);

    return 0;
}
