# lecture-12

    #include <iostream>
    #include <string>
    using namespace std;

    int main()
    {
        int ages[5];

        ages[0] = 19;
        ages[1] = 23;
        ages[2] = 22;
        ages[3] = 30;
        ages[4] = 18;
    }

    int main()
    {
        int array[5] = { 19, 23, 22, 30, 18 };
    }

    int main()
    {
      string months[12];

      string months = { "Jan", "Feb", "March", "April", "May", "June", "July", "Aug", "Sept", "Oct", "Nov", "Dec" };

    }

    int main()
    {
      int heartRates[8] = { 54, 60, 71, 59, 62, 63, 60, 58 };
      cout << heartRates[3] << endl;
      cout << heartRates[6] << endl;

    }

    int main()
    {
      int heartRates[8] = { 54, 60, 71, 59, 62, 63, 60, 58 };

      for (int i = 0; i < 8; i++) {
        cout << heartRates[i] << endl;
      }

    }

    int main()
    {
      string months[12] = { "January", "Febuary", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December" };

      for (int i = 0; i < 12; i++) {
        cout << months[i] << endl;
      }
    }

    int main()
    {
      int marks[5];
      float intput, sum = 0.0, avg;

      for (int i = 0; i < 5; i++) {
        cout << "Enter your grades:" << endl;
        cin >> marks[i];

        while (cin.fail()) {
          cin.clear();
          cin.ignore(100, '\n');
          cout << "Please enter a valid grade:" << endl;
          cin >> marks[i];
        }
        sum += marks[i];
      }
      avg = sum / marks[5];
      cout << "The average is =" << avg << endl;

      cout << "This are the values you entered." << endl;
      for (int j = 0; j < 5; j++) {
        cout << "\nThis are the values you entered." << endl;
        cout << marks[j];
      }

    }
